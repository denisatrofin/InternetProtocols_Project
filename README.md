## Project Overview  


This project implements a client-server communication system using sockets in C. The client retrieves data from a website and transmits it to a connected client. 
The project demonstrates socket programming, data transmission, and handling client-server interactions efficiently.

## Methodology

**Client-Side:**
- Creates a socket using AF_INET6 for IPv6 support.
- Resolves the hostname and establishes a connection to the remote site.
- Sends an HTTP GET request.
- Receives and processes data from the website.
- Saves the data into an HTML file.
- Sends the received data to the connected client.

**Server-Side:**
- Creates a socket and binds it to a specific port (22228).
- Listens for incoming connections.
- Accepts and handles multiple clients.
- Receives commands and responds accordingly.
- Calls ClientMessage() function for a specific command (08#)


## Technologies Used:
 - C (Sockets, Networking)
 - Linux Networking APIs
 - IPv6 support
