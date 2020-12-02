all:
	gcc -g -c -Wall principal.c -o principal.o
	gcc -g -c -Wall MetodoSimplex.c -o MetodoSimplex.o
	gcc -g -Wall principal.o MetodoSimplex.o -o Simplex

clean:
	rm -r *.o
	#rm -r application