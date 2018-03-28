simplecalculator: add.o subtract.o main.o
	gcc -o simplecalculator add.o subtract.o main.o
add.o :add.c
	gcc -c -o add.o add.c
subtract.o : subtract.c
	gcc -c -o subtract.o subtract.c
main.o : main.c
	gcc -c -o main.o main.c
clean :
	rm *.o simplecalculator
