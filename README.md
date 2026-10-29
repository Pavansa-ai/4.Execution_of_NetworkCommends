# 4.Execution_of_NetworkCommands
## AIM :Use of Network commands in Real Time environment
## Software : Command Prompt And Network Protocol Analyzer
## Procedure: To do this EXPERIMENT- follows these steps:
<BR>
In this EXPERIMENT- students have to understand basic networking commands e.g cpdump, netstat, ifconfig, nslookup ,traceroute and also Capture ping and traceroute PDUs using a network protocol analyzer 
<BR>
All commands related to Network configuration which includes how to switch to privilege mode
<BR>
and normal mode and how to configure router interface and how to save this configuration to
<BR>
flash memory or permanent memory.
<BR>
This commands includes
<BR>
• Configuring the Router commands
<BR>
• General Commands to configure network
<BR>
• Privileged Mode commands of a router 
<BR>
• Router Processes & Statistics
<BR>
• IP Commands
<BR>
• Other IP Commands e.g. show ip route etc.
<BR>

## Output
```
Microsoft Windows [Version 10.0.26200.9711]
(c) Microsoft Corporation. All rights reserved.

C:\Users\acer>ipconfig

Windows IP Configuration


Ethernet adapter Ethernet 2:

   Connection-specific DNS Suffix  . :
   Link-local IPv6 Address . . . . . : fe80::135b:9242:8df3:9b73%3
   IPv4 Address. . . . . . . . . . . : 192.168.56.1
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . :

Wireless LAN adapter Local Area Connection* 1:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Local Area Connection* 2:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Wi-Fi:

   Connection-specific DNS Suffix  . :
   IPv6 Address. . . . . . . . . . . : 2406:7400:bb:6f1a:b128:8a2a:d055:76e7
   Temporary IPv6 Address. . . . . . : 2406:7400:bb:6f1a:c03d:ac00:5fc6:6916
   Temporary IPv6 Address. . . . . . : 2406:7400:bb:6f1a:cc3d:7c30:9abe:bcf2
   Link-local IPv6 Address . . . . . : fe80::6aa7:5320:c2c9:49fa%9
   IPv4 Address. . . . . . . . . . . : 192.168.0.107
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . : fe80::5ee9:31ff:fe17:47b8%9
                                       192.168.0.1

Ethernet adapter Bluetooth Network Connection:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Ethernet adapter Ethernet:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

C:\Users\acer>ping google.com

Pinging google.com [2404:6800:4007:804::200e] with 32 bytes of data:
Reply from 2404:6800:4007:804::200e: time=3ms
Reply from 2404:6800:4007:804::200e: time=3ms
Reply from 2404:6800:4007:804::200e: time=3ms
Reply from 2404:6800:4007:804::200e: time=8ms

Ping statistics for 2404:6800:4007:804::200e:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 3ms, Maximum = 8ms, Average = 4ms

C:\Users\acer>ipconfig /all

Windows IP Configuration

   Host Name . . . . . . . . . . . . : TMP215-75-G2
   Primary Dns Suffix  . . . . . . . :
   Node Type . . . . . . . . . . . . : Hybrid
   IP Routing Enabled. . . . . . . . : No
   WINS Proxy Enabled. . . . . . . . : No

Ethernet adapter Ethernet 2:

   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : VirtualBox Host-Only Ethernet Adapter
   Physical Address. . . . . . . . . : 0A-00-27-00-00-03
   DHCP Enabled. . . . . . . . . . . : No
   Autoconfiguration Enabled . . . . : Yes
   Link-local IPv6 Address . . . . . : fe80::135b:9242:8df3:9b73%3(Preferred)
   IPv4 Address. . . . . . . . . . . : 192.168.56.1(Preferred)
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Default Gateway . . . . . . . . . :
   DHCPv6 IAID . . . . . . . . . . . : 755630119
   DHCPv6 Client DUID. . . . . . . . : 00-01-00-01-30-49-AD-9F-74-D4-DD-CF-7E-A8
   NetBIOS over Tcpip. . . . . . . . : Enabled

Wireless LAN adapter Local Area Connection* 1:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Microsoft Wi-Fi Direct Virtual Adapter
   Physical Address. . . . . . . . . : FC-6D-77-6F-A9-DD
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes

Wireless LAN adapter Local Area Connection* 2:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Microsoft Wi-Fi Direct Virtual Adapter #2
   Physical Address. . . . . . . . . : FE-6D-77-6F-A9-DC
   DHCP Enabled. . . . . . . . . . . : No
   Autoconfiguration Enabled . . . . : Yes

Wireless LAN adapter Wi-Fi:

   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Intel(R) Wi-Fi 6E AX211 160MHz
   Physical Address. . . . . . . . . : FC-6D-77-6F-A9-DC
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes
   IPv6 Address. . . . . . . . . . . : 2406:7400:bb:6f1a:b128:8a2a:d055:76e7(Preferred)
   Temporary IPv6 Address. . . . . . : 2406:7400:bb:6f1a:c03d:ac00:5fc6:6916(Preferred)
   Temporary IPv6 Address. . . . . . : 2406:7400:bb:6f1a:cc3d:7c30:9abe:bcf2(Preferred)
   Link-local IPv6 Address . . . . . : fe80::6aa7:5320:c2c9:49fa%9(Preferred)
   IPv4 Address. . . . . . . . . . . : 192.168.0.107(Preferred)
   Subnet Mask . . . . . . . . . . . : 255.255.255.0
   Lease Obtained. . . . . . . . . . : 29 October 2026 20:38:17
   Lease Expires . . . . . . . . . . : 30 October 2026 22:30:43
   Default Gateway . . . . . . . . . : fe80::5ee9:31ff:fe17:47b8%9
                                       192.168.0.1
   DHCP Server . . . . . . . . . . . : 192.168.0.1
   DHCPv6 IAID . . . . . . . . . . . : 150760823
   DHCPv6 Client DUID. . . . . . . . : 00-01-00-01-30-49-AD-9F-74-D4-DD-CF-7E-A8
   DNS Servers . . . . . . . . . . . : 2406:7400:b0:b::2
                                       2406:7400:a:10::2
                                       183.82.243.66
                                       49.205.72.130
   NetBIOS over Tcpip. . . . . . . . : Enabled

Ethernet adapter Bluetooth Network Connection:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Bluetooth Device (Personal Area Network)
   Physical Address. . . . . . . . . : FC-6D-77-6F-A9-E0
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes

Ethernet adapter Ethernet:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :
   Description . . . . . . . . . . . : Realtek PCIe GbE Family Controller
   Physical Address. . . . . . . . . : 74-D4-DD-CF-7E-A8
   DHCP Enabled. . . . . . . . . . . : Yes
   Autoconfiguration Enabled . . . . : Yes

C:\Users\acer>hostname
TMP215-75-G2

C:\Users\acer>nslookup google.com
Server:  UnKnown
Address:  2406:7400:b0:b::2

Non-authoritative answer:
Name:    google.com
Addresses:  2404:6800:4007:804::200e
          142.250.66.14


C:\Users\acer>tracert google.com

Tracing route to google.com [2404:6800:4007:804::200e]
over a maximum of 30 hops:

  1     7 ms     1 ms     1 ms  2406:7400:bb:6f1a:5ee9:31ff:fe17:47b8
  2     8 ms     3 ms     2 ms  2406:7400:b1::2
  3     *        *        *     Request timed out.
  4     *        *        *     Request timed out.
  5     3 ms    11 ms     2 ms  2001:4860:1:1::285c
  6     8 ms     3 ms     3 ms  2001:4860:0:1::a21b
  7    24 ms     2 ms     6 ms  2001:4860:0:1::1c75
  8     8 ms     3 ms     2 ms  pnmaaa-ap-in-x0e.1e100.net [2404:6800:4007:804::200e]

Trace complete.

C:\Users\acer>netstat

Active Connections

  Proto  Local Address          Foreign Address        State
  TCP    127.0.0.1:5141         TMP215-75-G2:63922     ESTABLISHED
  TCP    127.0.0.1:46935        TMP215-75-G2:55503     ESTABLISHED
  TCP    127.0.0.1:46936        TMP215-75-G2:49694     ESTABLISHED
  TCP    127.0.0.1:46937        TMP215-75-G2:49695     ESTABLISHED
  TCP    127.0.0.1:49669        TMP215-75-G2:49670     ESTABLISHED
  TCP    127.0.0.1:49670        TMP215-75-G2:49669     ESTABLISHED
  TCP    127.0.0.1:49672        TMP215-75-G2:49673     ESTABLISHED
  TCP    127.0.0.1:49673        TMP215-75-G2:49672     ESTABLISHED
  TCP    127.0.0.1:49682        TMP215-75-G2:49683     ESTABLISHED
  TCP    127.0.0.1:49683        TMP215-75-G2:49682     ESTABLISHED
  TCP    127.0.0.1:49686        TMP215-75-G2:49687     ESTABLISHED
  TCP    127.0.0.1:49687        TMP215-75-G2:49686     ESTABLISHED
  TCP    127.0.0.1:49688        TMP215-75-G2:49689     ESTABLISHED
  TCP    127.0.0.1:49689        TMP215-75-G2:49688     ESTABLISHED
  TCP    127.0.0.1:49690        TMP215-75-G2:49691     ESTABLISHED
  TCP    127.0.0.1:49691        TMP215-75-G2:49690     ESTABLISHED
  TCP    127.0.0.1:49692        TMP215-75-G2:49693     ESTABLISHED
  TCP    127.0.0.1:49693        TMP215-75-G2:49692     ESTABLISHED
  TCP    127.0.0.1:49694        TMP215-75-G2:46936     ESTABLISHED
  TCP    127.0.0.1:49695        TMP215-75-G2:46937     ESTABLISHED
  TCP    127.0.0.1:50954        TMP215-75-G2:56580     ESTABLISHED
  TCP    127.0.0.1:55497        TMP215-75-G2:55498     ESTABLISHED
  TCP    127.0.0.1:55498        TMP215-75-G2:55497     ESTABLISHED
  TCP    127.0.0.1:55499        TMP215-75-G2:55500     ESTABLISHED
  TCP    127.0.0.1:55500        TMP215-75-G2:55499     ESTABLISHED
  TCP    127.0.0.1:55501        TMP215-75-G2:55502     ESTABLISHED
  TCP    127.0.0.1:55502        TMP215-75-G2:55501     ESTABLISHED
  TCP    127.0.0.1:55503        TMP215-75-G2:46935     ESTABLISHED
  TCP    127.0.0.1:55570        TMP215-75-G2:58995     ESTABLISHED
  TCP    127.0.0.1:56509        TMP215-75-G2:58995     ESTABLISHED
  TCP    127.0.0.1:56580        TMP215-75-G2:50954     ESTABLISHED
  TCP    127.0.0.1:57546        TMP215-75-G2:58995     ESTABLISHED
  TCP    127.0.0.1:58995        TMP215-75-G2:55570     ESTABLISHED
  TCP    127.0.0.1:58995        TMP215-75-G2:56509     ESTABLISHED
  TCP    127.0.0.1:58995        TMP215-75-G2:57546     ESTABLISHED
  TCP    127.0.0.1:63922        TMP215-75-G2:5141      ESTABLISHED
  TCP    192.168.0.107:52802    104.18.125.108:https   ESTABLISHED
^C
C:\Users\acer>arp -a

Interface: 192.168.56.1 --- 0x3
  Internet Address      Physical Address      Type
  192.168.56.255        ff-ff-ff-ff-ff-ff     static
  224.0.0.22            01-00-5e-00-00-16     static
  224.0.0.251           01-00-5e-00-00-fb     static
  224.0.0.252           01-00-5e-00-00-fc     static
  239.255.255.250       01-00-5e-7f-ff-fa     static

Interface: 192.168.0.107 --- 0x9
  Internet Address      Physical Address      Type
  192.168.0.1           5c-e9-31-17-47-b8     dynamic
  192.168.0.106         b2-c1-84-46-4e-53     dynamic
  192.168.0.255         ff-ff-ff-ff-ff-ff     static
  224.0.0.22            01-00-5e-00-00-16     static
  224.0.0.251           01-00-5e-00-00-fb     static
  224.0.0.252           01-00-5e-00-00-fc     static
  239.255.255.250       01-00-5e-7f-ff-fa     static
  255.255.255.255       ff-ff-ff-ff-ff-ff     static

C:\Users\acer>getmac

Physical Address    Transport Name
=================== ==========================================================
FC-6D-77-6F-A9-E0   Media disconnected
FC-6D-77-6F-A9-DC   \Device\Tcpip_{4B2633DD-E32D-4A78-87AA-C56D8DE8704C}
74-D4-DD-CF-7E-A8   Media disconnected
0A-00-27-00-00-03   \Device\Tcpip_{06E31D9C-1031-4DF2-8C1D-E778ABD13DD6}

C:\Users\acer>ipconfig \flushdns

Error: unrecognized or incomplete command line.

USAGE:
    ipconfig [/allcompartments] [/? | /all |
                                 /renew [adapter] | /release [adapter] |
                                 /renew6 [adapter] | /release6 [adapter] |
                                 /flushdns | /displaydns | /registerdns |
                                 /showclassid adapter |
                                 /setclassid adapter [classid] |
                                 /showclassid6 adapter |
                                 /setclassid6 adapter [classid] ]

where
    adapter             Connection name
                       (wildcard characters * and ? allowed, see examples)

    Options:
       /?               Display this help message
       /all             Display full configuration information.
       /release         Release the IPv4 address for the specified adapter.
       /release6        Release the IPv6 address for the specified adapter.
       /renew           Renew the IPv4 address for the specified adapter.
       /renew6          Renew the IPv6 address for the specified adapter.
       /flushdns        Purges the DNS Resolver cache.
       /registerdns     Refreshes all DHCP leases and re-registers DNS names
       /displaydns      Display the contents of the DNS Resolver Cache.
       /showclassid     Displays all the dhcp class IDs allowed for adapter.
       /setclassid      Modifies the dhcp class id.
       /showclassid6    Displays all the IPv6 DHCP class IDs allowed for adapter.
       /setclassid6     Modifies the IPv6 DHCP class id.


The default is to display only the IP address, subnet mask and
default gateway for each adapter bound to TCP/IP.

For Release and Renew, if no adapter name is specified, then the IP address
leases for all adapters bound to TCP/IP will be released or renewed.

For Setclassid and Setclassid6, if no ClassId is specified, then the ClassId is removed.

Examples:
    > ipconfig                       ... Show information
    > ipconfig /all                  ... Show detailed information
    > ipconfig /renew                ... renew all adapters
    > ipconfig /renew EL*            ... renew any connection that has its
                                         name starting with EL
    > ipconfig /release *Con*        ... release all matching connections,
                                         eg. "Wired Ethernet Connection 1" or
                                             "Wired Ethernet Connection 2"
    > ipconfig /allcompartments      ... Show information about all
                                         compartments
    > ipconfig /allcompartments /all ... Show detailed information about all
                                         compartments
```
## Result
Thus Execution of Network commands Performed 
