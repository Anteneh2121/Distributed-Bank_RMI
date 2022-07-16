#  Distributed-Bank_RMI

 Banking system Remote Method Invocation

* A Distributed Banking System including a bank (server) and ATM (client) using Java RMI.



   **Home page**
<p align="center">
  <img src="https://github.com/Anteneh2121/Distributed-Bank_RMI/blob/main/bankServer.PNG">
</p>

 ##  Installation

```install on ubuntu 20.04 machine using the ff command

git clone https://github.com/Anteneh2121/Distributed-Bank_RMI
```

Use the package manager apt-get to install the dependencies.

## Usage

Go in the same directory  and run the following

```Ubuntu 20.04

## Usage

$ cd Distributed-Bank_RMI
adduser@ET-27608:~/Distributed-Bank_RMI$

adduser@ET-27608:~/Distributed-Bank_RMI$ sudo apt-get install openjdk-8-jdk

adduser@ET-27608:~/Distributed-Bank_RMI$ sudo apt-get update

adduser@ET-27608:~/Distributed-Bank_RMI$ cd scripts

adduser@ET-27608:~/Distributed-Bank_RMI/scripts$

```complile all script file

Run ./compile.sh

Start the registry ./start-registry.sh

* A Java RMI registry is a simplified name service that allows clients to get a reference (a stub) to a remote object. In general, a registry is used (if at all) only to locate the first remote object a client needs to use 

Start the server ./start-server.sh

Start the client ./start-client.sh





