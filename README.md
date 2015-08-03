#SimplePythonUnixSocket

## Description

Simple example of a server program and its corresponding client using a Unix Socket.

## Try it

To test it, open two ternimal windows:
in the 1st one, run the command "python3 server.py" which create a server binded to a unix socket at /tmp/python_unix_sockets_example
in the 2nd one, run the command "python3 client.py" which is connected to the unix socket at /tmp/python_unix_sockets_example

Once this done, in the client terminal window, start writing text. Press <ENTER> to send the text to the server which will write in on the standard output on his terminal window.

To close the server, send "DONE" to the server fron your client window.
