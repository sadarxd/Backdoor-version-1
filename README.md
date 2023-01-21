# Backdoor-version-2
Make a file with extenction .bat
====================================================================
The code you provided creates a server that listens for incoming connections on a specified port (default 4444). 
When a client connects to the server, it creates a new socket for the client and sets up input and output streams for communication.

It then uses the System.getProperty() method to get information about the host machine, such as the current user's name, home directory, and the operating system version.

It enters into a loop that continuously listens for commands from the client, and based on the command it receives, it performs the corresponding action.

The commands that are implemented are:

"QUIT": exit the server
"CMDLIST": return a list of available commands
"GETHOME": return the user's home path
"GETDIR": return the current directory path
"GETNAME": return the user name
"OSARCH": return the Operating System architecture
"OSNAME": return the Operating System name
"OSVERS": return the Operating System version
any other command: execute it as a command on the host machine and return the output.
It is important to note that this program creates a backdoor that could be potentially used maliciously to gain unauthorized access to a machine and should not be run without the owner's consent. 
Additionally, the program does not have any security features and does not encrypt the communication between the client and the server, which could be intercepted by a third party.

It is crucial to understand that this type of code should not be used in a production environment and is only for educational purposes.
