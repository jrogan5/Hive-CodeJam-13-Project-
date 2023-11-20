To run on two computers, 

1. open send.py on "client" computer and "listening.py" on "server" computer. 

2. make sure paths for files being sent and directory for files being recieved are correct:

Make sure:
- SERVER_DIR the directory from which the files are sent and recieved on the server side (hash represents a unique identifier string that is important in the context of the project.)
- JAVA_DIR_PATH the path from which the files are sent and recieved on the client side. 

  3 cases: 
  - client request manifest.txt from server
  - client request hash.zip from server
  - client send hash.zp to server

--> py listening.py on the "server" computer

--> py send.py on the "client" computer
