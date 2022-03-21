# A Simple Network Refresher :slightly_smiling_face:

**IP Addresses** - (Internet Protocol)
- Binary Notes
	-   8 Bits per Octet "***192***.168.0.1"
	- 	Binary IP = 11000000.10101000.00000000.00000001
	- 	32 Bits per IPv4 Address (32bit subnet mask - e.g: 255.255.255.0)
	- 	Binary is always halfed for Ocet (e.g: 128 - 64 - 32 - 16 - 8 - 2 - 1)
<br>
- **Private IP Classes**
	- Class A - 10.0.0.0--255.0.0.0 / 126 Networks / 16m Hosts
	- Class B - 172.16.0.0--172.31.0.0 / 255.255.0.0 / 16.3k Networks / 65k Hosts
	- Class C - 192.168.0.0--192.168.255.255 / 255.255.255.0 / 2.09m Networks / 254 Hosts
	- Loopback (LocalHost) - 127.0.0.0--127.0.0.7 / 255.255.255.0 / - / -
<br>

**MAC Addresses** - (Media Access Control)
- Physical (Hardware) Address tied to NIC (Network Interface Card)
	- 8 Bits per - Total 48 Bits Long
	- First 3 Pairs = Vendor, Last 3 = Device ID

**- TCP, UDP, Three-Way Handshake**
- TCP (Transmission Control Protocol)
	- Connection-oriented Protocol (HTTP, HTTPS, FTP, SSH)
	- SYN -> SYN ACK -> SYN (Handshake Interaction)
- UDP (User Datagram Protocol)
	- Connectionless Protocol (DNS, VoIP, Streaming Video)

**- Ports & Protocols**
- Common Ports & Protocols
	- **TCP**
		- FTP (21)
		- SSH (22)
		- Telnet (23)
		- SMTP (25)
		- DNS (53)
		- HTTP (80) / HTTPS (443)
		- POP3 (110)
		- SMB (139 + 445)
		- IMAP (143)
	- **UDP**
		- DNS (53)
		- DHCP (67, 68)
		- TFTP (69)
		- SNMP (161)

**- OSI Model** (**O**pen **S**ystems **I**nterconnection Model)
- (1) Physical Layer - (Data Cables, CAT5, CAT6, CAT6A, CAT7A)
- (2) Data Layer - (Switching, MAC Addresses)
- (3) Network Layer - (IP Addresses, Routing)
- (4) Transport Layer - (TCP, UDP)
- (5) Session Layer - (Session Management)
- (6) Presentation Layer - (WMV, JPEG, MOV, Media)
- (7) Application Layer - (HTTP, SMTP)

**- Subnetting**
- 255.0.0.0 (Class A)
- 255.255.0.0 (Class B)
- 255.255.255.0 (Class C)

**Whack (/) = Host Possibilities**
- 255.255.255.x
	- /32 = 1
	- /31 = 2
	- /30 = 4
	- /29 = 8
	- /28 = 16
	- /27 = 32
	- /26 = 64
	- /25 = 128
- 255.255.x.0
	- /24 = 256 (Most Common)
	- /23 = 512
	- /22 = 1,024
	- /21 = 2,048
	- /20 = 4,096
	- /19 = 8,192
	- /18 = 16,384
	- /17 = 32,768
- 255.x.0.0
	- /16 = 65,536
	- /15 = 131,072
	- /14 = 262,144
	- /13 = 524,288
	- /12 = 1,048,576
	- /11 = 2,097,152
	- /10 = 4,194,304
	- /9 = 8,388,608
- x.0.0.0
	- /8 = 16,777,216
	- /7 = 33,553,432
	- /6 = 67,108,864
	- /5 = 134,217,728
	- /4 = 268,435,456
	- /3 = 536,870,912
	- /2 = 1,073,741,824
	- /1 = 2,147,483,648

**Sources:**

https://codebeautify.org/ip-to-binary-converter (Binary conversion)

https://www.calculator.net/ip-subnet-calculator.html (Subnet Calculator)
