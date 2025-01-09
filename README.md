# TCP-UDP-String-Manipulation-Calculator
A TCP and UDP-based client-server program that performs string manipulation (reverse and capitalize) and mathematical calculations (online calculator).
TCP and UDP - String Manipulation & Online Calculator
Overview
This project implements two types of client-server communication over TCP and UDP. The server receives a string or mathematical expression from the client, processes it, and sends back the result. The client displays the result and terminates.

Objective
The goal of the assignment is to:

Implement TCP and UDP server-client communication.
Perform string manipulations on the received data.
Implement an online calculator to evaluate mathematical expressions sent by the client.
Features
TCP Client-Server Communication
Client sends a string to the server.
Server performs two operations: reverses the string and reverses its capitalization.
Server sends the modified string back to the client, which displays it.
UDP Client-Server Communication
Client sends a mathematical expression to the server (e.g., a+b*c/d with variable values).
Server evaluates the expression based on the values and returns the result to the client.
Client displays the calculated result.
Requirements
C compiler (e.g., GCC).
Text editor or IDE for coding.
Basic understanding of TCP/UDP communication and string operations in C.
