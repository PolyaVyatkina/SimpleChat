# Simple chat
Client application: `сlient1.py`

Server: `server1.py`

### Protocol Description:
Message:
1. The header contains information about the length of the message in bytes
2. The message contains the username, date of submission and text. The parts of the message are separated by \ 0.
    
Exit the client application with Ctrl + C. Output of incoming messages in the format [<user name>] <date> <time> :: <text>
