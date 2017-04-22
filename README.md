ADC 2017
Project 1
======
Group Member
------
(name and student id)

General Purpose
------
Implementing a single-thread client-server application,a file server, 
connecting through a TCP. Client is able to send a single or multiple
message to the server. The proposed file server supports the following
operations: read, mkdir, rmdir, opendir, upload and download.

Usage
------
- To compile:
```
g++ -o server server.cpp
```
```
g++ -o client client.cpp
```
- To run the server:
```
./server
Server should run firstly.
```
- To run the client:
```
./client
```
- To make operations:
Follow the instruction, enter the corresponding number of the operation,
then, enter the desired file name.

This file server can support 6 operation:
1. read 
2. mkdir
3. rmdir
4. opendir
5. upload
6. download

Detail:
1. read 
Please enter the function number:
1
[2017/03/22 16:38:05]
Enter the target file name
1.txt
[2017/03/22 16:38:25]
>>Successful read file
This is for the test of read.
The homework 1: file server
2. mkdir
3. rmdir
4. opendir
5. upload
6. download
