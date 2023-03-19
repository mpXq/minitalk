# minitalk
Communicate with signals
```
With this project, we learn the communication between programs through different signals.
The goal of this one is to create a server and a client,
in order to be able to send messages from the client to the server thanks to the signals "SIGUSR1" and "SIGUSR2".
For that, we send our string of characters in binary, SIGUSR1 corresponding to 0 and SIGUSR2 corresponding to 1.
This project teaches us also the use of bitshifting to succeed in sending and receiving messages in binary.
