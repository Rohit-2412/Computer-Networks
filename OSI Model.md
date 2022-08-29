# OSI Model: Open Systems Interconnection

# TCP/IP: Transmission Control Protocol/Internet Protocol

## TCP {practical model} refers OSI model{theoretical model}

1. ## Physical Layer

-   data is represented in the form of **bits**
-   Line Control- analog to digital and analog to digital

2. ## Data Link Layer

-   DATA is represented in the form of packets
-   **frame** = information + address(Physical address of both destination and source)

3. ## Network Layer

-   Packet : information + ip address of both source and destination

4. ## Transport Layer

## TCP {Transmission Control Protocol}

-   Connection oriented Protocol
-   Reliable
-   Slow connection
-   acknowledement:
-   -   **pos** = packet of 32 bytes
-   -   **neg** = request timed out
-   packet by packet data transfer
-   packet by packet of 4 bits
-   **Example** = mail

## UDP {User Datagram Protocol}

-   connection less Protocol
-   unreliable
-   fast connection
-   -   8 packet parallel tranformation
-   redundancy(duplicacy) is there
-   -   if we sent 8 packet received 4
-   -   we will send 8 again
-   **example** = online gaming

1. ## Session Layer

-   session id
-   session expired

6. ## Presentation Layer

-   encryption and data compression

7. ## Application Layer

-   connection/communication with the user

max 20 connections

-   IP ADDRESS uses
-   ICMP {Internet Control Message Protocol}
-   MAC = MEDIA ACCESS CONTROL
