CFLAG=-g 
INC=-I./ 
LIB=-L./ -lpthread -lrt

SRC=a.c
BIN=a

all: $(BIN)

a: a.c
	gcc $(CFLAG) -o a a.c $(INC) $(LIB)

calc: calc.c
	gcc $(CFLAG) -o calc calc.c $(INC) $(LIB)


calc2: calc2.c calOp.c
	gcc $(CFLAG) -o calc2 calc2.c calOp.c $(INC) $(LIB)

clean:
	rm -f a calc calc2 core.* *.o
