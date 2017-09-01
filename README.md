#Apache Nifi
============

For more information on [Apache Nifi](https://nifi.apache.org/index.html)

### Getting the Image
Use docker pull or Dockerfile to get Nifi image.

### Starting the container
* Start container using "-i" and "-t" option
  * docker -it -P dataramar/nifi:<tag> /bin/bash

### Start Nifi in the container
* Execute ```nifi.sh start``` to start the Nifi process

### Example to run a container
    docker run -it -P dataramar/nifi:0.2.1 /bin/bash
    
### Accessing Nifi WebUI
Nifi uses port 8080 by default. The container exposes 8080 so with the "-P" option you should be able to use the mapped port.
* ***URL syntax:*** http://host:port/nifi






# r-test
First repo to test and practise github and git

### Test Lists
Test 
* One
* Two
* Three

- One
- Two
- Three

