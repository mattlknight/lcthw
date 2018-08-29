CFLAGS=-Wall -g -static

ex1: ex1.c
	cc -Wall -g -static ex1.c -o ex1
	strip ex1
	ls -alh ex1
	file ex1
	-ldd ex1

.PHONY: clean
clean:
	-rm -f ex1
