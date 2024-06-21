
all: hello.o greeting.o
	gcc hello.o greeting.o -o hello

greeting.o: greeting.c greeting.h
	gcc -c greeting.c

hello.o: hello.c
	gcc -c hello.c

clean:
	rm *.o hello

