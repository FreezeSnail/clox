all: first
first: main.c 
	gcc main.c chunk.c memory.c debug.c value.c compiler.c scanner.c object.c table.c -o main vm.c &&./main
clean:
	rm -rf first
