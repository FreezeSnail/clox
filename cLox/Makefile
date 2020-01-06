all: first
first: main.c 
	gcc -std=c99  main.c chunk.c memory.c debug.c value.c -o main vm.c &&./main
clean:
	rm -rf first
