#DiffieHelman Keyexchange System 

PROJECT TITLE
_ _ _ _ _ _ _ _ 
IMPLEMENTATION OF DIFFIE HELMAN KEY EXCHANGE APPLICABLE TO AES ENCRYPTION IN ECB MODE USING
UDP SOCKET


PREREQUISITES
_ _ _ _ _ _ _ _
1. A Python Integrated Development Environment (IDE)
2. A Python Interpreter


INSTALLATION REQUIREMENT
_ _ _ _ _ _ _ _ _ _ _ _ 

1. Install an interpreter (preferably anaconda
2. Install an IDE (preferably Pycharm 2017.3.4)
3. Install pycryptodome package from the IDE
4. Ensure the selected UDP port is running, you can confirm this on windows
and linux with the following commands

Windows:  netstat -an | findstr ":port number"
Linux:	  netstat -plnt | grep ':port number'



FEATURES
_ _  _  _  _
1. A UDP socket with a dynamic port number (greater than 1023)
2. A buffer size of 1024 bytes
3. Two independent python files for the client and server
4. A function for generating public numbers of both client and server
5. A function for secret key generation
6. A function for random number generation
7. A class with attributes of encryption and decryption for (AES 128, 192, 256)
8. A conditional loop that determines successful or failed authentication
9. A timer for computing cipher execution duration
10. An excel document for time execution comparison of the 3 cipher key length
using varying message bytes size


DEPLOYMENT
_ _ _ _ _ _ 

1. Open both project files with installed IDE
2. Run the server side of the project first using the IDE
3. Run the client side of the project
4. Socket is established on the UDP port number 34288 
5. Communication between both parties begins


AUTHORS
_ _ _ _ _ 

Bello Adesoji Tolulope 

SUPPORT
_ _ _ _ _ _ _ _

Should in case you are having issues with running the project, send an email to
bello@mtu.edu


ACKNOWLEDGMENT
_ _ _ _ _ _ _ _ 

I hereby use this medium to acknowledge the efforts of Dr Kit Cishchke who stood as a pillar of
support during project development and willingly assisted in areas i experienced challenges.


