
# Chat Application

A desktop application built using JAVA's SWING and AWT GUI interfaces and chat feature implemented using socket programming

![Example](https://github.com/alevvio/ChatApp/assets/106387661/49f99b0f-239a-479e-9987-c588f127ac35)



## Features

- uses Spring as the application framework
- Real-time communication between a client and a server using java.net
- Program can be exited by using the back button


## Sockets

Having an active connection opened between the client and the server so client can send and receive data. This allows real-time communication using TCP sockets. This is made possible by using java.net

The client starts by connecting to the server through a socket(maybe also assigned to a specific namespace). Once connections is successful, client and server can emit and listen to events.
