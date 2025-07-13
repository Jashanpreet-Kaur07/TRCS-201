# Daily Diary

# DAY-1

I am Jashanpreet kaur from department of Computer Science Engineering.Today is my first day of training as a student of second year. On first day of the training, we learned about different types of companies such as:
        
        Product based companies
        Service based companies
        Startups

Then we learned about difference between linux and windows operating systems.As linux is an open source , it is free and we can use it anywhere while windows is not an open source.Linux has more security options whereas windows does not have the same level of security.Also,linux provides privacy and is license-free.

Then, we installed linux on our laptops.Here are the steps we followed:
 
        Download Oracle VirtualBox 7.1.10    
        Download Microsoft Visual Studio C++ 2019
        Download Ubuntu (Linux) 24.04.2 LTS

Then, we learned that 'LTS' means 'Long Term Support' , '24' represents the year , '04' represents the month , '2' represents the version updated.
After downloading these files,we discussed about career options in computer science engineering and also talked about productive companies in each career field.
Then, we came to know about booting and its types.

**Booting:**
It is the process of starting your computer and loading the operating system.

**Types of Booting:**
      
       Cold or Hard Booting: This refers to start a computer from a completely powered-off state.
       Soft or Warm Booting: This involves restarting a computer without completely cutting off power often done through the operating system.


# DAY - 2 

On second day of the training, we revise the previous work and start with learning some core concepts such as:

**Kernel:**
It is a computer program that is a core of a computer's operating system with complete control over everything in the system.

**Shell:**
It is a program that acts as an interface between the user and the operating system.


![Screenshot 2025-06-27 213109](https://github.com/user-attachments/assets/6557021f-f302-4be3-bda3-8d2b1b9ad069)


**Types of Shell:**

       Bash - Most common shell (Bourne-Again Shell)
       Sh - Original shell (Bourne Shell)
       Zsh - More additional features
      Fish - Interactive and modern

**Categories of Shell:**

      Command line shell
      Graphical shell

After discussing the linux shell, we learned about the file structure system.This structure organizes how files and directories are arranged on the system.
Then, we covered several basic shell commands:

      ls: Lists the contents of a directory.

      whoami: Displays the current username.

      date: Shows the current date and time.

      cd: Changes the current directory.
        Syntax: cd directory_name

      mkdir: Make new directory.
        Syntax: mkdir directory_name

      cat: Create a file with content.
        Syntax: cat>filename

      touch: Create file without content.
        Syntax: touch filename

      cp: Copies file from one location to another.
        Syntax: cp src_file.txt des_file.txt

      pwd: prints the current working directory.
        Syntax: pwd

      whereis: Locates the binary,source and manual pages files for a command.
        Syntax: whereis command_name

      whatis: Provides a brief one-line description of a commmand. 
        Syntax: whatis command_name

Here are the screenshots of commands which I had practised:

![VirtualBox screenshot2](https://github.com/user-attachments/assets/79d2b312-7ddf-47c5-a922-a9b9cfc07086)

![VirtualBox screenshot3](https://github.com/user-attachments/assets/0f5e6e56-d307-466b-be5b-fee04f283295)

![VirtualBox screenshot 4](https://github.com/user-attachments/assets/48357a71-3891-4d31-bf73-8b7021b9759e)



# DAY - 3   **[Linux File Permissions, Redirection & Pipes]**

**Topics covered:**

1. File Permissions using chmod

   * Modified file permissions to control access:
   
       chmod 444 filename - read only for all users

       chmod 644 filename - read/write for owner,read-only for others

       chmod +X filename.sh - make a shell script executable

   ![Day  3](https://github.com/user-attachments/assets/e3148ab3-c2a6-4e5c-85ac-657e477a3121)

   ![day 3](https://github.com/user-attachments/assets/26cc32b9-0bf4-4b86-9946-16da74b3b67c)

   ![day3](https://github.com/user-attachments/assets/dd338718-2a8d-4fe5-9014-7e4f3f84e679)



3. Shell Script Creation (.sh files)
   
    * Created basic shell scripts using nano

    * Saved with .sh extension

    * Made executable using chmod +X

    * Ran scripts using: ./filename.sh

4. Input/Output Redirection

    * Used redirection operators:

       \> → write to a file
     
      \>> → append to a file

      \<  → read input from file

      ![1](https://github.com/user-attachments/assets/63413ef1-d198-43a2-83b0-0a8f7c0d88cb)

      

5. Pipes ( \| )
   
     * Connected commands to filter/process output:

       ![2](https://github.com/user-attachments/assets/56a3e618-eaaf-4404-8473-11afbb2555c2)

       ![3](https://github.com/user-attachments/assets/888be08f-5ca4-48d9-86f1-12e4ef674c9c)


# Example of using variable:
   ![5](https://github.com/user-attachments/assets/b9b218bd-6742-4664-a6c7-0f4a10671500)

   ![4](https://github.com/user-attachments/assets/37668554-ab0e-4073-990b-05af7b159162)

# Example of making table of a number:
  ![6](https://github.com/user-attachments/assets/55038f88-97f1-4e24-8ecf-3b5d5ef378c4)

  ![7](https://github.com/user-attachments/assets/818dba48-b14f-4a59-99f2-ebc7a7cfb49e)

# Example of comparing two numbers:
  ![8](https://github.com/user-attachments/assets/9138af8a-5b21-48ea-abe9-c4a4a1b6a6e2)
  
  ![9](https://github.com/user-attachments/assets/96a7116d-c68a-4d69-8137-a1a1cc2346c6)
  

 # DAY - 4   

 **File Compression**
 
 It is the process of reducing the size of a file or group of files, making them take up less storage space.

 **Why do we compress files?**
 
 - To reduce their size
 - To save storage space
 - To transfer files faster

**Syntax to Compress Files:** gzip filename 

**Example:** gzip notes.txt **→ Creates** notes.txt.gz

(It deletes notes.txt)

**Syntax to Uncompress Files:** gunzip filename.txt.gz  

**If want to keep the original file too**
**Use -k flag**

**Syntax:** gzip -k notes.txt

**Now:** 
- notes.txt (kept)
- notes.txt.gz (created)

# Wildcards

•Special characters used to match and expand filenames.
| Wildcard | Meaning                   | Example                 | Matches                  |
|----------|---------------------------|-------------------------|--------------------------|
| `*`      | Matches zero or more characters | `ls *.txt`              | a.txt, notes.txt, file123.txt |
| `?`      | Matches exactly one character | `ls file?.txt`          | file1.txt, fileA.txt (not file12.txt) |
| `[]`     | Matches one character from the set | `ls file[12].txt`       | file1.txt, file2.txt     |
| `[a-z]`  | Matches one character from a range | `ls file[a-c].txt`      | filea.txt, fileb.txt, filec.txt |
| `[! ]`   | Matches one character not in set | `ls file[10-9].txt`     | fileX.txt (not file1.txt) |
| `{}`     | Brace expansion for multiple patterns | `cp file{1,2,3}.txt /backup/` | file1.txt, file2.txt, file3.txt |



 # Assignment - Escaping Characters

| Wildcard | Meaning                   | Example                 | Matches                  |
|----------|---------------------------|-------------------------|--------------------------|
| `*`      | Matches zero or more characters | `ls *.txt`              | a.txt, notes.txt, file123.txt |
| `?`      | Matches exactly one character | `ls file?.txt`          | file1.txt, fileA.txt (not file12.txt) |
| `[]`     | Matches one character from the set | `ls file[12].txt`       | file1.txt, file2.txt     |
| `[a-z]`  | Matches one character from a range | `ls file[a-c].txt`      | filea.txt, fileb.txt, filec.txt |
| `[! ]`   | Matches one character not in set | `ls file[10-9].txt`     | fileX.txt (not file1.txt) |
| `{}`     | Brace expansion for multiple patterns | `cp file{1,2,3}.txt /backup/` | file1.txt, file2.txt, file3.txt |



# Hardware 

Hardware refers to the physical parts of computer system means the components which we can see and touch.

| Category               | Description                                     | Examples                                              |
|------------------------|-------------------------------------------------|-------------------------------------------------------|
| 1. Input Devices       | Used to enter data into the computer            | Keyboard, Mouse, Scanner, Microphone, Webcam          |
| 2. Output Devices      | Used to display or output results from the computer | Monitor, Printer, Speaker, Projector                |
| 3. Processing Unit     | Performs all calculations and tasks             | CPU (Central Processing Unit)                         |
| 4. Storage Devices     | Used to store data permanently or temporarily   | Hard Drive (HDD), SSD, USB drive, CD/DVD              |
| 5. Communication Devices | Used for data exchange between computers        | Modem, Network Interface Card (NIC), Router           |


# Components of CPU Cabinet

| Category           | Examples                                 | Purposes                                                                    |
|--------------------|------------------------------------------|-----------------------------------------------------------------------------|
| Input Devices      | Keyboard, Mouse, Scanner, Microphone     | Used to enter data into the computer, allows user interaction.              |
| Processing Devices | CPU (Central Processing Unit), GPU (Graphics Processing Unit) | Manages and processes data; executes instructions.                        |
| Output Devices     | Monitor, Printer, Speakers               | Displays or outputs information and results processed by the computer.      |
| Storage Devices    | Hard Disk Drive (HDD), Solid State Drive (SSD), USB Flash Drive | Retains data and information for long-term access.                        |
| Motherboards       | Main motherboard board                   | The main circuit board connecting and facilitating communication among components. |
| Power Supply Units (PSU) | PSU                                      | Converts electrical power and provides it to the computer components.       |
| Cooling Devices    | Fans, Heat sinks                         | Maintains optimal operating temperatures of internal components.            |
| Networking         | Network interface Card (NIC)             | Connects the computer to networks for communication and internet access.       |

# Motherboard

It is also known as **Printed Circuit Board**.

![image](https://github.com/user-attachments/assets/424a04aa-712a-4ded-b457-11afafa6025d)

# Difference between RAM and Hard Disk

![image](https://github.com/user-attachments/assets/44839a99-5a44-4d65-b5cb-bf6a73aa9c70)

# Difference between RAM and Cache Memory

![image](https://github.com/user-attachments/assets/9d92cbb8-1625-4cf3-85ff-fb87d0aae682)

# ROM

ROM stands for Read-Only Memory. It is a non-volatile memory was used to operate the system. As its name refers to read-only memory, we can only read the stored programs and data.

- Information stored in ROM is permanent.
- Information and programs are stored on ROM in binary format (0s and 1s).
- It is used in the start-up process of the computer.

  ![image](https://github.com/user-attachments/assets/64f6e9eb-d3f2-46cd-97e8-ab56417fe91b)


# DAY - 5

# Computer Hardware and Troubleshooting

**HDD**
An HDD (Hard Disk Drive) is a non-volatile storage device commonly used in computers to store the operating system, software applications, files, and data persistently. It retains data even when the computer is powered off. It consists of one or more rigid rotating disks (platters) coated with magnetic material, along with read/write heads that move across the disk surfaces to access data.

**Features of HDD**

| Feature                   | Description                     | Typical Value                  |
|---------------------------|---------------------------------|-------------------------------|
| Storage Capacity          | The amount of data the HDD can store | 1TB, 2TB, 4TB                 |
| Rotational Speed          | Speed at which platters spin     | 5400 RPM, 7200 RPM             |
| Interface                 | Connection interface             | SATA III, NVMe                 |
| Cache Size               | Internal buffer memory           | 64MB, 128MB                   |
| Form Factor              | Physical size of the drive       | 3.5 inch, 2.5 inch             |
| Mean Time Between Failures (MTBF) | Reliability estimate         | 1 million hours                |

**Types of HDD**

🖥️ 1. Desktop HDD

- Use: Regular computers at home or office

- Size: Usually 3.5 inches

- Features: Good storage capacity, average speed

- Example Use: Storing files, games, and software for personal or office work

💻 2. Laptop HDD

- Use: Portable computers

- Size: Smaller — typically 2.5 inches

- Features: Lower power usage, more compact

- Example Use: Lightweight storage for mobile computing

🏢 3. Enterprise HDD

- Use: Servers and data centers

- Size: 2.5 or 3.5 inches

- Features: Designed for 24/7 operation, fast, highly reliable

- Example Use: Handling large databases, cloud storage, high-performance tasks

📡 4. NAS (Network Attached Storage) HDD

- Use: Storage shared across multiple devices in a network

- Size: Typically 3.5 inches

- Features: Optimized for continuous use, built for RAID environments

- Example Use: Small business backups, home media servers

🎥 5. Surveillance HDD

- Use: Security camera systems

- Size: Often 3.5 inches

- Features: Can handle constant writing from video feeds, works non-stop

- Example Use: Recording footage from multiple cameras over time

**If your PC is Running Slow**

| ⚠️ Problem                  | 🛠️ Fix                                                |
|----------------------------|--------------------------------------------------------|
| Too many startup programs  | Disable from Task Manager → Startup tab               |
| Background processes       | End unnecessary tasks via Task Manager                |
| Low disk space             | Uninstall unused apps, clean up temporary files       |
| Outdated software/drivers | Update Windows and drivers regularly                  |
| Malware or viruses         | Run a full system antivirus scan                      |
| Fragmented hard drive      | Use Defragment tool (for HDDs only)                   |
| Overheating                | Clean fans, improve airflow                          |
| Old hardware               | Upgrade to SSD or add more RAM                        |

# **Printer Issues and Solutions**
| ⚠️ Issue                          | 🛠️ Solution                                                                 |
|----------------------------------|------------------------------------------------------------------------------|
| Paper jams                       | Remove jammed paper carefully; check alignment and avoid overfilling tray   |
| Slow printing                    | Lower print quality settings; update drivers; clear print queue             |
| Faded or missing colors          | Replace ink/toner; clean print heads; use correct paper type                |
| Printer offline                  | Check network connection; restart printer; set as default printer           |
| Print jobs sent to wrong printer | Set correct default printer in system settings                              |

# BSOD
BSOD stands for Blue Screen of Death

🧠 What It Means:

- It's a stop error that appears when Windows encounters a critical system failure.

- The system crashes and shows a blue screen with an error code.

⚠️ Common Causes:

- Faulty hardware: Bad RAM, overheating, failing hard drives

- Driver issues: Outdated or incompatible drivers

- Corrupted system files: Often from failed updates or malware

- Software conflicts: Especially with low-level system software

- Malware: Can mess with system stability

# **BIOS/UEFI Settings and POST Errors**

🧩 Term                     | 📘 Meaning                                                             |
|----------------------------|------------------------------------------------------------------------|
| BIOS                       | Basic Input/Output System; firmware that initializes hardware at boot  |
| UEFI                       | Unified Extensible Firmware Interface; modern replacement for BIOS     |

**BIOS Settings**

| BIOS Setting             | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| Boot Order               | Determines the sequence of devices the system checks to boot the OS        |
| Secure Boot              | Ensures only trusted OS/software boots, improving security                 |
| SATA Mode                | Configures hard drive interface: AHCI, IDE, or RAID                        |
| CPU Virtualization       | Enables virtualization support for running virtual machines                |
| XMP (Extreme Memory Profile) | Loads pre-defined RAM overclocking profiles                      |
| Fan Control              | Allows customization of fan speeds based on temperature                    |


 **What is POST?**

POST stands for Power-On Self-Test.It checks hardware before booting OS.

**Common POST Errors**

| POST Error Code | Meaning                                | Possible Cause                          | Suggested Fix                          |
|-----------------|----------------------------------------|-----------------------------------------|----------------------------------------|
| 1 beep          | Memory refresh failure                 | Faulty RAM or motherboard               | Reseat or replace RAM                  |
| 2 beeps         | Parity circuit failure                 | RAM issue                               | Replace RAM                            |
| 3 beeps         | Base 64K memory failure                | First 64KB of RAM is bad                | Replace RAM                            |
| 4 beeps         | System timer failure                   | Motherboard timer not working           | Replace motherboard                    |
| 5 beeps         | Processor error                        | CPU not functioning                     | Reseat or replace CPU                  |
| 6 beeps         | Keyboard controller failure            | Keyboard or controller issue            | Check keyboard connection or replace   |
| 7 beeps         | Virtual mode exception error           | CPU or motherboard issue                | Replace CPU or motherboard             |
| 8 beeps         | Display memory error                   | Graphics card issue                     | Reseat or replace graphics card        |
| 9 beeps         | ROM BIOS checksum failure              | BIOS corruption                         | Reflash or replace BIOS chip           |
| 10 beeps        | CMOS shutdown register read/write fail | CMOS battery or motherboard issue       | Replace CMOS battery or motherboard    |

**Accessing and Resetting BIOS**

| Task                | Step-by-Step Instructions                                                       | Notes                                     |
|---------------------|----------------------------------------------------------------------------------|-------------------------------------------|
| Accessing BIOS       | 1. Restart or turn on your PC                                                   |                                            |
|                      | 2. Immediately press the BIOS key (usually `DEL`, `F2`, `ESC`, or `F10`)        | Key varies by motherboard brand           |
|                      | 3. Wait for BIOS/UEFI setup interface to load                                   | Use a wired keyboard if USB isn't working |
| Resetting BIOS       | 1. Access the BIOS using the steps above                                        |                                            |
|                      | 2. Navigate to the "Exit" or "Save & Exit" tab                                  | This tab usually contains reset options   |
|                      | 3. Select "Load Setup Defaults" or "Reset to Default Settings"                  | Confirms restoring factory settings        |
|                      | 4. Save changes and exit BIOS (`F10`)                                           | PC will reboot with default settings      |


# DAY-6 (System Recovery, Backup & Network Tools)

**Safe Mode**

Safe Mode is a diagnostic startup mode in operating systems like Windows, macOS, and Android that loads only the essential system files and drivers. It’s designed to help you troubleshoot issues when your device isn’t functioning properly.

**🛠️ Key Features of Safe Mode:**

- Loads minimal drivers (no fancy graphics, sound, or network unless you choose Safe Mode with Networking)
- Disables third-party apps and startup programs
- Helps isolate issues caused by faulty drivers, software, or malware
- Often used to uninstall problematic updates or drivers
  
**💡 Types of Safe Mode:**

| Mode                      | Description                                                                 |
|---------------------------|-----------------------------------------------------------------------------| 
| Safe Mode                 | Basic troubleshooting with minimal drivers and no internet                  |
| Safe Mode with Networking | Adds network drivers so you can access the internet                        |
| Safe Mode with Command Prompt | Opens a command-line interface for advanced troubleshooting         |

**Recovery Tools in Windows**

 Recovery tools help you troubleshoot, repair, and restore your system to a stable state without needing a complete reinstall.

 | Recovery Tool               | Purpose                                                                 | How to Access                                      |
|----------------------------|-------------------------------------------------------------------------|----------------------------------------------------|
| System Restore             | Reverts system files and settings to a previous state                  | Control Panel > Recovery > Open System Restore     |
| Reset This PC              | Reinstalls Windows (with or without keeping personal files)            | Settings > System > Recovery > Reset this PC       |
| Startup Repair             | Fixes boot issues preventing Windows from loading                      | WinRE > Troubleshoot > Advanced Options > Startup Repair |
| Recovery Drive             | Creates a bootable USB drive for system recovery                       | Control Panel > Recovery > Create Recovery Drive   |

**Operating System Repair**

| Repair Method                  | Description                                                                 | How to Use                                                   |
|-------------------------------|-----------------------------------------------------------------------------|--------------------------------------------------------------|
| System File Checker (SFC)     | Scans and repairs corrupted system files                                   | Run `sfc /scannow` in Command Prompt (Admin)                |
| Deployment Imaging (DISM)     | Repairs Windows image and component store                                  | Run `DISM /Online /Cleanup-Image /RestoreHealth`            |
| Startup Repair                | Fixes boot issues preventing Windows from loading                          | Access via WinRE > Troubleshoot > Advanced Options          |
| System Restore                | Reverts system to a previous working state                                  | Control Panel > Recovery > Open System Restore              |
| Reset This PC                 | Reinstalls Windows (option to keep or remove personal files)                | Settings > System > Recovery > Reset this PC                |
| Bootrec Commands              | Repairs boot records and configuration data                                | Use `bootrec /fixmbr`, `/fixboot`, `/rebuildbcd` in CMD     |
| Safe Mode                     | Loads minimal drivers for troubleshooting                                   | Access via Advanced Startup > Startup Settings              |
| Installation Media Repair     | Reinstalls or repairs Windows using bootable USB/DVD                        | Boot from media > Select "Repair your computer"             |

**Signs of Virus/Malware Infections**

| Slow system performance          |
| Frequent crashes or freezes      |
| Annoying pop-ups                 |
| Homepage or search engine changes|
| Unusual network activity         |
| Unknown apps or files            |
| Disabled antivirus or firewall   |
| Fake virus alerts                |

**Virus & Malware Removal Methods**

- Boot your system into Safe Mode to prevent malware from launching.
- Disconnect from the internet to block external communication by malicious software.
- Delete temporary files from system folders to remove hidden malware traces.
- Use System Restore to roll back your PC to a clean previous state.
- Run a full Antivirus Scan using Microsoft Defender or trusted third-party tools.

**Methods for Backing Up Windows**

- Windows Backup App – Backs up folders, apps, settings, and Wi-Fi info to OneDrive.
- File History – Automatically saves versions of personal files like Documents and Pictures.
- System Image Backup – Creates a full snapshot of your system, including OS and apps.
- System Restore Points – Saves system settings before major changes (not personal files).
- OneDrive Folder Sync – Syncs Desktop, Documents, and Pictures to the cloud manually.

**RJ45 Connector**

RJ45 is the standard connector used for Ethernet networking.

**RJ-45 Cable Making (T568B Standard):**

| Pin | Wire Color     | Use/Signal Description         |
|-----|----------------|-------------------------------|
| 1   | White-Orange   | Transmit + (TX1+)             |
| 2   | Orange         | Transmit – (TX1–)             |
| 3   | White-Green    | Receive + (RX+)               |
| 4   | Blue           | Bi-Directional Transmit +     |
| 5   | White-Blue     | Bi-Directional Transmit –     |
| 6   | Green          | Receive – (RX–)               |
| 7   | White-Brown    | Bi-Directional Transmit +     |
| 8   | Brown          | Bi-Directional Transmit –     |

**🔧 Steps to Make the Cable:**

- Strip the outer jacket of the Ethernet cable (about 1 inch).
- Untwist the wire pairs and straighten them.
- Arrange wires in the T568B order listed above.
- Trim the wires evenly so they’re about 0.5 inch long.
- Insert wires into the RJ45 connector, making sure each wire reaches the end.
- Crimp the connector using the crimping tool.
- Repeat the process for the other end of the cable (use same order for straight-through cable).


# DAY-7 (Networking Fundamentals)

**Hosts in a Network**

In networking, a host refers to any device connected to a network that can send or receive data. These devices play a central role in communication and resource sharing across the network.

**Network Definition**

A network is a system of interconnected devices or entities that communicate and share resources with each other.

**Key Features**

- Security
- Performance
- Data Sharing
- Backup & Recovery
- Hardware/Software Compatibility
- Connectivity

# **IP Address Basics**

An IP address (Internet Protocol address) is a unique identifier assigned to each device connected to a network that uses the Internet Protocol for communication.

**Types**

 Types of IP Addresses:
- Public IP: Used to identify devices on the internet
- Private IP: Used within local networks (e.g., home or office)

**Properties**

- Uniqueness: Each device on a network must have a unique IP address to avoid conflicts.
- Universal: Same structure used globally.

**IPv4 vs IPv6**

| Feature                  | IPv4                                  | IPv6                                      |
|--------------------------|----------------------------------------|-------------------------------------------|
| Address Length           | 32-bit                                 | 128-bit                                   |
| Address Format           | Decimal (e.g., 192.168.0.1)            | Hexadecimal (e.g., 2001:0db8::1)          |
| Total Addresses          | ~4.3 billion                           | ~340 undecillion (3.4×10³⁸)               |
| Address Classes          | Yes (A, B, C, D, E)                    | No classes                                |

**IP Address Representation**

🔢 Binary Notation: 
- Displays the IP address as 32 bits (for IPv4), grouped into four 8-bit segments.
- Example: 192.168.1.1 becomes
11000000.10101000.00000001.00000001

⚪ Dotted-Decimal Notation:
- The human-friendly format using four decimal numbers separated by dots.
- Each number ranges from 0 to 255, representing one byte (8 bits).
- Example: 192.168.1.1

**Classful Addressing (IPv4)**

🧠 What Is Classful Addressing?
Classful addressing divides the 32-bit IPv4 address space into five classes: A, B, C, D, and E. Each class has a specific range, default subnet mask, and intended use.

| Class | Starting Bits | IP Range                   | Default Subnet Mask | Intended Use                     |
|-------|----------------|----------------------------|----------------------|----------------------------------|
| A     | 0              | 0.0.0.0 – 127.255.255.255   | 255.0.0.0            | Very large networks (e.g., ISPs) |
| B     | 10             | 128.0.0.0 – 191.255.255.255 | 255.255.0.0          | Medium-sized networks            |
| C     | 110            | 192.0.0.0 – 223.255.255.255 | 255.255.255.0        | Small networks (e.g., LANs)      |
| D     | 1110           | 224.0.0.0 – 239.255.255.255 | N/A                  | Multicasting                     |
| E     | 1111           | 240.0.0.0 – 255.255.255.255 | N/A                  | Reserved for future use          |

**Subnet Mask**

A subnet mask is a 32-bit number used in IPv4 networking to divide an IP address into two parts: the network portion and the host portion.

**MAC Address**

A MAC address (Media Access Control address) is a unique identifier assigned to a device’s network interface card (NIC) for communication at the data link layer of the OSI model.

**DNS-Domain Name System**

The Domain Name System (DNS) is like the internet’s phone book — it translates human-friendly website names (like www.google.com) into machine-friendly IP addresses (like 142.250.182.4).

**Default Gateway**

A default gateway is the device (usually a router) that acts as the exit point from your local network to other networks — like the internet.

**CIDR-Classless Inter-Domain Routing**

🧠 What CIDR Does:
- Allows flexible IP address allocation using variable-length subnet masks (VLSM)
- Reduces waste of IP addresses by assigning only what’s needed
- Enables route aggregation (supernetting), which simplifies routing tables
- Supports both IPv4 and IPv6 addressing

**Types of Network Cables**

- Coaxial Cable – Used for cable TV, CCTV, and legacy Ethernet connections.
- Twisted Pair Cable (UTP/STP) – Commonly used in LANs for Ethernet and telephone wiring.
- Fiber Optic Cable – Ideal for high-speed, long-distance data transmission with minimal interference.

**Numerical:**

*Given: 205.150.65.0/26

1. Subnet Mask:
   26 bits → 255.255.255.192

2. Subnets Possible:
   /26 from Class C (/24) → 2 bits → 2² = 4

3. Hosts per Subnet:
   32-26=6 bits → 2⁷-2=62
   
4. Network IP:
   First Subnet starts at → 205.150.65.0

5. Broadcast IP:
   First Subnet ends at → 205.150.65.63        





    




