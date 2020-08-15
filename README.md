# ATM-Banking-System

I built a banking system with Java Eclipse

## 1.	Introduction – (1) Reference _ATM Bank System.
This project was created with reference to the following requirements.


### Project requirements: 
1. the program is divided into two parts: Client side and Server side
2. The server side is responsible for managing all bank cards, administrators can increase and delete bank cards.
(1) Each bank card is uniquely identified by card number
(2) The new bank card password is "1234", the amount of the card is 0 yuan;
(3) Only the bank card that the administrator has added can login from the client side;
(4) The bank card that the administrator has deleted can’t login from the client side;
3. The client is responsible for ATM common operation.
(1) After the client enters the correct bank card number and password and the system checks correctly, the client can do other operations;
(2) After login, users can query the balance, withdrawals, deposits, transfer and modify password operation;
(3) When the password is modified, the user needs to enter new passwords two times, which make sure the password is changed correctly
   (4) After each client’s operation such as withdrawals and deposit operations, the result of operation should display, such as "successful operation" or "insufficient balance, failure of operation", etc..
4. Imitate the actual interface of ATM as much as possible.
5. For failure operations, the exception capture mechanism is used for error.
6. Server supports multiple clients.
Technology: GUI, Thread, Networking, Exception, Collection, I/O
Submit: java source code, java bytecode, and word document that describes the design and screen copy of your GUI running application

