# webserver

A basic HTTP server using C++98 standard that handles GET/POST/DELETE requests
Learning to collaborate and about programming with sockets.

## Installation and usage
```
git clone git@github.com:vincentvis/viroli_webserv.git viroli_webserv
cd viroli_webserv
cmake -S . -B build
cmake --build build
```

Run the server with default configuration and browse its testing websites.
```
cd build
./webserv
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
