# Installing java 

## Introduction
 This is about installing **Openjdk 17** on Ubuntu 22.04

first copy the tar file [Referhere](https://www.oracle.com/java/technologies/downloads/#java17)
Now follow the command

```bash
wget <"java version tar file">
 
tar xvzf jdk-17_linux-x64_bin.tar.gz 
```
![image](images/1.png)

here we got the tar file and untar that file by excecuting the above commands

now we need to move untar file to /opt folder
```bash
 sudo mv jdk-17.0.12 /opt
```
![image](images/2.png)

now set the path by the following command

```bash
 sudo vi /etc/environment
```
add the path " :/opt/jdk-17.0.12/bin "
![image](images/3.png)

now exit and relogin 
Now check for java version to check if the java installed correctly or not
```bash
java -version
```
![image](images/4.png)

we can see java installed sucessfully

