# 411-W14

This week's project was to be able to comunicate with other machines. 
I did an example using socket programming, with the type client-server application, where one side acts as the server and waits for connections from clients. 
A listening socket does just what it sounds like. It listens for connections from clients. When a client connects, the server calls accept() to accept, or complete, the connection.
The client calls connect() to establish a connection to the server and initiate the three-way handshake. The handshake step is important since it ensures that each side of the connection is reachable in the network, in other words that the client can reach the server and vice-versa. It may be that only one host, client or server, can reach the other.
