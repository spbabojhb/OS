TARGET = project
SRC = project.c
OBJ = project.o
CC = gcc
LDFLAGS = -pthread -lpthread
CFLAGS = -D_REENTRANT

all: $(OBJ)
	$(CC) -o $(TARGET) $(LDFLAGS) $(OBJ)

.c.o:
	$(CC) -c $(CFLAGS) $<

clean:
	rm -rf *.o $(TARGET)
