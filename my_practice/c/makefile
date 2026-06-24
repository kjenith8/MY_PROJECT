.PHONY : clean

SRC := $(wildcard src/*.c)
OBJ := $(SRC:.c=.o)

main : $(SRC)
	gcc $(SRC) -o build/main
	./build/main

#$(OBJ) : $(SRC)
#	gcc -c 

clean:
	rm -f build/main