.PHONY : clean

SRC := $(wildcard src/*.c)
OBJ := $(SRC:src/%.c=build/%.o)



main : $(OBJ)
	gcc $(OBJ) -o build/main
	./build/main

build/%.o: src/%.c
	gcc -c $< -o $@ 

clean:
	rm -f build/main build/*.o