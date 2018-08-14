# vmnet
### Connect with network interfaces to read and write packets on guest operating systems.
## 概述
The vmnet framework is an API for virtual machines to read and write packets.

The API allows a Guest OS interface to be in host mode or shared mode. Interfaces in host mode can communicate with the native host system and other interfaces running in host mode. In shared mode, the network interface can send and receive packets to the Internet, the native host, and other interfaces running in sharing mode.
