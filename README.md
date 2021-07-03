# Client-Server-Chat-Application
A client-server chat application consists of a Chat Client and a Chat Server and
there exists a two way communication between them. Here, Message Processor
is used to interpret message from the user, Message Interpreter is used to
extract and pass the received message. Message Maker is used to construct
back the message and Client Manager is used to maintain the clients list which
the and sender receiver at both sides use to interact with each other. In
general, the server process will start on some computer system; in fact, the
server should be executed before the client. Server usually initializes itself, and
then goes to wait state or sleep state where it will wait for a client request. After
that, a client process can start on either the same machine or on some other
machine. Whenever the client wants some service from the server, it will send a
request to the server and the server will accept the request and process it. After
the server has finished providing its service to the client, the server will again
go back to sleep, that is, waiting for the next client request to arrive. This
process is repeated as long as the server processes is running. Whenever such
request comes, the server can immediately serve the client and again go back
to the waiting state for the next request to arrive.
