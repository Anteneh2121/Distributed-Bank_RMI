#  Distributed-Bank_RMI

 Banking system Remote Method Invocation

*A Distributed Banking System including a bank (server) and ATM (client) using Java RMI.

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

Start the server ./start-server.sh

Start the client ./start-client.sh

```
## Usage

There are two ways to run the application the application


```Ubuntu 20.04

```

### Run as Flask application 

Go to the same directory as the main application and run the following


```bash
export FLASK_APP=app.py
flask run
```
