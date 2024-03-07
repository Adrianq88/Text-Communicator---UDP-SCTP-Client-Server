# Text-Communicator UDP/SCTP Client-Server

## Project Description:

This project entails the development of a text communicator using the C programming language. It implements client-server architecture, enabling users to exchange text messages over a network connection.


## Features:

Client-Server Communication: Utilizes C sockets for establishing communication between clients and servers.
Message Exchange: Allows clients to send and receive text messages through the server.


## How to use

### Creating Directories and Source Files:
```
mkdir komunikator_projekt
cd komunikator_projekt

mkdir serwer
cd serwer
touch serwer.c
cd ../..

mkdir klient
cd klient
touch klient.c
cd ../..
```

### Creating Server and Client Code:
```
nano ~/komunikator_projekt/serwer/serwer.c

nano ~/komunikator_projekt/klient/klient.c
```

### Copying Attached Programs:


### Compilation:

Server:
```
~/komunikator_projekt$ gcc ~/komunikator_projekt/serwer/serwer.c -o ~/komunikator_projekt/serwer/serwer -lsctp
```

Client:
```
~/komunikator_projekt$ gcc ~/komunikator_projekt/klient/klient.c -o ~/komunikator_projekt/klient/klient -lsctp
```

### Operation:

LOGIN CREDENTIALS FOR THE COMMUNICATOR
```
a) Username: user1
Password: pass1

b) Username: user2
Password: pass2
```

## License:

This project is released under the GNU General Public License v3.0. Refer to the LICENSE.md file for more information.


## Author:

Created by Adrianq88

Thank you for using the Text Communicator!




