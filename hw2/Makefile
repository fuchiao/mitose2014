CC=gcc
all: a.out t.sh
	./a.out < t.sh
a.out: sh.c
	$(CC) sh.c
clean: a.out
	rm a.out

