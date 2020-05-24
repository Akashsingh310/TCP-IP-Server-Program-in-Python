 
<h1>TCP/IP Server Program That Send And Recieves Message To Client in python</h1>

**Socket programming** is started by importing the socket library and making a simple socket.

```
import socket 
 
s = socket.socket(socket.AF_INET, socket.SOCK_STREAM)
```

Here we made a socket instance and passed it two parameters. The first parameter is **AF_INET** and the second one is **SOCK_STREAM. AF_INET** refers to the address family ipv4. The **SOCK_STREAM** means connection-oriented TCP protocol.

**How we can connect to server**

A Server is a program that provides service to other computers on the network or Internet. Similarly, a client is a program that receives services from the server. When a server wants to communicate with a client, there is a need for a socket. A socket is a point of connection between the server and the client.

**Note:** Open In Two Separate DOS Windows And First Execute server, then Execute client.


**Please run [server.py](https://github.com/Akashsingh310/TCP-IP-Server-Program-in-Python/blob/master/server.py) and [client.py](https://github.com/Akashsingh310/TCP-IP-Server-Program-in-Python/blob/master/client.py)**


**Output of server**

![server](https://github.com/Akashsingh310/TCP-IP-Server-Program-in-Python/blob/master/server.png)

**Output of client**

![client](https://github.com/Akashsingh310/TCP-IP-Server-Program-in-Python/blob/master/client.png)
