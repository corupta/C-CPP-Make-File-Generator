INCDIR =	-I"." -I"./headers1" -I"./src1"

tc1.exe:	main1.o multTwoInt.o addTwoInt.o
		gcc main1.o multTwoInt.o addTwoInt.o -o tc1.exe
		@echo "Makefile finished successfully. Created program: tc1.exe"

main1.o:	./headers1/addTwoInt.h ./headers1/multTwoInt.h
		gcc -c $(INCDIR) ./main1.c

multTwoInt.o:	./headers1/multTwoInt.h
		gcc -c $(INCDIR) ./src1/multTwoInt.c

addTwoInt.o:	./headers1/addTwoInt.h
		gcc -c $(INCDIR) ./src1/addTwoInt.c

