# TCP-IP-chat-server
This Python chat application enables multiple clients to connect to a server, featuring admin privileges for kicking/banning users. Security measures include an admin password, bans recorded in 'bans.txt,' and command handling. The code leverages socket programming and threading, offering a simple yet extensible platform for communication.
Readme:

Installation:

Ensure you have Python installed.
Run the server script: python server_script.py.
Run the client script: python client_script.py.
Usage:

Choose a nickname when prompted.
If 'admin,' set a password.
Use '/kick' and '/ban' commands if admin.
Enjoy chatting with others!
Note:

Admin commands are restricted to users with 'admin' as their nickname.
Banned users' nicknames are stored in 'bans.txt'.
For security, change the default admin password.
