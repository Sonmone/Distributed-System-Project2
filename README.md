# Distributed-System-Project2
An advanced distributed system of both servers and clients supproting several basic functions.

<h2>Introduction</h2>
<p>This project implements a simple distributed system with both client and server program.</p>
Compilation
Go to the root folder of code 3.1, then use CMD order:
javac-Djava.ext.dirs=./lib -d bin @bian.txt 
Run
Go to this folder: code 3.1/bin
Run client through this CMD order:
java -Djava.ext.dirs=../lib activitystreamer.Client
Run server through this CMD order:
java -Djava.ext.dirs=../lib activitystreamer.Server
Activity Format
If the client wants send an activity message, it must input a JSON text in GUI such as
{"sport": "running"}, just as the picture shows:
