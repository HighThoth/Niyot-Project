**What Is Bettercap?**

Bettercap, a portable framework written in GO, is often considered a Swiss army knife for its extensive capabilities in performing reconnaissance, attacking WiFi, and scanning Bluetooth low energy devices and Ethernet networks.

Its a tool used by many in cyber security , including penetration testers, reverse engineers, and security researchers, to perform {MITM} Man In The Middle attacks, also known as on-path attacks.  

**Some of its features include:**

. IP host discovery and reconnaissance

.Network spoofing attacks via ARP, DNS, NDP, DHCPv6 poisoning

.Port scanning

.WiFi network scanning and attacks like de-authentication and WPA/WPA2 handshake capturing 

&nbsp;       **Bettercap can be installed on Windows, Linux, macOS,and Andriod**

**INSTALLATION**

We can install bettercap by entering the command **sudo apt install bettercap** on our kali

**sudo apt install bettercap.**

Starting Bettercap: After installation, you can start Bettercap by running:

**sudo bettercap**

To execute a Man-In-The-Middle attack, identify devices connected to the network using the bettercap module net.probe, which can be found by typing help on the bettercap terminal.

**net.probe on**

To show all the devices that are connected to the same network with their IP, MAC, Name, etc. Now we need to copy the IP address of the devices on which we want to sniff.

**net.show**

Every time Bettercap is started you will get a command line interface with it. To use, type out the module name and any options you want. For example, to turn on arp spoofing you would type:

**arp.spoof on**

In the terminal interface. To change variables type set and the variable name. For instance, to set arp spoof targets type:

**set arp.spoof.targets \[target or target range here\]**

Turning on the sniffing and catching the packets.

**net.sniff on**

and you should be set. To find any other options of variables simply type help or help followed by the module name such as:

**help arp.spoof**