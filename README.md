# Python-Socket
This repository provides a simple implementation of a Greetings server and an EchoServer using Python's socket programming library. 

## Client-Server
#### Greetings server (Folder - Client-Server)
The Greetings server is a simple server that listens for incoming client connections and sends a predefined greeting message to each client that connects. It showcases how to set up a server socket, accept incoming connections, and send data to clients.

## Echo-Server
#### Basic Echo-Server (Folder - Echo-Server-v1)
The EchoServer is a more advanced server that listens for client connections and echoes back any message received from the client. It showcases bidirectional communication between the server and the client, where the server receives data from the client and sends it back as a response. This server demonstrates how to handle incoming client connections, receive data, and send data back to the client.
#### Buffered EchoServer (Folder - Echo-Server-v2)
The Buffered EchoServer is an enhanced version of the EchoServer application that allows for the handling of arbitrary sized messages. It addresses the limitation of the basic EchoServer, which can only handle messages of limited size due to the inherent buffer constraints.
#### EchoServer with a Sustained Connection (Folder - Echo-Server-v3)
The EchoServer with a Sustained Connection is an enhanced version of the EchoServer application that allows for continuous communication between the server and client, maintaining the connection until a specific message is received. Unlike the previous version that served a single request and then disconnected, this server keeps the connection alive to facilitate ongoing interactions.
