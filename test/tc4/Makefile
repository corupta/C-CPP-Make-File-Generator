INCDIR =	-I"." -I"./headers4" -I"./src4"

tc4.exe:	main4.o multTwoInt.o addTwoInt.o
		gcc main4.o multTwoInt.o addTwoInt.o -o tc4.exe
		@echo "Makefile finished successfully. Created program: tc4.exe"

main4.o:	./headers4/addTwoInt.h ./headers4/multTwoInt.h
		gcc -c $(INCDIR) ./main4.c

multTwoInt.o:	./headers4/multTwoInt.h
		gcc -c $(INCDIR) ./src4/multTwoInt.c

addTwoInt.o:	./headers4/addTwoInt.h
		gcc -c $(INCDIR) ./src4/addTwoInt.c

