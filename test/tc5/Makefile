INCDIR =	-I"." -I"./headers5" -I"./headers5/headers5_2" -I"./src5"

tc5.exe:	main5.o multTwoInt.o addTwoInt.o
		gcc main5.o multTwoInt.o addTwoInt.o -o tc5.exe
		@echo "Makefile finished successfully. Created program: tc5.exe"

main5.o:	./headers5/addTwoInt.h ./headers5/headers5_2/multTwoInt.h
		gcc -c $(INCDIR) ./main5.c

multTwoInt.o:	./headers5/headers5_2/multTwoInt.h
		gcc -c $(INCDIR) ./src5/multTwoInt.c

addTwoInt.o:	./headers5/addTwoInt.h
		gcc -c $(INCDIR) ./src5/addTwoInt.c

