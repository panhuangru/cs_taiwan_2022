windows作業系統提供許多工具與指令來服務使用者,底下哪些是windows作業系統所提供的預設工具(複選)? (A)電腦管理 (B)工作管理員 (C) mysql (D) netstat
題組:
小明使用的Windows作業系統遭受駭客攻擊
請問他可以使用底下哪一個工具檢查網路連線?(A)ping (B)工作管理員 (C) mysql (D) netstat
請問他可以使用底下哪一個工具檢查惡意程式執行時的process ID?(A)ping (B)工作管理員 (C) mysql (D) netstat
當小明找到惡意程式執行時的process ID後,他可以使用哪一個程式終止惡意程式的執行?(A)tsakkill (B)jobkill (C)kill (D)terminate
當使用netstat時,可以使用不同參數來顯示不同內容,若要顯示連線的程式PID時可載用哪一個參數?(A)n(B)a(C)o(D)p
(A)(B)(C)(D)
(A)(B)(C)(D)
問答題
**簡述作業系統的功能**(operating system functions)
Following are some of important functions of an operating System.

Memory Management 記憶體管理
Process Management 管理程式
Device Management設定裝置
File Management提供管理檔案功能
Network Management 網路管理
Security 監控安全性
window updates: 更新系統軟體
Control over system performance
Coordination between other software and users – 協調工作
Job accounting
Error detecting aids
Coordination between other software and users




**開機程序（boot process）**
This is the process of loading an opertaing system.It starts when computer turn on and end when operating system is loaded into memory


## boot process steps
_1. The Startup
switching the power ON. It supplies electricity to the main components like BIOS and processor.
_2. BIOS: Power On Self Test_
It is an initial test performed by the BIOS check on the input/output devices, computer’s main memory, disk drives, etc to find if it has any error
_3. Loading of OS_
OS is loaded into the main memory. OS starts working and executes all the initial files and instructions.
_4. System Configuration_
the drivers are loaded into the main memory. Drivers are programs that help in the functioning of the peripheral devices(TTHIET BI NGOAI VI CPU)
_5. Loading System Utilities_
System utilities are basic functioning programs, for example, volume control, antivirus, etc. In this step, system utilities are loaded into the memory
_6. User Authentication_
If any password has been set up in the computer system, the system checks for user authentication. Once the user enters the login Id and password correctly the system finally starts._



## OSI 模型與TCP/IP protocal suite
**OSI有七層?簡述其功能**
## OSI(OPEN SYSTEM INTERCONNECTION)describes seven layers that computer systems use to communicate over a network
- OSI HAS 7 LAYER as below:
 - LAYER (7) APPLICATION
 - LAYER (6) PRESENTATION
 - LAYER (5) SESSION
 - LAYER (4) TRANSPORT
 - LAYER (3) NETWORK
 - LAYER (2) DATA LINK
 - LAYER (1) PHYSICAL
**7 LAYER FUNCTION
## LAYER (7) APPLICATION:
 - IS THE ONLY LAYER WHERE USER CAN COMMUNICATE WITH THE DATA(send and receive data and present meaningful data to user.)
 - PROVIDES USER INTERFACE AND SUPPORT SERVICES FOR NETWORK APPLICATION(EX:Hypertext Transfer Protocol (HTTP), File Transfer Protocol (FTP), Post Office Protocol (POP), Simple Mail Transfer Protocol (SMTP), and Domain Name System (DNS).
## LAYER (6) PRESENTATION 
 - RESPONSIBLE FOR TRANSLATION / COMPRESSION / ENCYPTION OR DECRYPTION
  +Translation: vonvert data to machine understandable format 
  +Compression: reducing data size to transfer more quickly and ensure that no appreciable loss in quality 
  +encrytipn or dycryption: encryption scamble data to unreadable form and decryption scramble data back to readable form
  - presentation protocol:Apple Filing Protocol (AFP)/NetWare Core Protocol (NCP)/Secure Socket Layer (SSL),....
## LAYER (5) SESSION 
 +Help setting up and managing conncetions enabling sending and receiving data 
 +Control how to start and end session: remain open and functional while data is stranfering and close when it end
 +Authenticate user's identity and authourize user to access the file
 +dialog controller: allow system to comunicate in duplex or half duplex mode
 +session management: manage which data packet belongs to which file
 protocol:SMPP, Short Message Peer-to-Peer/PPTP, Point-to-Point Tunneling Protocol,...
## LAYER (4) TRANSPORT
 +segmentation: break data from r into segment 
 +flow control: controls the amount of date being transmitted
 +Error control: checking if data was receive fully and correctly
 +one of the most common example of transport layer is TCP and UDP
 ## LAYER (3) NETWORK
 +breaking up segments into network packets, and reassembling the packets on the receiving end.
 +routing:chose the best path to delivery from source to destination
 +logical addressing: add ip address into segment to send packets to destination
 
 ## LAYER (2) DATA LINK
 +node-to-node delivery of data.
 +ensure error-free transmission of information
 +add MAC address for data 
 
 ## LAYER (1) PHYSICAL_
 +responsible for the physical cable or wireless connection between network nodes.
 +while taking care of bit rate control.
 +convert binary into signal
 
 

**底下網路設備運作在哪一層? Hub, switch, router, L4-switch, proxy**
-Hub works under the physical layer of the OSI model 
-switch works under the Datalink layer of the OSI model
-router under the network layer of the OSI model
-L4-switch work under transport layer
--PROXY work under applicaion layer





**TCP/IP有那些層?寫出與OSI七層模型的對應!**
## TCP/IP stands for Transmission Control Protocol/Internet Protocol Ssupport network communication
- TCP/IP model consists of five layers:
  -LAYER (5) APPLICATION
  -LAYER (4) TRANSPORT 
  -LAYER (3) NETWORK or INTERNET
  -LAYER (2) DATA LINK
  -LAYER (1) PHYSICAL_
** APLLICATION, PRESENTATION AND SESSION LAYER IN OSI MODEL ARE REPRESENTED IN TCP/IP MODEL AS APPLICATION LAYER
** the combination of the Physical layer and Data Link layer are called network access layer
## LAYER (1) PHYSICAL_
+convert binary sequence into signal and transmit them over local medial
+in charge of the data transmission between two networked devices.
## LAYER (2) DATA LINK
 +flow control: controls the amount of date being transmitted
 +Error control: checking if data was receive fully and correctly
## LAYER (3) NETWORK or INTERNET
+add logical address or ip address into segment to send to destination
+routing data:chose the best path to delivery from source to destination
## LAYER (4) TRANSPORT 
+conncetion establishment
+data transfer:guarantee the deliverey of data
+also responsible for error and flow control
+conncetion termination
## LAYER (5) APPLICATION
+provide means to access information on the network




## HTTP vs HTTPs
* HTTP Stand for hyper text transfer protocol 
* An HTTP is an application layer protocol
* communication between different communication systems
* use for transferring data over a network.
- HTTP STANDARD is all imformation is sent in clear text in public internet so hacker can steal your information so this is the reason why https was developed
*HTTPS stand for secure hyper t4ext transfer protocol 
- this is http with security feature https encrypt(scramble） the data  from http
- ensures the security of the data
- The HTTPS protocol is secured due to the SSL protocol(secure sockets layer)



## DNS vs DNSsec**
- DNS is domain name system 
- DNS responsible for stranslating text host name into ip address
- DNS is not secure
- DNSSEC is DNS Security Extensions 
- authentication: protect users from redirection to fraudulent websites and unintended addresses.




## telnet vs ssh
-*telnet is use to acceSS remote serves
-aslo use to manage and configure  other network device such as (router, switch)
-check if port are close or open in serve
-telnet is a command line tool and no graphica user interfaces
-all command sent in clear text so no encryption
-* SSH is secure shell 
- enable two computer to communicate and share data 
- protect date from being attacked
- ssh does anything telfnet dose but it is a secure protocol
 
 
 
## ftp vs sftp is used to transfer file over the network and use tcp to transfer file
- FTP stand for file transfer protocol is standrad protocol  to transfer data between computer and servers over a tcp/ip netwok
- give the ability of website designer to uploade image, picture,..
- it's not secure protocol
- SFTP stand for secure file transfer protocol
- same as ftp but add secutrity layer data is encrypted 
- SFTP secure shell authenticates user and server

## smtp, pop3
- SMTP simple mail transfer protocol use for sending email. authenticates and  directs  the transfer of email
- widely used TCP protocol for email sending
- SMTP is a push protocol
-Pop3 stand for pop office protocol 3 use for retreiving email form email serve (download the eamil  to your device from a mail serve and only download in your inbox)
-POP3 transfers emails from the server to the client, allowing you to read them even if you are not connected to the internet
POP3 is known as a pop protocol


**SNMP**
-SNMP stand for simple network management protocol
-used to monitor and manage network devices connected over an IP 
-exchange management between network device



**TCP vs UDP**
-TCP stand for transmission control protocol
-check for errors and to guarantee the deliverey of data TCP RELIABLE
UDP stand for useR datagram protocol is also use for sending and recieving data but its not guarantee the delivery of data UDP is faster than TCP UDP UNRELIABLE



## TCP three-way handshaking(三項交握)**
TCP uses a three-way handshake to establish a reliable connection.
 step1: the client sends a syn segment to the serve asking for synchronization (mean the connection)
 step2: the serve replies with syn-ack(synchroniaztion and acknowledgement) the serve acknowledges the client's connection request and ask the client to open a connection too
 step3: client replies with ack (this time no more synchronization/conncetion request)
Then 2 way conncetion between them established




## TCP syn flood attack
mean step 1:client sent syn to the serve with fake id
 step2: sever respond syn acc to fake ip (notice that client cant receive that syn ack) and dont get the feedback and stay open to wait for the respond) at that time maybe the first machine may be sending mutipile time so the whole thin perpetuate the volume so concetion is exhausted and mabe crash
the attacker sends repeated SYN packets to every port on the targeted server, often using a fake IP address



**IP** 
IP stand for internet protocol 
-routing and addressing packets of data so that they can travel across networks and arrive at the correct destination
-allowing the sending computer to decide which path of packet to delivery

**ICMP**
-ICMP stand for internet control message protocol use to diagnose network communication issues.
-ICMP is used by a device, like a router, to communicate with the source of a data packet about transmission issue
-is mainly used to determine whether or not data is reaching its intended destination in a timely manner. 
-it can also be used in distributed denial-of-service (DDoS) attacks.
