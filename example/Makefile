
flags = -g -Wall -m64 -O2 -I../include

tcolors_src = $(wildcard ../src/*.c)

logger:
	gcc $(flags) $(tcolors_src) $@.c -lm -o $@.exe
	./$@.exe

clean:
	rm *.exe
