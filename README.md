**zsend** - read from standard input and write to specified zmq endpoint

**zrecv** - read from specified zmq source and write to standard output


usage
=====

    [STDIN] | zsend [req|push|pub] tcp://your-server-url:port

    zrecv [rep|pull|sub] tcp://your-server-url:port [subscription topic] | [STDOUT]
