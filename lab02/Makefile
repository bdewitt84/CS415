all : lab2.exe


lab2.exe: command.o string_parser.o 
	gcc -o lab2.exe command.o string_parser.o


command.o: command.c command.h
	gcc -c command.c

string_parser.o: string_parser.c string_parser.h
	gcc -c string_parser.c

clean:
	rm -f core *.o lab2.exe

