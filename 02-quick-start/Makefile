.SUFFIXES: .c .o

TARGET=quick
OBJS=$(TARGET).o
LIBS=-lGL -lglfw

$(TARGET): $(OBJS)
	$(CC) -o $(TARGET) $(OBJS) $(LIBS)

clean:
	rm -f $(OBJS) $(TARGET)

.c.o:
	$(CC) -c $< -o $@

