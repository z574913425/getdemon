test2:main.o fun.o
	gcc main.o fun.o -o test2
main.o:main.c
	gcc main.c -c
fun.o:fun.c
	gcc fun.c -c
clean:
	rm -f *.o
