CC = gcc
CFLAGS = -Wall -Wextra
TARGET = hello

all: $(TARGET)

$(TARGET): hello_world.c
	$(CC) $(CFLAGS) -o $(TARGET) hello_world.c

clean:
	rm -f $(TARGET)
