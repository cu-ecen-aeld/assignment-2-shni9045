CC = $(CROSS_COMPILE)gcc
CFLAGS = -Wall -Werror
writer: writer.o
	 $(CC) $(CFLAGS) -o writer writer.o
writer.o: writer.c
	 $(CC) $(CFLAGS) -c writer.c

clean: 
	 rm -f  *.o  \
	        writer 
