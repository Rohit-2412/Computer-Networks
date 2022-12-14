# **CSE 307**

## IP Address

Types of IP Address:

1. Classful = IPv4
2. Classless = IPv6

### 1. IPv4 : consists of 32 bits

Example: 192.1.1.1 > here 192 or the first octet is used to find the class of IP Address

### **Classes in IP Address for IPv4**

1. A = 0 - 126

    > 1 NETWORK ID & 3 HOST ID
    > default subnet mask = 255.0.0.0

> `127 is used for local machine`

1. B = 128 - 191

    > 2 NETWORK ID & 2 HOST ID
    > default subnet mask = 255.255.0.0

2. C = 192 - 223

    > 3 NETWORK ID & 1 HOST ID
    > default subnet mask = 255.255.255.0

3. D = _Research & Development_
4. E = Future Use

### 2. IPv6

    1. Example: 2345:0425:2CA1:0000:0000:0567:5673:23b5
    2. Size = 128 bits

`Default ip address is based upon class of ip address`

` Bruteforce = A technique used to break passwords forcefully`

## HUB

> A device which is used to send data packets to all devices connected to the network ( 1 to all )

## Switch (smart device)

> A device which is used to send data packets only to one device ( 1 to 1 )

-   Has memory
-   Total ports = 24
-   Unicast the data
-   MAC Table
-   Broadcast only once
-   Multiport network device
-   DLL Table
-   Collision decreases
-   IPv6 introduced for bigger network

-   ### DOS = Disk Operating System
-   ### DOS = Denial of Service

## Types of Cable:

1.  Straight Cable
    > Used to connect two dissimilar devices
    -   Example: Switch to PC
2.  Cross Cable

    > Used to connect two similar devices

    -   Example: Switch to Switch

    ### **Rule for wire connection**

    -   1 -> 3

    -   2 -> 6

    ### _Color combination_

    -   Blue & Blue White

    -   Orange & Orange White

    -   Brown & Brown White

    -   Green & Green White

    *   ## Diagram: <br>
        ![Image](https://media.fs.com/images/community/upload/wangEditor/201911/06/_1573024232_I7qO4uoRQQ.jpg)

**3. Patch Cable**

> It can work like both cables- straight and cross

-   Telephone wire uses `RJ11` connector

-   First side wire arrangement doesn't matter in cross cable, other end matters

## Types of data sending

1. unicast - **one to one** connection
2. multicast - **selected** persons
3. broadcast - **one to all** (2 or 200000)

## Types of IP address assigning

### DHCP = Dynamic Host Configuration Protocol

> 1. DHCP = automatic ip **address** assigning

> 2. Static = Manual assign

-   `loop = repeating`

> comes when we connect devices under mesh topology
