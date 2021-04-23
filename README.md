# Secure-Chatroom-SSL

The goal of this assignment is to create a secure chat room by implementing a secure connection using SSL. I modified the provided code to implement a simple chat room with user interface from the following link https://cs.lmu.edu/~ray/notes/javanetexamples. Then I changed the mode of connection between the client and server using Java SSLSocket instead of Java socket. The process to use SSLsocket is slightly different from using simple socket, because first we need to generate a private key, public key, trust store and key store. Then implement a handshake process to verify the keys between client and server. Finally, after the handshake process is done, the server and client will be able to communicate securely.