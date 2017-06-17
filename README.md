# ICS

## Intranet/Internet Chatting System (Service)

To Run the Server: Give the port number to be used as argument  
To Run the Client: Give the host address and port number of the server as argument  

### Intranet
Step 1: Compile ChatServer.java and ChatClient.java using javac command  
Step 2: Run the server on server computer using the format: 
```
java ChatServer \<port-number\>  
```
Step 3: Run the client using command: 
```
java ChatClient \<host-address\> \<port-number\> 
```
  
>PS: To Run both client and server on same machine, host would be the localhost (generally 127.0.0.1) and use port number of your choice
