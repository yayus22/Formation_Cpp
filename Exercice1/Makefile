
OPTIONS = -o2 -Wall

all : exercice1

exercice1 : exercice1.h exercice1.o
	g++ ${OPTIONS} -o exercice1 exercice1.o

exercice.o : exercice1.cpp exercice1.h
	g++ ${OPTIONS} -c -o exercice.o exercice1.cpp

clean :
	rm -rf exercice *.o