**Beginner's Guide to Armitage**

**Introduction:** Armitage is the graphical user interface (GUI) version of the popular penetration testing tool Metasploit. Unlike Metasploit's command-line interface, Armitage allows users to perform pen testing tasks through clicks and right-clicks, making it more user-friendly.

**Getting Started:**

- Armitage is installed by default in Kali Linux and can be started using the command "armitage".
- Start the PostgreSQL service used by Armitage.
- Start the msfdb service.

**Connecting Armitage:**

- Upon starting Armitage, it needs to connect to the Metasploit RPC server. Click on "Connect".

**Navigating Armitage:**

- Armitage has three sections:
    1.  Metasploit modules displayed graphically.
    2.  Visual representation of the network being tested.
    3.  Console section for Metasploit commands.

**Menus of Armitage:**

- Armitage offers various menus for different tasks, such as adding hosts, setting labels, performing scans, and finding attacks.

**Adding Attacker Machine:**

- To add the attacker machine, go to Host > Add Host and enter the IP address.

**Adding OS and Label:**

- Right-click on the attacker system, go to Host > Operating System to set the OS.
- Similarly, go to Host > Set Label to give a name to the attacker system.

**Adding Target System:**

- Perform a ping scan to detect live systems on the target network: Host > Nmap Scan > Ping Scan.
- Enter the IP address range to scan for live systems.

**Scanning for Open Ports:**

- Perform a quick scan to detect open ports on the target: Hosts > Nmap > Quick Scan.
- Perform a comprehensive scan to detect the target's operating system.

**Finding Attacks:**

- Go to Attacks > Find Attacks to discover exploits related to the target system.

**Launching an Exploit:**

- Select an exploit from the Attack menu, such as "ms08_067 vulnerability".
- Click on "Launch" to execute the exploit.

**Conclusion:**

- Armitage simplifies the penetration testing process by providing a graphical interface for Metasploit, making it easier for beginners to perform security testing.