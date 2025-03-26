
# Server_3_free_threads
the project appeared as a result of experiments on sockets. <br>
This is a WSGI server based on threads

<br>

***
### *<p style="color: red;"><p style="color: red;">Important!</p></p>*
*It is supported only on Linux 2.5.44 and later*
***

<br>

## the server uses four threads:
1.<b>accepting_connections</b>, to accept connections<br>
2.<b>reading_from_socket</b>, to read data from a client socket<br>
3.<b>sending_to_socket</b>, to send data to a socket<br>
4.<b>close_client_sock</b>, to close client sockets<br>

<br>

***
### *<p style="color: yellow;">Note</p>*
*It is recommended to use a python 3.13 or later<br>
build from the source code, with the GIL disabled,<br> 
to improve performance*
***

<br>

## Quick start

### log in to your project folder
<img src="img/1.1.png">
<img src="img/1.2.png">

<h3>activate the virtual environment</h3>

<img src="img/2.1.png">

install the library with the command:<br>
pip install server-3-free-threads



