INCDIR =	-I"." -I"./pat pat" -I"./dom" -I"./bom"

tc2.exe:	main2.o addTwoInt.o multTwoInt.o
		gcc main2.o addTwoInt.o multTwoInt.o -o tc2.exe
		@echo "Makefile finished successfully. Created program: tc2.exe"

main2.o:	./addTwoInt.h ./dom/multTwoInt.h
		gcc -c $(INCDIR) ./main2.c

addTwoInt.o:	./addTwoInt.h
		gcc -c $(INCDIR) ./addTwoInt.c

multTwoInt.o:	./dom/multTwoInt.h
		gcc -c $(INCDIR) ./dom/multTwoInt.c

