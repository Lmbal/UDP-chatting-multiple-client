# UDP-chatting-multiple-client
gcc server.c -o server
./server 32505
 gcc -o client.c -o client
./client 127.0.0.1 32505
openssl req -x509 -nodes -days 365 -newkey rsa:1024 -keyout mycert.pem -out mycert.pem 
gcc server3.c -o server3 -L/usr/lib -lssl -lcrypto
gcc client3.c -o client3 -L/usr/lib -lssl -lcrypto
