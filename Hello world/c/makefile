
CFLAGS = -Wall -c $(DEBUG)
CC = gcc
LFLAGS = -Wall $(DEBUG)
OBJS = main.o
DEBUG = -g

main: $(OBJS)
	$(CC) $(LFLAGS) $(OBJS) -o main

main.o:
	$(CC) $(CFLAGS) main.c

clean:
	\rm *.o main
