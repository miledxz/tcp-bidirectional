# tcp-bidirectional
Demonstration of TCP communication between client and server

# Client Server TCP network

- This project consists for a TCP protocol based bidirectional multi-client server communication.
- Bidirectional multi-client server communication.
- Either can send full length texts with low latency.

## Instructions
- Enter `./serverSide.out 3000` , where 3000 is the PORT number
- Enter `./clientSide.out [localhost](http://localhost) 3000` where 3000 is the same PORT number as provided for server.
- Client has to send the first message, then server and so on. For quitting the chat, either the server or client can enter `exit` and the program will terminate.
- For testing multiple client, open up a new window and enter `./clientSide.out [localhost](http://localhost) 3000`. When you want to quit, enter `exit` and server can go back to the previous client.

