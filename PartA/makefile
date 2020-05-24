#!make -f

CC = gcc -ggdb
SAN = -fsanitize=address -static-libasan -fno-omit-frame-pointer

testc: testc.c
	$(CC) -o testc testc.c $(SAN) && ./testc