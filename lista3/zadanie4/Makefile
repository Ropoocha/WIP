all: main

main: main.o newagent.o north.o south.o east.o west.o distance.o
	clang -o zadanie4.out main.o newagent.o north.o south.o east.o west.o distance.o -lm

main.o: main.c
	clang -c main.c

newagent.o: newagent.c
	clang -c newagent.c

north.o: north.c
	clang -c north.c

south.o: south.c
	clang -c south.c
	
east.o: east.c
	clang -c east.c

west.o: west.c
	clang -c west.c

distance.o: distance.c
	clang -c distance.c

clean:
	rm -f zadanie4.out *.o *~
