# Python_DevOps_Socket-Library

### 1. **Socket**:

A socket is an endpoint for communication between two machines over a network. It can be used to establish connections, send and receive data, and close connections.

### 2. **Socket Types**:

Python's `socket` library supports various socket types, but the two most common are:

- **Stream Sockets (`socket.SOCK_STREAM`)**: These provide a reliable, connection-oriented communication channel. They use protocols like TCP (Transmission Control Protocol) and ensure that data is delivered in the order it was sent.

- **Datagram Sockets (`socket.SOCK_DGRAM`)**: These are connectionless and provide an unreliable, message-oriented communication channel. They use protocols like UDP (User Datagram Protocol) and do not guarantee delivery order or delivery at all.

### 3. **Address Families**:

The `socket` library supports different address families. The most commonly used are:

- **IPv4 (`socket.AF_INET`)**: This is used for IPv4 addresses and provides a 32-bit address space.

- **IPv6 (`socket.AF_INET6`)**: This is used for IPv6 addresses which have a much larger address space.

### 4. **Creating a Socket**:

```python
import socket

# Create a socket object
server_socket = socket.socket(socket.AF_INET, socket.SOCK_STREAM)
```
