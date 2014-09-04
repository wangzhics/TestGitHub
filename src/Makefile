CC = gcc -Wall

all: helloworld

clean :
	rm -f *.o helloworld

helloworld: helloworld.o
	${CC} -o helloworld helloworld.o

helloworld.o:
	${CC} -c helloworld.c
	
