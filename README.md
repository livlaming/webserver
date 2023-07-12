# webserver

A basic HTTP/1.1 web server using C++98 standard that handles GET/POST/DELETE requests.
Learning to collaborate and about programming with sockets.

The webserver uses the same non-blocking, event-driven architecture that nginx does. This allows the server to handle a high amount of requests with speed.
poll is used to handle the multiplexing.

## Installation and usage
```
cmake -S . -B build
cmake --build build
```

Run the server with default configuration and browse its testing websites.
```
cd build
./webserv 
```

Run server with config file
```
./webserv [configfile]
```

Open your favorite browser and enter in its address bar:
```
http://localhost:8248/
OR
http://localhost:8248/servernames/koda.com/index.html
```


## CPP resources

https://www.learncpp.com/

https://cplusplus.com/reference/

https://isocpp.org/faq

https://web.stanford.edu/class/archive/cs/cs106b/cs106b.1084/cs106l/handouts/170_Copy_Constructor_Assignment_Operator.pdf
