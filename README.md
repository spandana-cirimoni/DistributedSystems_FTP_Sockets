# Java FTP Program with Encryption and Authentication

-This Java program implements a simplified version of an FTP (File Transfer Protocol) system with user authentication and file encryption.
-The client and server communicate over sockets, and files are transferred securely using a Caesar Cipher encryption algorithm.

## Overview

- The program consists of two main components: the client and the server. 
- The client must register with the server using a username and password for authentication. Once authenticated, the client can request files from the server. 
- If the requested file exists, it is sent to the client after encryption. The program uses a Caesar Cipher algorithm for encryption.

## How to RUN

- Make sure you have installed java19 before running the code
- Run the program using "make compile" command.
- once the server.java and client.java are compiled, use the command "make server" command.
- Later use the "make client" command to connect with the server.(i have mentioned "in-csci-rrpc01.cs.iupui.edu" machine in line 21 of client.java)
- type in the username and password. (username: spandana and password: cirimoni are already registered user credentials)
- type the file name:(sample1.txt is a sample text file to test)

## Code Structure

- Client.java: Contains the client-side code for connecting to the server, user authentication, and file transfer.
- Server.java: Implements the server-side functionality, including user authentication, file existence checks, and file transfer.

## Observations and Result
- There are mentioned in the Assignment2.docx
