all: logfile memory simple vulnerable

logfile: memory
	touch logfile

memory: memory.c 
	gcc -g -o memory memory.c 

simple: simple.c 
	gcc -g simple.c -o simple

vulnerable: vulnerable.c 
	gcc -g vulnerable.c -o vulnerable

clean: 
	rm -f *.o memory simple vulnerable