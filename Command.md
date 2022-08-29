## ping = packet identifier grouper

`command:`
`ping address{ip address or url}`

> it will send and receive 4 packets

`ping www.google.com -n 10`

> for getting n number of packets

## MAC (Media Access Control) Address

`getmac`

```
Physical Address    Transport Name
=================== ==========================================================
48-9E-BD-74-9D-9A   Media disconnected
80-D2-1D-F0-B9-8F   \Device\Tcpip_{5F615021-6BD3-4C80-97E9-15E4BFE03783}
```

**RIP = Routing Information Protocol** <br>
**OSPF = open shortest path first (in case of traffic)**

> Length: 48 bits
> Further 24 bits and 24 bits

### To check vendor's MAC address (NIC card) connect wired or wireless device

> copy the first 3 octets of system's mac address and paste it on [https://dnschecker.org/mac-lookup.php](MAC Address)

## Tracing the route of packet from sender to receiver

```
tracert www.google.com
```

**Output:**

```
Tracing route to www.google.com [2404:6800:4002:81c::2004]
over a maximum of 30 hops:

  1    57 ms     5 ms     4 ms  fe80::4049:e7ff:fee3:eb85
  2     *        *        *     Request timed out.
  3   646 ms   609 ms   713 ms  2405:200:318:1503::3
  4   614 ms   712 ms   611 ms  2405:200:801:1500::65
  5   230 ms   286 ms   405 ms  2405:203:10:8200:130:26:30:99
  6   296 ms   297 ms   404 ms  2001:4860:1:1::f48
  7   178 ms   238 ms   161 ms  2404:6800:8095::1
  8   352 ms   325 ms   422 ms  2001:4860:0:1::1684
  9     *        *      163 ms  2001:4860:0:11dd::2
 10   284 ms   296 ms   620 ms  2001:4860:0:1a::1
 11   428 ms   424 ms   215 ms  2001:4860:0:1::54ff
 12   134 ms   302 ms    86 ms  del11s17-in-x04.1e100.net [2404:6800:4002:81c::2004]

Trace complete.
```

-   hop = router / node / end
-   16 = worst case
