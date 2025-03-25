<style>
.none {
    margin: 0;
    padding: 0;
}

.notes {
    border: 1px solid #4682B4;
    padding: 20px;
}
</style>

<h1>Server_3_free_threads</h1><br>

<p>The WSGI server is based on threads, <br>
which began with experiments on sockets.</p>

<div class="notes">
<h3 class="none" style="color: red;">Important!</h3>
It is supported only on Linux 2.5.44 and later
</div>


<ol><h3>the server uses four threads:</h3>
    <li><b>accepting_connections</b>, to accept connections</li>
    <li><b>reading_from_socket</b>, to read data from a client socket</li>
    <li><b>sending_to_socket</b>, to send data to a socket</li>
    <li><b>close_client_sock</b>, to close client sockets</li>
</ol>


<div class="notes">
<h3 class="none" style="color: yellow;">Note</h3>
It is recommended to use a python 3.13 or later<br>
build from the source code, with the GIL disabled,<br> 
to improve performance
</div>

<h2>Quick start</h2><br>

<h3>log in to your project folder</h3>

[//]: # (![Картинка][2])
<img src="img/1.1.png">
<img src="img/1.2.png">



<h3>activate the virtual environment</h3>

<img src="img/2.1.png">


install the library with the command:<br>
*pip install server-3-free-threads*





[1]: https://docs.python.org/3/whatsnew/3.13.html#whatsnew313-free-threaded-cpython "Free-threaded CPython"
[2]: img/1.1.png
[3]: img/1.2.png
[4]: img/2.1.png