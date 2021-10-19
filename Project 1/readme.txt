- Bryan Monh : monhbryan@csu.fullerton.edu
- Andy Duong : aqduong@csu.fullerton.edu

Language: Python 2.7.18

Tuffix Instructions to execute program:
Open project directory and navigate to server folder
Run server.py first with command "python server.py {port}"  E.g. "python server.py 12000"
Navigate to client folder
Run client.py with command "python client.py {ip address} {port}" E.g. "python client.py localhost 12000"
FTP commands can now be used from the client E.g "get file.txt", "put upload.txt", "ls", "quit"


If python 3+ is installed and is the default for "python" command, "py -2 {filename}" will run under python 2. 
Run server.py first with "python -2 {port}".
For example:  "python -2 server.py 12000" would run server.py with python 2, on the 12000 port.
Run client.py second with "python -2 client.py {ip address} {port}". 
For example: "python -2 client.py 127.0.0.1 12000"  would run client.py with python 2, connecting to the 127.0.0.1 (localhost) and connect to the 12000 port.


