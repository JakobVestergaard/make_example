
readfromfile: main.o SingleDash.o DoubleDash.o Options.o
	g++ -o readfromfile main.o SingleDash.o DoubleDash.o Options.o

Options: Options.cpp Options.h
	g++ -o Options.o Options.cpp Options.h

SingleDash: SingleDash.cpp SingleDash.h
	g++ -o SingleDash.o SingleDash.cpp SingleDash.h

DoubleDash: DoubleDash.cpp DoubleDash.h
	g++ -o DoubleDash.o DoubleDash.cpp DoubleDash.h

clean:
	rm -f main.o SingleDash.o DoubleDash.o Options.o
