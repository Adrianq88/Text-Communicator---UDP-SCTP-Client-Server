# Text-Communicator---UDP-SCTP-Client-Server

Text Communicator - C Client-Server Application

# Project Description:

This project entails the development of a text communicator using the C programming language. It implements client-server architecture, enabling users to exchange text messages over a network connection.

Features:

Client-Server Communication: Utilizes C sockets for establishing communication between clients and servers.

Message Exchange: Allows clients to send and receive text messages through the server.

System Requirements:

The program requires a C compiler to build and run.

How to Use:

Setup: Ensure a C compiler is installed on your system.

Compiling the Code:

For the server:
bash
Copy code
$ gcc -o server server.c
For the client:
bash
Copy code
$ gcc -o client client.c
Starting the Server: Run the server-side application. This will establish a connection endpoint for clients.

Connecting Clients: Clients need to run the client-side application and specify the server's IP address and port number.

Messaging: Once connected, clients can exchange messages with each other via the server.

How to Run:

Server:

bash
Copy code
$ ./server
Server listening on port 8000...
Client:

bash
Copy code
$ ./client
Enter server IP address: 192.168.1.100
Enter server port: 8000
Connected to server. Start messaging!
License:

This project is released under the GNU General Public License v3.0. Refer to the LICENSE.md file for more information.

Author:

Author: [Your Name]
Contact: [Your Email]

Thank you for using the Text Communicator!




