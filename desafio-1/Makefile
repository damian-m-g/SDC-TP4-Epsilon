CC=gcc
CFLAGS=-Wall

all: hello_humans

hello_humans: hello_humans.o
	$(CC) $(CFLAGS) -o hello_humans hello_humans.o

hello_humans.o: hello_humans.c
	$(CC) $(CFLAGS) -c hello_humans.c

install:
	install -Dm755 hello_humans /usr/local/bin/hello_humans

clean:
	rm -f hello_humans hello_humans.o