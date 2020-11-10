# Unix-Domain-Sockets
Implementation in C language

Steps to run:

gcc -c server.c

gcc -o server server.o

gcc -c client.c

gcc -o client client.o

./server 

./client 1 2 3 4

Result = 10

./client 875 90 45

Result = 1010

./client DOWN

Result = 0 //exit and unlink server at this cmd
