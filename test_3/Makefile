.PHONY:hello
hello:hello.c
	gcc -o hello hello.c
	
#hello:hello.o
#	gcc hello.o -o hello

#hello.o:hello.s 
#	gcc -c hello.s -o hello.o 
#hello.s:hello.i 
#	gcc -S hello.i -o hello.s 
#ello.i:hello.c 
#	gcc -E hello.c -o hello.i
.PHONY:clean
clean:
	rm -f hello.i hello.s hello.o hello
