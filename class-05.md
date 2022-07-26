# Windows Command Line Tools

The Server Message Block Protocol (SMB) is a client-server communication protocol. SMB can be used to share access to files, printers, serial ports, data on a network, and to carry transaction protocols for authenticates inter-process communication.

SMB works through a response-request protocol where a client makes requests and the server responds, such as file sharing between networked computers. 

Created in 1983 at IBM, SMB has continued to be improved with performance and security by Microsoft. SMB protocol dialects have been created over the years to support network requirements and to improve security and performance. Important SMB upgrades include: SMB 1.0 (1984), Samba (1992), CIFS (1996), NQ (1998), Netsmb (2004), SMB 2.0 (2006), Tuxera SMB (2009), Likewise (2009), SMB 2.1 (2010), SMB 3.0 (2012), MoSMB (2012), SMB 3.02 (2014), and SMB 3.1.1 (2015). 

SMB requires an open port on a computer or server to facilitate communication. SMB ports are usually 139 and 445. Port 139 is used by SMB dialects that communicate over NetBIOS, a transport layer protocol designed for use in Windows OS over a network. Port 445 is used by newer versions of SMB on top of a TCP stack, allowing SMB to communicate over the internet and means IP addresses can be used by SMB like file sharing. While SMB ports being open raises security concerns, there are Windows security updates in place to prevent exploits. A user can remain vigilant by patching their system when available, backing up their data, using a firewall, using a VPN, using a VLAN, and using MAC address filtering. 

## Things I would like to know more about
Understanding the functionality and versatility of SMB by using it myself.
