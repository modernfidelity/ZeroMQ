ZeroMQ
======

Some basic ZeroMQ examples

Install Libzmq (3.2.3)
---------------

After installing the ZeroMQ library 

cd into zeromq-3.2.3 src folder 

./configure

sudo make install 

On the mac; 
this then installs the zmq lib by default into /usr/local/lib/lizmq*



Hello World (client + server)
------------------------------

Compile the server & client files : 

gcc  hw_client.c -o hw_client  -L/usr/local/lib -lzmq

gcc  hw_server.c -o hw_server  -L/usr/local/lib -lzmq
  
  
