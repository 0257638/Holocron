> [!important] Goal - Complete the installation and configuration of the Raspberry Pi Servers

Equipment Needed:
- Raspberry Pi
- SD Card
- Raspberry Pi power cable
- Computer with SD card reader
- HDMI Cable
- Monitor
- Keyboard 
- Mouse

# Operating System
In your teams install the Raspberry Pi OS.

https://www.raspberrypi.com/documentation/computers/getting-started.html#install-using-imager

## Boot into the Raspberry Pi

Once the OS has been installed, boot into the Raspberry Pi, and connect it to the CyberRange network via Wifi. 

Credentials:

| SSID         | Password     |
| ------------ | ------------ |
| `CyberRange` | `CyberRange` |
``
The Raspberry Pi can connect to the SchoolsNet to access the internet via Ethernet.

## Server name

As the servers need to interact, a naming policy will be created.


| Server            | Name          |
| ----------------- | ------------- |
| Web               | http_server   |
| Database          | db_server     |
| File              | file_server   |
| DNS               | dns_server    |
| Email             | email_server  |
| DHCP              | dhcp_server   |
| Domain Controller | domain_server |

You will need to rename the computer name for the Raspberry Pi to the assigned name.

# Software Installation

Depending on the purpose of the server, you will need to install different packages. **Research may be required**.

For instance,
 
| Server            | Software |
| ----------------- | -------- |
| Web               | Apache   |
| Database          | MariaDB  |
| File              |          |
| DNS               |          |
| Email             |          |
| DHCP              |          |
| Domain Controller |          |
For your software, find a tutorial on how to complete the installation.

