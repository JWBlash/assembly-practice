all: random.o
	gcc -o random random.o -nostdlib -static

random.o:
	as random.asm -o random.o

clean:
	rm -rf random random.o
