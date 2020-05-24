#!make -f

CC = gcc -ggdb
SAN = -fsanitize=address -fno-omit-frame-pointer

testc: testc.c
	$(CC) -o testc testc.c $(SAN) && ./testc