# Task 1 - OSI

he OSI (Open Systems Interconnection) model is a conceptual framework used to understand and describe the functions of a networking or telecommunication system. It was developed by the International Organization for Standardization (ISO) to standardize the protocols used in various layers of network communication. The model is divided into seven layers, each responsible for specific functions in the process of data transmission between devices across a network.

| Layer No | Layer Name          | Responsibility                                                     | Information Form(Data Unit) | Device or Protocol |
|----------|---------------------|--------------------------------------------------------------------|------------------------------|--------------------|
| 7        | Application Layer   | Helps in identifying the client and synchronizing communication.  | Message                      | SMTP               |
| 6        | Presentation Layer  | Data from the application layer is extracted and manipulated in the required format for transmission. | Message | JPEG, MPEG, GIF |
| 5        | Session Layer       | Establishes Connection, Maintenance, Ensures Authentication and Ensures security. | Message | Gateway |
| 4        | Transport Layer     | Take Service from Network Layer and provide it to the Application Layer. | Segment | Firewall |
| 3        | Network Layer       | Transmission of data from one host to another, located in different networks. | Packet | Router |
| 2        | Data Link Layer     | Node to Node Delivery of Message.                                  | Frame | Switch, Bridge |
| 1        | Physical Layer      | Establishing Physical Connections between Devices.                 | Bits | Hub, Repeater, Modem, Cables |
