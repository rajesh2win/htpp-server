# htpp-server
testing http server creation
client first makes a TCP connection before sending any http requests.

run telnet command:

>telnet localhost 8888
Trying 127.0.0.1 …
Connected to localhost.
GET /hello HTTP/1.1

>from the browser localhost:8888
Actually web server created a listening socket and starts accepting  new connection from browser or any other clients.
Both client and server use sockets to communicate each other.
Client initiates a TCP connection , after sucessful connection @layer4 (TCP) then starts HTTP request and that eventually leads to some response
