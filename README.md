# spl-net
This was the third assignemnt in the course SPL201 - java server for Book Club

Implementing a thread safe Server (Java) - TPC and Reactor patterns, and a multiple thread Client (Cpp). Server-Client Communication according to 'STOMP' protocol.

For running, do the following steps:

1) terminal command: ~/bin/mvn compile
2) terminal command: mvn exec:java -Dexec.mainClass="bgu.spl.net.impl.stomp.StompServer" -Dexec.args="<port> <serverType>"
3) wait for clients to work with the server!
