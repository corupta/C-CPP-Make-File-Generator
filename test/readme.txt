
Test-cases contain a few header and source files with simple codes.


tc1 and tc2 are straightforward.
In tc3, one header file included in main3.c but not found.
	(your program should give error message containing related file name.)
In tc4, one header file not included in main4.c.
	(your program should give warning message containing related file name.)
In tc5, your program should handle multi-level directories

**All directory and file names will be UNIQUE.
**For any problems or (unintentional) mistakes in test-cases,
	share them on piazza.
	Can Hoca or I will be answering your questions.

Below, directory trees(structures) for test-cases are given.
////////////////////////////////////////////////////////////////////

tc1
├── headers1
│   ├── addTwoInt.h
│   └── multTwoInt.h
├── main1.c
└── src1
    ├── addTwoInt.c
    └── multTwoInt.c

////////////////////////////////////////////////////////////////////

tc2
├── addTwoInt.c
├── addTwoInt.h
├── main2.c
├── multTwoInt.c
└── multTwoInt.h

////////////////////////////////////////////////////////////////////

tc3 (in tc3, one header file included in main3.c and is not found)
├── headers3
│   └── addTwoInt.h
├── main3.c
└── src3
    ├── addTwoInt.c
    └── multTwoInt.c

////////////////////////////////////////////////////////////////////

tc4 (in tc3, unusedFunc.h was not included in any file)
├── headers4
│   ├── addTwoInt.h
│   ├── multTwoInt.h
│   └── unusedFunc.h
├── main4.c
└── src4
    ├── addTwoInt.c
    └── multTwoInt.c

////////////////////////////////////////////////////////////////////

tc5
├── headers5
│   ├── addTwoInt.h
│   └── headers5_2
│       └── multTwoInt.h
├── main5.c
└── src5
    ├── addTwoInt.c
    └── multTwoInt.c

////////////////////////////////////////////////////////////////////
