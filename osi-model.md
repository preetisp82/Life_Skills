# OSI Model

## Introduction

The OSI (Open Systems Interconnection) model is a framework that explains how data is transmitted between devices over a network. It divides communication into seven layers, where each layer performs a specific task. This layered approach makes it easier to understand, design, and troubleshoot networks.

## Seven Layers of the OSI Model

### Layer 7 - Application Layer

* Provides services directly to user applications.
* Enables communication between software and the network.
* Examples: HTTP, FTP, SMTP, DNS.

### Layer 6 - Presentation Layer

* Converts data into a suitable format.
* Performs encryption and decryption.
* Handles data compression.

### Layer 5 - Session Layer

* Establishes and manages communication sessions.
* Synchronizes data exchange.
* Terminates sessions after communication is complete.

### Layer 4 - Transport Layer

* Ensures reliable data delivery.
* Breaks data into segments.
* Performs error detection and flow control.
* Examples: TCP and UDP.

### Layer 3 - Network Layer

* Determines the best path for data transmission.
* Uses logical addressing.
* Handles routing between networks.
* Example: IP protocol.

### Layer 2 - Data Link Layer

* Provides node-to-node communication.
* Detects and corrects errors.
* Uses MAC addresses.
* Devices: Switches and bridges.

### Layer 1 - Physical Layer

* Responsible for transmitting raw bits.
* Defines cables, connectors, and signals.
* Devices: Hubs and repeaters.

## Data Flow in the OSI Model

When data is sent from one device to another:

1. Data starts at the Application Layer.
2. It passes through all seven layers.
3. Each layer adds its own information.
4. At the receiving end, data moves upward through the layers.
5. The original message is finally delivered to the application.

## Advantages of the OSI Model

* Simplifies network communication.
* Makes troubleshooting easier.
* Promotes standardization.
* Allows interoperability between different systems.
* Helps in understanding networking concepts.

## Conclusion

The OSI model provides a structured approach to network communication. Although modern networks mainly use the TCP/IP model, the OSI model remains an important reference for understanding how data travels across a network and for diagnosing network-related problems.

## References

* https://www.youtube.com/watch?v=vv4y_uOneC0
* https://www.geeksforgeeks.org/layers-of-osi-model/
