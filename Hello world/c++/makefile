
CFLAGS = -Wall -c $(DEBUG)
CC = g++
LFLAGS = -Wall $(DEBUG)
OBJS = main.o
DEBUG = -g

main: $(OBJS)
	$(CC) $(LFLAGS) $(OBJS) -o main

main.o:
	$(CC) $(CFLAGS) main.cpp

clean:
	\rm *.o main
