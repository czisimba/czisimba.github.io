---
layout: post
title: TCP/UDP常用端口速查
---

0/TCP,UDP 保留端口；不使用（若发送过程不准备接受回复消息，则可以作为源端口） 官方 
1/TCP,UDP TCPMUX（传输控制协议端口服务多路开关选择器） 官方 
5/TCP,UDP RJE（远程作业登录） 官方 
7/TCP,UDP ECHO（回显）协议 官方 
9/TCP,UDP DISCARD（丢弃）协议 官方 
11/TCP,UDP SYSTAT协议 官方 
13/TCP,UDP DAYTIME协议 官方 
15/TCP,UDP NETSTAT协议 官方 
17/TCP,UDP QOTD（Quote of the Day，每日引用）协议 官方 
18/TCP,UDP 消息发送协议 官方 
19/TCP,UDP CHARGEN（字符发生器）协议 官方 
20/TCP,UDP 文件传输协议 - 默认数据端口 官方 
21/TCP,UDP 文件传输协议 - 控制端口 官方 
22/TCP,UDP SSH (Secure Shell) - 远程登录协议，用于安全登录 文件传输（SCP，SFTP）及端口重新定向 官方 
23/TCP,UDP Telnet 终端仿真协议 - 未加密文本通信 官方 
25/TCP,UDP SMTP（简单邮件传输协议） - 用于邮件服务器间的电子邮件传递 官方 
26/TCP,UDP RSFTP - 一个简单的类似FTP的协议 非官方 
35/TCP,UDP QMS Magicolor 2 printer 非官方 
37/TCP,UDP TIME时间协议 官方 
39/TCP,UDP Resource Location Protocol（资源定位协议） 官方 
41/TCP,UDP 图形 官方 
42/TCP,UDP Host Name Server（主机名服务） 官方 
42/TCP,UDP WINS（WINS主机名服务） 非官方 
43/TCP WHOIS 协议 官方 
49/TCP,UDP TACACS 登录主机协议 官方 
53/TCP,UDP DNS（域名服务系统） 官方 
56/TCP,UDP 远程访问协议 官方 
57/TCP MTP，邮件传输协议 
67/UDP BOOTP（BootStrap协议）服务；同时用于DHCP（动态主机设定协议） 官方 
68/UDP BOOTP 客户端；同时用于DHCP（动态主机设定协议） 官方 
69/UDP TFTP（小型文件传输协议） 官方 
70/TCP Gopher信息检索协议 官方 
79/TCP Finger协议 官方 
80/TCP HTTP（超文本传输协议）- 用于传输网页 官方 
81/TCP HTTP预备（超文本传输协议） 官方 
81/TCP Torpark - Onion routing ORport 非官方 
82/UDP Torpark - 控制端口 非官方 
88/TCP Kerberos - 认证代理 官方 
101/TCP 主机名 
102/TCP ISO-TSAP 协议 
107/TCP 远程Telnet协议 
109/TCP POP（Post Office Protocol），“邮局协议”，第2版 
110/TCP POP3（“邮局协议”，第3版）- 用于接收电子邮件 官方 
111/TCP,UDP Sun协议 官方 
113/TCP ident - old server identification system, 仍然被IRC 服务器用来认证它的用户 官方 
115/TCP SFTP, 简单文件传输协议 
117/TCP UUCP-PATH 
118/TCP,UDP SQL 服务 官方 
119/TCP NNTP (Network News Transfer Protocol) - 用来收取新闻组的消息 官方 
123/UDP NTP (Network Time Protocol) - used for time synchronization 官方 
135/TCP,UDP EPMAP (End Point Mapper) / Microsoft RPC Locator Service 官方 
137/TCP,UDP NetBIOS NetBIOS Name Service 官方 
138/TCP,UDP NetBIOS NetBIOS Datagram Service 官方 
139/TCP,UDP NetBIOS NetBIOS Session Service 官方 
143/TCP,UDP IMAP4 (Internet Message Access Protocol 4) - used for retrieving E-mails 官方 
152/TCP,UDP BFTP, Background File Transfer Program
153/TCP,UDP SGMP, Simple Gateway Monitoring Protocol 
156/TCP,UDP SQL Service 官方 
158/TCP,UDP DMSP, Distributed Mail Service Protocol 
161/TCP,UDP SNMP (Simple Network Management Protocol) 官方 
162/TCP,UDP SNMPTRAP 官方 
170/TCP Print-srv 
179/TCP BGP (Border Gateway Protocol) 官方 
194/TCP IRC (Internet Relay Chat) 官方 
201/TCP,UDP AppleTalk Routing Maintenance 
209/TCP,UDP The Quick Mail Transfer Protocol 
213/TCP,UDP IPX 官方 
218/TCP,UDP MPP, Message Posting Protocol 
220/TCP,UDP IMAP, Interactive Mail Access Protocol, version 3 
259/TCP,UDP ESRO, Efficient Short Remote Operations 
264/TCP,UDP BGMP，Border Gateway Multicast Protocol 
308/TCP Novastor Online Backup 官方 
311/TCP Apple Server-Admin-Tool, Workgroup-Manager-Tool 
318/TCP,UDP TSP, Time Stamp Protocol 
323/TCP,UDP IMMP, Internet Message Mapping Protocol 
383/TCP,UDP HP OpenView HTTPs Operations Agent 
366/TCP,UDP SMTP, Simple Mail Transfer Protocol. ODMR, On-Demand Mail Relay 
369/TCP,UDP Rpc2portmap 官方 
371/TCP,UDP ClearCase albd 官方 
384/TCP,UDP A Remote Network Server System 
387/TCP,UDP AURP, AppleTalk Update-based Routing Protocol 
389/TCP,UDP LDAP (Lightweight Directory Access Protocol) 官方 
401/TCP,UDP UPS Uninterruptible Power Supply 官方 
411/TCP Direct Connect Hub port 非官方 
412/TCP Direct Connect Client-To-Client port 非官方 
427/TCP,UDP SLP (Service Location Protocol) 官方 
443/TCP HTTPS - HTTP Protocol over TLS/SSL (encrypted transmission) 官方 
444/TCP,UDP SNPP，Simple Network Paging Protocol 
445/TCP Microsoft-DS (Active Directory，Windows shares, Sasser worm，Agobot, Zobotworm) 官方 
445/UDP Microsoft-DS SMB file sharing 官方 
464/TCP,UDP Kerberos Change/Set password 官方 
465/TCP Cisco protocol 官方 
465/TCP SMTP over SSL 非官方 
475/TCP tcpnethaspsrv (Hasp services, TCP/IP version) 官方 
497/TCP dantz backup service 官方 
500/TCP,UDP ISAKMP，IKE-Internet Key Exchange 官方 
502/TCP,UDP Modbus，Protocol 
512/TCP exec, Remote Process Execution 
512/UDP comsat, together with biff：notifies users of new c.q. yet unread e-mail 
513/TCP Login 
513/UDP Who 
514/TCP rsh protocol - used to execute non-interactive commandline commands on a remote system and see the screen return 
514/UDP syslog protocol - used for system logging 官方 
515/TCP Line Printer Daemon protocol - used in LPD printer servers 
517/UDP Talk 
518/UDP NTalk 
520/TCP efs 
520/UDP Routing - RIP 官方 
513/UDP Router 
524/TCP,UDP NCP (NetWare Core Protocol) is used for a variety things such as access to primary NetWare server resources, Time Synchronization, etc. 官方 
525/UDP Timed, Timeserver
530/TCP,UDP RPC 官方 
531/TCP,UDP AOL Instant Messenger, IRC 非官方 
532/TCP netnews 
533/UDP netwall, For Emergency Broadcasts 
540/TCP UUCP (Unix-to-Unix Copy Protocol) 官方 
542/TCP,UDP commerce (Commerce Applications) 官方 
543/TCP klogin, Kerberos login 
544/TCP kshell, Kerberos Remote shell 
546/TCP,UDP DHCPv6 client 
547/TCP,UDP DHCPv6 server 
548/TCP AFP（Apple Filing Protocol） 
550/UDP new-rwho, new-who 
554/TCP,UDP RTSP (Real Time Streaming Protocol) 官方 
556/TCP Remotefs, rfs, rfs_server 
560/UDP rmonitor, Remote Monitor 
561/UDP monitor 
563/TCP,UDP NNTP protocol over TLS/SSL (NNTPS) 官方 
587/TCP email message submission（SMTP） (RFC 2476) Official 
591/TCP FileMaker 6.0 (and later) Web Sharing (HTTP Alternate, see port 80) 官方 
593/TCP,UDP HTTP RPC Ep Map（RPC over HTTP, often used by DCOM services and Microsoft Exchange Server） 官方 
604/TCP TUNNEL 
631/TCP,UDP IPP，Internet Printing Protocol 
636/TCP,UDP LDAP over SSL (encrypted transmission, also known as LDAPS) 官方 
639/TCP,UDP MSDP, Multicast Source Discovery Protocol 
646/TCP LDP, Label Distribution Protocol 
647/TCP DHCP Failover Protocol 
648/TCP RRP, Registry Registrar Protocol 
652/TCP DTCP, Dynamic Tunnel Configuration Protocol 
654/UDP AODV, Ad hoc On-Demand Distance Vector 
665/TCP sun-dr, Remote Dynamic Reconfiguration 非官方 
666/UDP 毁灭战士，电脑平台上的一系列第一人称射击游戏。 
674/TCP ACAP, Application Configuration Access Protocol 
691/TCP MS Exchange Routing 官方 
692/TCP Hyperwave-ISP 
694/UDP Linux-HA High availability Heartbeat port 非官方 
695/TCP IEEE-MMS-SSL 
698/UDP OLSR, Optimized Link State Routing 
699/TCP Access Network 
700/TCP EPP, Extensible Provisioning Protocol 
701/TCP LMP, Link Management Protocol. 
702/TCP IRIS over BEEP 
706/TCP SILC, Secure Internet Live Conferencing 
711/TCP TDP, Tag Distribution Protocol 
712/TCP TBRPF, Topology Broadcast based on Reverse-Path Forwarding 
720/TCP SMQP, Simple Message Queue Protocol 
749/TCP, UDP kerberos-adm, Kerberos administration 
750/UDP Kerberos version IV 
782/TCP Conserver serial-console management server 
829/TCP CMP (Certificate Management Protocol) 
860/TCP iSCSI 
873/TCP rsync File synchronisation protocol 官方 
901/TCP Samba Web Administration Tool (SWAT) 非官方 
902 VMware Server Console[1] 非官方 
904 VMware Server Alternate (if 902 is in use - ie SUSE linux) 非官方 
911/TCP Network Console on Acid (NCA) - local tty redirection over OpenSSH 
981/TCP SofaWare Technologies Remote HTTPS management for firewall devices running embedded Checkpoint Firewall-1 software 非官方 
989/TCP,UDP FTP Protocol (data) over TLS/SSL 官方 
990/TCP,UDP FTP Protocol (control) over TLS/SSL 官方 
991/TCP,UDP NAS (Netnews Admin System) 
992/TCP,UDP Telnet protocol over TLS/SSL 官方 
993/TCP IMAP4 over SSL (encrypted transmission) 官方 
995/TCP POP3 over SSL (encrypted transmission) 官方
1025/tcp NFS-or-IIS 非官方 
1026/tcp Often utilized by Microsoft DCOM services 非官方 
1029/tcp Often utilized by Microsoft DCOM services 非官方 
1058/tcp nim AIX Network Installation Manager 官方 
1059/tcp nimreg 官方 
1080/tcp SOCKS proxy 官方 
1099/tcp RMI Registry 官方 
1099/udp RMI Registry 官方 
1109/tcp Kerberos POP 
1140/tcp AutoNOC 官方 
1167/udp phone, conference calling 
1176/tcp Perceptive Automation Indigo home control server 官方 
1182/tcp,udp AcceleNet 官方 
1194/udp OpenVPN 官方 
1198/tcp,udp The cajo project Free dynamic transparent distributed computing in Java 官方
1200/udp Steam Friends Applet 官方 
1214/tcp Kazaa 官方 
1223/tcp,udp TGP: "TrulyGlobal Protocol" aka "The Gur Protocol" 官方 
1241/tcp,udp Nessus Security Scanner 官方 
1248/tcp NSClient/NSClient++/NC_Net (Nagios) 非官方 
1270/tcp,udp Microsoft Operations Manager 2005 agent (MOM 2005) 官方 
1311/tcp Dell Open Manage Https Port 非官方 
1313/tcp Xbiim (Canvii server) Port 非官方 
1337/tcp WASTE Encrypted File Sharing Program 非官方 
1352/tcp IBM Lotus Notes/Domino RPC 官方 
1387/tcp Computer Aided Design Software Inc LM (cadsi-lm ) 官方 
1387/udp Computer Aided Design Software Inc LM (cadsi-lm ) 官方 
1414/tcp IBM MQSeries 官方 
1431/tcp RGTP 官方 
1433/tcp,udp Microsoft SQL database system 官方 
1434/tcp,udp Microsoft SQL Monitor 官方 
1494/tcp Citrix Presentation Server ICA Client 官方 
1512/tcp,udp WINS 
1521/tcp nCube License Manager 官方 
1521/tcp Oracle database default listener, in future releases official port 2483 非官方 
1524/tcp,udp ingreslock, ingres 官方 
1526/tcp Oracle database common alternative for listener 非官方 
1533/tcp IBM Sametime IM - Virtual Places Chat 官方 
1547/tcp Laplink 官方 
1547/udp Laplink 官方 
1550 Gadu-Gadu (Direct Client-to-Client) 非官方 
1581/udp MIL STD 2045-47001 VMF 官方 
1589/udp Cisco VQP (VLAN Query Protocol) / VMPS 非官方 
1627 iSketch 非官方 
1677/tcp Novell GroupWise clients in client/server access mode 
1701/udp l2tp, Layer 2 Tunnelling protocol 
1716/tcp America's Army MMORPG Default Game Port 官方 
1723/tcp Microsoft PPTP VPN 官方 
1723/udp Microsoft PPTP VPN 官方 
1725/udp Valve Steam Client 非官方 
1755/tcp Microsoft Media Services (MMS, ms-streaming) 官方 
1755/udp Microsoft Media Services (MMS, ms-streaming) 官方 
1761/tcp,udp cft-0 官方 
1761/tcp Novell Zenworks Remote Control utility 非官方 
1762-1768/tcp,udp cft-1 to cft-7 官方 
1812/udp radius, RADIUS authentication protocol 
1813/udp radacct, RADIUS accounting protocol
1863/tcp Windows Live Messenger, MSN 官方 
1900/udp Microsoft SSDP Enables discovery of UPnP devices 官方 
1935/tcp Real Time Messaging Protocol (RTMP) raw protocol 官方 
1970/tcp,udp Danware Data NetOp Remote Control 官方 
1971/tcp,udp Danware Data NetOp School 官方 
1972/tcp,udp InterSystems Caché 官方 
1975-77/udp Cisco TCO (Documentation) 官方 
1984/tcp Big Brother - network monitoring tool 官方 
1985/udp Cisco HSRP 官方 
1994/TCP STUN-SDLC protocol for tunneling 
1998/tcp Cisco X.25 service (XOT) 
2000/udp Cisco SCCP (Skinny) 官方 
2000/tcp Cisco SCCP (Skinny) 官方 
2002/tcp Cisco Secure Access Control Server (ACS) for Windows 非官方 
2030 Oracle Services for Microsoft Transaction Server 非官方 
2031/tcp mobrien-chat - Mike O'Brien <mike@mobrien.com> November 2004 官方 
2031/udp mobrien-chat - Mike O'Brien <mike@mobrien.com> November 2004 官方 
2049/udp nfs, NFS Server 官方 
2049/udp shilp 官方 
2053/tcp knetd, Kerberos de-multiplexor 
2056/udp Civilization 4 multiplayer 非官方 
2073/tcp DataReel Database 官方 
2073/udp DataReel Database 官方 
2074/tcp Vertel VMF SA (i.e. App.. SpeakFreely) 官方 
2074/udp Vertel VMF SA (i.e. App.. SpeakFreely) 官方 
2082/tcp Infowave Mobility Server 官方 
2082/tcp CPanel, default port 非官方 
2083/tcp Secure Radius Service (radsec) 官方 
2083/tcp CPanel default SSL port 非官方 
2086/tcp GNUnet 官方 
2086/tcp WebHost Manager default port 非官方 
2087/tcp WebHost Manager default SSL port 非官方 
2095/tcp CPanel default webmail port 非官方 
2096/tcp CPanel default SSL webmail port 非官方 
2123/udp  gtpcv1 gtpcv2
2152/udp gtpuv1
2161/tcp ?-APC Agent 官方 
2181/tcp EForward-document transport system 官方 
2181/udp EForward-document transport system 官方 
2200/tcp Tuxanci game server 非官方 
2219/tcp NetIQ NCAP Protocol 官方 
2219/udp NetIQ NCAP Protocol 官方 
2220/tcp NetIQ End2End 官方 
2220/udp NetIQ End2End 官方 
2222/tcp DirectAdmin's default port 非官方 
2222/udp Microsoft Office OS X antipiracy network monitor [1] 非官方 
2301/tcp HP System Management Redirect to port 2381 非官方 
2302/udp ArmA multiplayer (default for game) 非官方 
2302/udp Halo: Combat Evolved multiplayer 非官方 
2303/udp ArmA multiplayer (default for server reporting) (default port for game +1) 非官方 
2305/udp ArmA multiplayer (default for VoN) (default port for game +3) 非官方 
2369/tcp Default port for BMC Software CONTROL-M/Server - Configuration Agent port number - though often changed during installation 非官方 
2370/tcp Default port for BMC Software CONTROL-M/Server - Port utilized to allow the CONTROL-M/Enterprise Manager to connect to the CONTROL-M/Server - though often changed during installation 非官方
2381/tcp HP Insight Manager default port for webserver 非官方 
2404/tcp IEC 60870-5-104 官方 
2427/udp Cisco MGCP 官方 
2447/tcp ovwdb - OpenView Network Node Manager (NNM) daemon 官方 
2447/udp ovwdb - OpenView Network Node Manager (NNM) daemon 官方 
2483/tcp,udp Oracle database listening port for unsecure client connections to the listener, replaces port 1521 官方 
2484/tcp,udp Oracle database listening port for SSL client connections to the listener 官方 
2546/tcp,udp Vytal Vault - Data Protection Services 非官方 
2593/tcp,udp RunUO - Ultima Online server 非官方 
2598/tcp new ICA - when Session Reliability is enabled, TCP port 2598 replaces port 1494 非官方 
2612/tcp,udp QPasa from MQSoftware 官方 
2710/tcp XBT Bittorrent Tracker 非官方 
2710/udp XBT Bittorrent Tracker experimental UDP tracker extension 非官方 
2710/tcp Knuddels.de 非官方 
2735/tcp NetIQ Monitor Console 官方 
2735/udp NetIQ Monitor Console 官方 
2809/tcp corbaloc:iiop URL, per the CORBA 3.0.3 specification. Also used by IBM WebSphere Application Server Node Agent 官方 
2809/udp corbaloc:iiop URL, per the CORBA 3.0.3 specification. 官方 
2944/udp Megaco Text H.248 非官方 
2945/udp Megaco Binary (ASN.1) H.248 非官方 
2948/tcp WAP-push Multimedia Messaging Service (MMS) 官方 
2948/udp WAP-push Multimedia Messaging Service (MMS) 官方 
2949/tcp WAP-pushsecure Multimedia Messaging Service (MMS) 官方 
2949/udp WAP-pushsecure Multimedia Messaging Service (MMS) 官方 
2967/tcp Symantec AntiVirus Corporate Edition 非官方 
3000/tcp Miralix License server 非官方 
3000/udp Distributed Interactive Simulation (DIS), modifiable default port 非官方 
3001/tcp Miralix Phone Monitor 非官方 
3002/tcp Miralix CSTA 非官方 
3003/tcp Miralix GreenBox API 非官方 
3004/tcp Miralix InfoLink 非官方 
3006/tcp Miralix SMS Client Connector 非官方 
3007/tcp Miralix OM Server 非官方 
3025/tcp netpd.org 非官方 
3050/tcp,udp gds_db (Interbase/Firebird) 官方 
3074/tcp,udp Xbox Live 官方 
3128/tcp HTTP used by web caches and the default port for the Squid cache 官方 
3260/tcp iSCSI target 官方 
3268/tcp msft-gc, Microsoft Global Catalog (LDAP service which contains data from Active Directory forests) 官方 
3269/tcp msft-gc-ssl, Microsoft Global Catalog over SSL (similar to port 3268, LDAP over SSL version) 官方 
3300/tcp TripleA game server 非官方 
3305/tcp,udp ODETTE-FTP 官方 
3306/tcp,udp MySQL Database system 官方 
3333/tcp Network Caller ID server 非官方 
3386/tcp,udp GTP' 3GPP GSM/UMTS CDR logging protocol 官方 
3389/tcp 远端桌面协定（RDP） 官方 
3396/tcp Novell NDPS Printer Agent 官方 
3689/tcp DAAP Digital Audio Access Protocol used by Apple’s iTunes 官方 
3690/tcp Subversion version control system 官方 
3702/tcp,udp Web Services Dynamic Discovery (WS-Discovery), used by various components of Windows Vista 官方 
3724/tcp World of Warcraft Online gaming MMORPG 官方 
3784/tcp,udp Ventrilo VoIP program used by Ventrilo 官方 
3785/udp Ventrilo VoIP program used by Ventrilo 官方 
3868 tcp,udp Diameter base protocol Official 
3872/tcp Oracle Management Remote Agent 非官方 
3899/tcp Remote Administrator 非官方 
3900/tcp Unidata UDT OS udt_os 官方 
3945/tcp Emcads server service port, a Giritech product used by G/On 官方
4000/tcp Diablo II game 非官方 
4007/tcp PrintBuzzer printer monitoring socket serve 非官方 
4089/udp OpenCORE Remote Control Service 官方 
4089/tcp OpenCORE Remote Control Service 官方 
4093/udp PxPlus Client server interface ProvideX 官方 
4093/tcp PxPlus Client server interface ProvideX 官方 
4096/udp Bridge-Relay Element ASCOM 官方 
4100 WatchGuard Authentication Applet - default port 非官方 
4111/tcp,udp Xgrid 官方 
4111/tcp Microsoft Office SharePoint Portal Server - default administration port 非官方 
4226/tcp,udp Aleph One (computer game) 非官方 
4224/tcp Cisco CDP Cisco discovery Protocol 非官方
4569/udp Inter-Asterisk eXchange 非官方 
4662/tcp OrbitNet Message Service 官方 
4662/tcp port often used by eMule 非官方 
4664/tcp Google Desktop Search 非官方 
4672/udp eMule - port often used 非官方 
4894/tcp LysKOM Protocol A 官方 
4899/tcp Radmin remote administration tool (program sometimes used as a Trojan horse) 官方 
5000/tcp commplex-main 官方 
5000/tcp UPnP - Windows network device interoperability 非官方 
5000/tcp,udp VTun - VPN Software 非官方 
5001/tcp,udp Iperf (Tool for measuring TCP and UDP bandwidth performance) 非官方 
5001/tcp Slingbox and Slingplayer 非官方 
5003/tcp FileMaker Filemaker Pro 官方 
5004/udp RTP Real-time Transport Protocol 官方 
5005/udp RTP Real-time Transport Protocol 官方 
5031/tcp,udp AVM CAPI-over-TCP (ISDN over Ethernet tunneling) 非官方 
5050/tcp Yahoo! Messenger Yahoo! Messenger 官方
5051/tcp ita-agent Symantec Intruder Alert 官方 
5060/tcp Session Initiation Protocol (SIP) 官方 
5060/udp Session Initiation Protocol (SIP) 官方 
5061/tcp Session Initiation Protocol (SIP) over Transport Layer Security (TLS) 官方 
5093/udp SPSS License Administrator (SPSS) 官方 
5104/tcp IBM NetCOOL / IMPACT HTTP Service 非官方 
5106/tcp A-Talk Common connection 非官方 
5107/tcp A-Talk Remote server connection 非官方 
5110/tcp ProRat Server 非官方 
5121/tcp Neverwinter Nights 官方 
5176/tcp ConsoleWorks default UI interface 非官方 
5190/tcp ICQ and AOL Instant Messenger 官方 
5222/tcp XMPP/Jabber - client connection 官方 
5223/tcp XMPP/Jabber - default port for SSL Client Connection 非官方 
5269/tcp XMPP/Jabber - server connection 官方 
5351/tcp,udp NAT Port Mapping Protocol - client-requested configuration for inbound connections through network address translators 官方 
5353/udp mDNS - multicastDNS 
5402/tcp,udp StarBurst AutoCast MFTP 官方 
5405/tcp,udp NetSupport 官方 
5421/tcp,udp Net Support 2 官方 
5432/tcp PostgreSQL database system 官方 
5445/udp Cisco Vidéo VT Advantage 非官方 
5495/tcp Applix TM1 Admin server 非官方
5498/tcp Hotline tracker server connection 非官方 
5499/udp Hotline tracker server discovery 非官方 
5500/tcp VNC remote desktop protocol - for incoming listening viewer, Hotline control connection 非官方 
5501/tcp Hotline file transfer connection 非官方 
5517/tcp Setiqueue Proxy server client for SETI@Home project 非官方 
5555/tcp Freeciv multiplay port for versions up to 2.0, Hewlett Packard Data Protector, SAP 非官方 
5556/tcp Freeciv multiplay port 官方 
5631/tcp Symantec pcAnywhere 官方 
5632/udp Symantec pcAnywhere 官方 
5666/tcp NRPE (Nagios) 非官方 
5667/tcp NSCA (Nagios) 非官方 
5800/tcp VNC remote desktop protocol - for use over HTTP 非官方 
5814/tcp,udp Hewlett-Packard Support Automation (HP OpenView Self-Healing Services) 官方 
5900/tcp VNC remote desktop protocol (used by ARD) 官方 
6000/tcp X11 - used between an X client and server over the network 官方 
6001/udp X11 - used between an X client and server over the network 官方 
6005/tcp Default port for BMC Software CONTROL-M/Server - Socket Port number used for communication between CONTROL-M processes - though often changed during installation 非官方 
6050/tcp Brightstor Arcserve Backup 非官方 
6051/tcp Brightstor Arcserve Backup 非官方 
6100/tcp Vizrt System 非官方 
6110/tcp softcm HP SoftBench CM 官方 
6110/udp softcm HP SoftBench CM 官方 
6111/tcp spc HP SoftBench Sub-Process Control 官方 
6111/udp spc HP SoftBench Sub-Process Control 官方 
6112/tcp "dtspcd" - a network daemon that accepts requests from clients to execute commands and launch applications remotely 官方 
6112/tcp Blizzard's Battle.net gaming service, ArenaNet gaming service 官方 
6129/tcp Dameware Remote Control 非官方 
6257/udp WinMX (see also 6699) 非官方 
6346/tcp,udp gnutella-svc (FrostWire, Limewire, Bearshare, etc.) 官方 
6347/tcp,udp gnutella-rtr 官方 
6444/tcp,udp Sun Grid Engine - Qmaster Service 官方 
6445/tcp,udp Sun Grid Engine - Execution Service 官方 
6502/tcp,udp Danware Data NetOp Remote Control 非官方 
6522/tcp Gobby (and other libobby-based software) 非官方 
6543/udp Jetnet - default port that the Paradigm Research & Development Jetnet protocol communicates on 非官方 
6566/tcp SANE (Scanner Access Now Easy) - SANE network scanner daemon 非官方 
6600/tcp Music Playing Daemon (MPD) 非官方 
6619/tcp,udp ODETTE-FTP over TLS/SSL 官方 
6665-6669/tcp Internet Relay Chat 官方 
6679/tcp IRC SSL (Secure Internet Relay Chat) - port often used 非官方 
6697/tcp IRC SSL (Secure Internet Relay Chat) - port often used 非官方 
6699/tcp WinMX (see also 6257) 非官方 
6881-6999/tcp,udp BitTorrent full range of ports used most often 非官方 
6891-6900/tcp,udp Windows Live Messenger (File transfer) 官方 
6901/tcp,udp Windows Live Messenger (Voice) 官方 
6969/tcp acmsoda 官方 
6969/tcp BitTorrent tracker port
