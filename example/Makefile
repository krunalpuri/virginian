CC = gcc
LIB = ../lib
CUDA = /usr/local/cuda

all: test.c
	$(CC) -I$(LIB) -I$(CUDA)/include -L$(CUDA)/lib -lcudart test.c $(LIB)/virginian.a -o test
	./test

clean:
	rm -rf test

