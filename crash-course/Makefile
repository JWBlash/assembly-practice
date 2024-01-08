all: asem.o
	gcc -o asem asem.o -nostdlib -static

asem.o:
	as asem.asm -o asem.o

clean:
	rm -rf asem asem.o
