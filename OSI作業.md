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
Processor Management 管理程式
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


**boot process steps**
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



OSI 模型與TCP/IP protocal suite
_**OSI有七層?簡述其功能**_
**OSI(OPEN SYSTEM INTERCONNECTION)**
_OSI HAS 7 LAYER
LAYER (7) APPLICATION
LAYER (6) PRESENTATION
LAYER (5) SESSION
LAYER (4) TRANSPORT
LAYER (3) NETWORK
LAYER (2) DATA LINK
LAYER (1) PHYSICAL_
**7 LAYER FUNCTION**
LAYER (7) APPLICATION IS THE ONLY LAYER WHERE USER CAN COMMUNICATE WITH THE DATA(send and receive data and present meaningful data to user.)
+PROVIDES USER INTERFACE AND SUPPORT SERVICES FOR NETWORK APPLICATION LIKE MAIL TRANSFER/ BROWSING INTERNET, REMOTE DESKOPT CONNECTION (EX: HTTP/HTTPS/SMTP/FTP/TELNET)Hypertext Transfer Protocol (HTTP), File Transfer Protocol (FTP), Post Office Protocol (POP), Simple Mail Transfer Protocol (SMTP), and Domain Name System (DNS).
LAYER (6) PRESENTATION （use ssl)
-RESPONSIBLE FOR TRANSLATION / COMPRESSION / ENCYPTION OR DECRYPTION
 +Translation: vonvert data to machine understandable binary format (010101)
 +Compression: reducing data size to transfer more quickly and ensure that no appreciable loss in quality 
 +encrytipn or dycryption: encryption scamble data to unreadable form and decryption scramble data back to readable form
LAYER (5) SESSION 
 +Help setting up and managing conncetions enabling sending and rece
iving data (control how to start and end session)remian open and functional while data is stranfering and close when it end
 +AUTHENTICATe user's identity AND AUTHORIZe user to access the file
 +dialog controller (allow system to comunicate in duplex or half duplex mode)
 +help session management (manage which data packet belongs to which file)
LAYER (4) TRANSPORT
 +take data form session layer devide data into segment to transfer to netwoek layer  and also reassembling the segments and turning it back into data that can be used by the session layer
 +flow control: controls the amount of date being transmitted
 +Eerror control: checking if data was receive fully and correctly 
 LAYER (3) NETWORK
 +breaking up segments into network packets, and reassembling the packets on the receiving end.
 +routing packets
 LAYER (2) DATA LINK
 +node-to-node delivery of data.
 +ensure error-free transmission of information
 
 LAYER (1) PHYSICAL_
 +responsible for the physical cable or wireless connection between network nodes.
 +transmission of the raw data, which is simply a series of 0s and 1s, while taking care of bit rate control.

**底下網路設備運作在哪一層? Hub, switch, router, L4-switch, proxy**
-Hub works under the physical layer of the OSI model 
-switch works under the Datalink layer of the OSI model
-router under the network layer of the OSI model
-L4-switch work under transport layer
--PROXY work under applicaion layer
**TCP/IP有那些層?寫出與OSI七層模型的對應!**
*TCP/IP stands for Transmission Control Protocol/Internet Protocol Ssupport network communication
**The TCP/IP model consists of five layers: **
LAYER (5) APPLICATION
LAYER (4) TRANSPORT 
LAYER (3) NETWORK or INTERNET
LAYER (2) DATA LINK
LAYER (1) PHYSICAL_
APLLICATION, PRESENTATION AND SESSION LAYER IN OSI MODEL ARE REPRESENTED IN TCP/IP MODEL AS APPLICATION LAYER
-the combination of the Physical layer and Data Link layer are called network access layer
LAYER (1) PHYSICAL_
+convert binary sequence into signal and transmit them over local medial+ in charge of the data transmission between two networked devices.
LAYER (2) DATA LINK
+error control, flow control
LAYER (3) NETWORK or INTERNET
+add logical address or ip to the tcp or udp segment that recieve form transport layer to form ip packet (ensure ip packet can reach correct destination
+routing data
+path determination： chosing the best possible path for data delivery
LAYER (4) TRANSPORT 
+conncetion establishment
+data transfer:guarantee the deliverey of data
+error control, flow control
+conncetion termination
LAYER (5) APPLICATION
+provide means to access information on the network


HTTP vs HTTPs
hTTP Stand for hyper text transfer protocol that is used for viewing web pages
HTTP STANDARD is all imformation is sent in clear text in public internet so hacker can steal your information so this is the reason why https was developed
HTTPS stand for secure hyper t4ext transfer protocol and this is http with security feature https encrypt(scramble） the data  from http
HyperText Transfer Protocol 超文本傳輸協定
HTTP是一種用於分佈式、協作式和超媒體訊息系統的應用層協定
HTTP是全球資訊網的數據通信的基礎。
**DNS vs DNSsec**
DNS is domain name system is responsible for stranslating text host name into ip address
DNSSEC is DNS Security Extensions authentication and integrity of dns
**telnet vs ssh**
telnet is use to acceSS remote serves and aslo use to mange and configure  other network device such as (router, switch) and to check if port are close or open in serve
telnet is a command line tool and no graphica user interfaces. all command sent in clear text so no encryption
SSH is secure shell protect date from being attacked ssh does anything telfnet dose but it is a secure protocol
**ftp vs sftp** is used to transfer file over the network and use tcp to transfer file
FTP stand for file transfer protocol is standrad protocol  to transfer file between computer and servers over a tcp/ip netwok give the ability of website designer to uploade image, picture,.. it's not secure protocol
SFTP stand for secure file transfer protocol same as ftp but add secutrity layer data is encrypted using secure shell authenticates user and server
**smtp, pop3**
SMTP simple mail transfer protocol use for sending email authenticates and  directs  the transfer of email
Pop3 stand for pop office protocol 3 use for retreiving email form email serve (download the eamil  to your device from a mail serve and only download in your inbox)
**SNMP**
SNMP stand for simple network management protocol used to monitor and manage network devices connected over an IP and exchange management between network device

**TCP vs UDP**
TCP stand for transmission control protocol check for errors and to guarantee the deliverey of data TCP RELIABLE
UDP stand for use datagram protocol is also use for sending and recieving data but its not guarantee the delivery of data UDP is faster than TCP UDP UNRELIABLE

**TCP three-way handshaking(三項交握)**
TCP uses a three-way handshake to establish a reliable connection.
 step1: the client sends a syn segment to the serve asking for synchronization (mean the connection)
 step2: the serve replies with syn-ack(synchroniaztion and acknowledgement) the serve acknowledges the client's connection request and ask the client to open a connection too
 step3: client replies with ack (this time no more synchronization/conncetion request)
Then 2 way conncetion between them established
TCP syn flood attack
mean step 1:client sent syn to the serve with fake id
 step2: sever respond syn acc to fake ip (notice that client cant receive that syn ack) and dont get the feedback and stay open to wait for the respond) at that time maybe the first machine may be sending mutipile time so the whole thin perpetuate the volume so concetion is exhausted and mabe crash
the attacker sends repeated SYN packets to every port on the targeted server, often using a fake IP address

**IP** 
IP stand for internet protocol which is the set of rules governing(control)  the format of data sent via the internet or local network.
**ICMP**
ICMP stand for internet control message protocol use to diagnose network communication issues.
