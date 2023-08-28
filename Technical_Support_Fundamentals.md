This is a collection of my brief notes from *Google IT Support* courses on [Coursera](https://www.coursera.org/professional-certificates/google-it-support).

1. Technical Support Fundamentals ([Coursera](https://www.coursera.org/learn/technical-support-fundamentals?specialization=google-it-support))
2. The Bits and Bytes of Computer Networking ([Coursera](https://www.coursera.org/learn/computer-networking?specialization=google-it-support))
3. Operating Systems and You: Becoming a Power User ([Coursera](https://www.coursera.org/learn/os-power-user?specialization=google-it-support))
4. System Administration and IT Infrastructure Services ([Coursera](https://www.coursera.org/learn/system-administration-it-infrastructure-services?specialization=google-it-support); not finished)
5. IT Security: Defense Against the Digital Dark Arts ([Coursera](https://www.coursera.org/learn/it-security?specialization=google-it-support); not finished)



## Content

[Introduction to IT Support](#introduction-to-it-support)

[Hardware](#hardware)

[Operating systemt](#operating-system)

[Networking](#networking)

[Software](#software)

[Troubleshooting](#troubleshooting)

[Content](#content)

[Courses list](README.md#contents)



 

### Introduction to IT Support

#### What is IT?
- **IT** is "the use of digital technology, like computers and the Internet, to store and process data into useful information."

- The IT industry refers to the entire scope all jobs and resources related to computing technologies in society. From network engineers, to hardware tech, to desktop support personnel.

- The heart and soul of IT support is helping people.

- IT helps people solve meaningful problems by using technology.

- IT skills have become necessary for day-to-day living.

- The Digital Divide refers to the digital literacy skill gap.
  

#### What does an IT Support Specialist do?

- There's really no such thing as "day-to-day work."

- Managing, installing, maintaining, troubleshooting, and configuring office and computing equipment.

- "Failure as a feedback" to be better-equipped to tackle those problems next time around.


#### What is a computer?
A **computer** is a device that stores and processes data by performing calculations.

#### QWERTY layout
- [How QWERTY conquered keyboards](https://www.youtube.com/watch?v=c8f6us-Sjlo)

#### What is an algorithm?
An **algorithm** is a series of steps that solve specific problems.


#### What is cryptography?
**Cryptography** is the art of writing and solving codes. It evolved into a modern science in World War 2.



#### What does "open source" software mean?
**Open source** means anyone could modify and share it.


#### Computer Language
*What a computer calculates, and how.*

#### What is binary?
**Binary system** is the communication that a computer uses (also known as a base-2 numeral system).

- We group binary into 8 numbers, or **bits** (Technically, a **bit** is a binary digit.)
  - A group of 8 bits is referred to as a **byte**.

- 256 possible values
  - 255 possible *decimal* values (0-255)

- [Binary-to-text converter](https://www.rapidtables.com/convert/number/binary-to-ascii.html)

- [A great game to practice learning binary](https://games.penjee.com/binary-numbers-game/)

#### Character Encoding
- **Character Encoding** Assigns our binary values to characters, so that we as humans can read them.

- [ASCII](https://en.wikipedia.org/wiki/ASCII) was the breakthrough standard, early on.
  - Bonus: [ASCII Art](https://en.wikipedia.org/wiki/ASCII_art)

- [UTF-8](https://en.wikipedia.org/wiki/UTF-8) replaced ASCII because it can store a character in more than one byte.

- The unicode standard helps us represent character encoding in a consistent manner.

- RGB model


#### Binary

- The key concept behind binary is "on and off."

- Computer punch card holes represent the number 1

- Transistors voltage =1, low voltage =0


- [Wonderopolis: How Does the Binary System Work?](https://wonderopolis.org/wonder/how-does-the-binary-system-work)
- [BBC: Introducing Binary](https://www.bbc.co.uk/bitesize/guides/zwsbwmn/revision/1)
- [How to Geek: What is Binary, and Why Do Computers Use It?](https://www.howtogeek.com/367621/what-is-binary-and-why-do-computers-use-it/)

#### What are logic gates?
**Logic gates** allow our transistors to do more complex tasks, like decide where to send electrical signals depending on logical conditions.


#### PC

##### What is abstraction?
**Abstraction** is to take a relatively complex system and simplify it for our use.

##### Computer Architecture Overview

##### The 4 Layers of Computers
1. Hardware
  - The **hardware layer** is made up of the physical components of a computer
2. Operating System
  - The **operating system** allows hardware to communicate with the system.
3. Software
  - The **software layer** is how we as humans interact with our computers.
4. Users
  - The **user** interacts with the computer; and can operate, maintain, and even program the computer.


[Content](#content)

----------------------------------------------------------------------------


### Hardware


#### What are ports?
**Ports** are connection points that we can connect devices to that extend the functionality of our computer.

#### What is a CPU?
- The **CPU (Central Processing Unit)** is the brain of our computer, it does all the calculations and data processing.

- **RAM (Random Access Memory)** is our computer's short-term memory.

- **Hard drive** holds all of our data, which includes all of our music, pictures, and applications.

- **Motherboard** is the body or circulatory system of the computer that connects all the pieces together. 

- **Power supply** converts electricity from the wall outlet into a format the computer can use.



#### What is a program?
- **Programs** are instructions that tell the computer what to do.

- **External Data Bus** is an internal network of wires, which send voltage to wires to represent on (1) or off (0)

- **Registers** store the data the CPU works with.

- **Memory Controller Chip (MCC)** is a bridge between the CPU and the RAM, like a nerve in your brain controlling thoughts or memories.

- **Address Bus** connects the CPU to the MCC, and sends the *location* of the data, but not the data itself. Then, the MCC looks for the data in the hard drive, then sends it to the CPU via the EDB. 

- **Cache** is smaller than RAM, but can store more frequently-used data in a way that's easier and faster to use. 

- **Clock wire** lets the CPU know it can start doing calculations. This is triggered by voltage sent to the clock wire, and is referred to as a *clock cycle*.

- **Clock speed** is the maximum number of clock cycles that the computer can handle in a certain time period (measured in Hz).

- **Overclocking** increases the rate of a CPU's clock cycles to increase performance. This technique has advantages and disadvantages.



#### CPU

- The most important part of the computer.

- **Instruction set** is a list of instructions the CPU can run (hard-coded, differing by manufacturer, not unlike a car engine).

- You need to make sure a CPU is compatible with a motherboard. Make sure the CPU and motherboards' sockets and pins match.
  - LGA and PGA sockets

- A **heat sink** pulls heat from the CPU and dissipates it with a fan or other medium.

#### RAM

- Computer's short-term memory.

- The data is volatile--once you power off your machine, the data stored in RAM is cleared.

- RAM defined by the amount of data it can process at once (for example, 16 GB worth of programs).

- The most common type of RAM is DRAM, or **dynamic random-access memory**.
  - Other types of memory sticks using DRAM chips include **dual inline memory module (DIMM)** sticks, which feature different pin sizes.
  - **Synchronous DRAM (SDRAM)** synchronizes to the computer's clock speed, which lets it process data faster.
  - **Double data rate SDRAM (DDR SDRAM/DDR)** is faster and more efficient than previous versions.
    - DDR 4 is currently the fastest type of short-term memory for your computer.

#### Motherboards

- Can expand computer functionality through expansion cards, routes power from the power supply, and allows parts of the computer to communicate with each other.

- **Chipset** decides how components talk to each other in the computer.
  - **Northbridge** connects RAM and video cards
  - **Southbridge** maintains I/O (input/output) controllers, like hard drives and USB devices that input and output data.

- The chipset allows you to manage data between the CPU, RAM, and peripherals.

- **Peripherals** are external devices we connect to our computer, like a mouse, keyboard, and monitor.

- **Expansion slots** give us the ability to increase the functionality of a computer.

- The standard for expansion bus today is the **Peripheral Component Interconnect (PCI) Express**.

- The most common form factor for motherboards is **Advanced Technology eXtended (ATX**
  - **Information Technology eXtended* is a smaller version (mini, nano, pico varieties exist).

#### Storage

- HDD and SSD
  - RPM

#### ATA Drives
- [Supplemental reading](https://www.techwalla.com/articles/difference-between-ata-and-sata-hard-drives)

- SATA is the most common

- NVM Express (or NVMe)
  - [Cisco: NVMe for Absolute Beginners](https://blogs.cisco.com/datacenter/nvme-for-absolute-beginners)
  - [Supplemental reading](https://searchstorage.techtarget.com/definition/NVMe-non-volatile-memory-express)

- "Hot-swappable"

#### Power Supplies

- Computers use AC voltage, and **power supplies** converts AC from the wall to low-voltage DC power to use in the computer.

- **Amperage** measured in amps; amps pull electricity as needed, whereas voltage pushes all electricity.

- **Wattage** is the amount of volts and amps that a device needs.

- You can power most basic desktops with a 500W power supply.

- It's better to err on the side of larger power supplies.

- Knowing how to diagnose power issues is a critical skill for IT support specialists.

#### Mobile Devices

- Mobile devices are computers too, featuring CPUs, RAM, storage, power systems, and peripherals.
  - The difference is they're portable and powered by batteries.

- Mobile devices' components are usually integrated, and not interchangeable.
  - **System on a Chip (SoC)** packs the CPU, RAM, and sometimes even the storage onto a single chip. 
    - Used by very small mobile devices.
    - Advantage is small size and less battery power use.

- Mobile devices can use peripherals and can *be* peripherals.

- Mobile devices can use standard or proprietary ports/connectors, requiring specific adapters or connectors.

#### Standard power, data, display, and connector types 
 - USB-C
 - Lightning adapter
 - Mini USB
 - Micro USB
 - Micro HDMI
 - Mini HDMI
 - Mini display port 

- IT professionals may be called upon to help users with mobile devices, including:
  - Setup
  - Troubleshooting
  - Repairs
  - Replacement

#### Batteries and Charging Systems

- Mobile devices use rechargeable batteries.
  - May use a external charger, cradle, stand, or wireless charger.

- Rechargeable batteries have a limited lifespan, measured in **charge cycles**. 
  - A **charge cycle** is one full charge and discharge of a battery.

- Charging circuit manages the power transfer from external power source to rechargeable battery, similar to a power supply unit (PSU), in regards to input power compared to output power.

- Mismatching chargers to devices can damage the battery, device, and the charger.

- Batteries should be charged or discharged in their **safe operating temperature** range. 
    - Otherwise they risk swelling, rupturing, or catching on fire.

- Always ensure the charger, battery, and device are all designed to work with each other.

#### Peripherals

- **Peripherals** Anything that you connect to your computer externally that adds functionality.

- **USB** stands for **Universal Serial Bus** and is the most popular connection type.
  - You'll most commonly run into:
    - USB 2.0 (transfer speeds of 480 Mb/s)
    - USB 3.0 (transfer speeds of 5 Gb/s)
    - USB 3.1 (transfer speeds of 10 Gb/s)

#### Don't mistake transfer speeds
- Mb != MB
  - MB is **megabyte**, or **unit of data storage**
  - Mb/s is a **megabit per second**, which is a **unit of data transfer rate**.
    - Example: To transfer a 1MB file in a second, you'll need an 8 Mb/s connection speed (because there are **8 bits** in **1 byte**)
    - Just use simple multiplication. :)

#### USB ports

- USB ports are backwards-compatible
- USB A can charge devices

- In general:
  - USB 2.0 (black)
  - USB 3.0 (blue)
  - USB 3.1 (teal)

- Most recent is **Type-C connector**, becoming a universal standard for display and data transfer, and intended to replace many peripheral connection types.

- Other input standards include:
  - **DVI** and **VGA**, which only output video
  - **HDMI** a standard in televisions and computers, outputting both audio and video
  - **DisplayPort** also outputs audio and video
  - **USB Type C** can handle data transfer and power, on top of audio and video.

#### Useful links for connecting displays
 - [Windows](https://support.microsoft.com/help/27911/windows-10-connect-to-a-projector-or-pc)
 - [MacOS](https://support.apple.com/guide/mac-help/mchl5fdd37ce/mac)
 - [Ubuntu](https://help.ubuntu.com/stable/ubuntu-help/display-dual-monitors.html) 



#### BIOS

 - **Drivers** (AKA *services*) contain instructions the CPU needs to understand external devices.

 - The CPU doesn't know there are devices it can talk to, so it connects to something called the BIOS.

 - The **Basic Input/Output Services (BIOS)** helps initialize the hardware in the computer, and gets the operating system up and running.
   - The BIOS is not stored on the hard drive;
     - Instead, the BIOS is stored on the motherboard, in a special **read-only memory chip (ROM chip)**
     - ROM is not volatile like RAM, and doesn't clear when the computer is turned off
  - When the operating system loads, the BIOS loads drivers from non-essential devices directly from the hard drive.

 - The **UEFI (Unified Extensible Firmware Interface)** performs the same function as BIOS; but is a modernized and superior format. 
  - Most modern computers come with UEFI, and will become the BIOS standard.

 - Computers run a **power-on self test (POST)** to figure out which hardware is on the computer, happening before the BIOS initializes anything.
   - Since the screen is not active, the computer usually communicates via a beep.

- The **CMOS battery** stores basic data about booting the computer (like date, time, and how to start up)
  - You can alter these in the CMOS or BIOS settings menu.

- **Reimaging** involves wiping and reinstalling an operating system, and is a common IT task. This process involves navigating the computer's BIOS.

#### Putting It All Together

 - **Electrostatic discharge** (AKA, *static electricity*) is a major hazard to computer components.
   - You should always ground yourself before working on physical components of a computer.

 - Keep computer components in anti-static bags until you need to access them for your computer.

 - **Standoffs** are used to raise and attach your motherboard to the case.

 - CPUs have a marker that has to align with the CPU socket on the motherboard.
   - Again: Make sure your CPU is compatible with your motherboard.

 - Before you attach the heat sink, apply thermal paste to the CPU.

 - Align your RAM/DIMM sticks as good practice (it protects your pins from damage)
   - (Read your motherboard's manual to learn about its RAM slots.)

 - Create a wind tunnel that takes in air, blows it over the components, then pushes it all out back.

 - Keep cables off to the side, so as not to damage the motherboard.

#### Mobile Device Repair

 - Always refer to the **return merchandise authorization (RMAO** policy before you do anything.

 - **Factory reset** Removes all data, apps, and customizations from the device.

 - When working on mobile devices, follow the same safeguards as you would with a computer:
   - Protect against static discharge;
   - Use the proper tools;
   - Keep parts organized and labeled;
   - Take pictures along the way;
   - Follow vendor documentation;
   - Test the device to ensure it works


[Content](#content)
-----------------------------------------------------------------------------------------OS-------------------------------------------------------------------

### Operating system

#### Remote Connection and SSH

- **Remote connection** allows us to manage multiple machines from anywhere in the world.

- **Secure shell (SSH)** is a protocol implemented by other programs to securely access one computer from another.
  - To use SSH, you need:
    - An SSH client installed on the computer you're connecting *from*, and;
    - An SSH server on the computer you're trying to connect *to*.

- An SSH server isn't a physical machine.
  - It's a program that runs as a background process, constantly checking if a client is trying to connect with it. 
  - It then authenticates the request.

- The most popular SSH client on Linux is the **OpenSSH Program**.

- A popular form of SSH for Windows is **PuTTY**.

- To log into a remote machine, you need to have an account on that computer.

- You also need the host name/IP address for that computer.

- You can connect through SSH using a password; but that's not the most secure method.

- Alternatively, you can use an **SSH authentication key**.
  - SSH keys come in a set of two keys: *private* and *public*
  - You can lock something with a public key; but you can only unlock it with a private key, and vice-versa. 
  - [Read more about SSH authentication keys]()

- Another method of secure remote connection is a **VPN**.
  - **Virtual private network (VPN):** Allows you to connect to a private network (like your work network) over the Internet.


#### Remote Connections on Windows

- **PuTTY** is a free, open source software that you can use to make remote connections through several network protocols, including SSH.

- In PuTTY configuration, make note of the *host name, port,* and *connection type* options.
  - By default, the port is set to `22`, which is the default port the SSH protocol uses.

- PuTTY also comes with a tool called **Plink (PuTTY Link)**, which is implemented into the command line after PuTTY is installed (and used to make SSH connections).

- Microsoft provides another way to connect to other Windows computers with **Remote Desktop Protocol (RDP)** 
  = RDP clients are also available for Linux and Mac.
  - RDP provides a GUI.

- **Microsoft Terminal Services Client (MSTSC)** is used to create RDP connections to remote computers.


#### Components of an Operating System

- **Operating system:** The whole package that manages our computer's resources and lets us interact with it.

- There are two main parts to an operating system: the **kernel** and the **user space**.
  - The **kernel** is the main core of an operating system: 
    - Directly communicates with the hardware;
    - Manages the system's resources;
    - Handles file storage and management.
  - And the **user space** is everything outside of the kernel (system programs, user interfaces, etc).

- The term *operating system* refers to both the kernel and user space.

#### The major operating systems dealt with in IT
- Windows (also commonly known as "PC")
- MacOS
- Linux
  - Ubuntu
  - Debian
  - Red Hat

- **Process management** is a kernel process that allows the computer to multitask at a rate faster than we can blink.

- The kernel optimizes *memory usage* and makes sure our applications have enough memory to run.

- **Input/Output (I/O) Management** is anything that can give us input, or that we can use for output of data.
  - It's how the kernel talks to external devices like discs, keyboards, audio devices, etc.
  - Clicking with your mouse is an example of this.

- In summary, main kernel operations are:
  - File management
  - Process management
  - Memory management
  - I/O management


#### Files and File Systems

- There are 3 main components to handling files on an operating system
  1. File data
  2. Metadata
  3. File system

#### File system
- A brand new hard disk needs to be edited, so the OS needs to know what type of file system is used

- *NTFS* is the file system used by Windows, and is an evolution of the system introduced in Windows NT
  - NTFS features include encryption, faster access speeds, and superior security.
  - Windows is currently developing another file system called **ReFS (Refined File System)** but isn't ready for consumer use yet.

- **APFS** is the default file system for MacOS, as of March 2017.
  - Previously was HFS+. It's *journaled*, which means it does a better job saving your disk state in case of failure.

- Different Linux distributions use different file systems; but a standard for Linux is **ext4** (the fourth iteration of ext file systems, and backwards-compatible).

- A good rule of thumb is to stick with the file system that your operating system recommends.

#### Data
- We write data to our hard drive in the form of *data blocks*.
  - This mean data saved can be broken down into different pieces and written to different parts of the disk, instead of in one solid piece.

- **Block storage** improves faster handling of data because the data isn't stored as one long piece and can be accessed quicker. 
  - It also helps manage storage space.

- **Metadata** tells us everything we need to know about a file.
  - File owner
  - Permissions
  - File size
  - Date modified
  - Date created
  - File type (extension)

- **File extension** is the appended part of a filename that tells us what type of file it is in certain operating systems.

- A working knowledge of file systems (and the differences between them) can help you do things like recover data from damaged disks; or explore ways to boot from two different kinds of operating systems (like Windows or Linux) on the same computer.


#### Process Management

- One of the most important kernel tasks is *process management*.

- **Process:** A program that's executing, like our internet browser or text editor.

- **Program:** An application that we can run, like Chrome.
  - When a program wants to run, a process has to be created for it.
  - This process requires hardware resources, like RAM and CPU.

- The kernel manages computer's resources effectively and efficiently. But technically, it doesn't handle everything *all at once*.
  - Instead, it executes processes one by one, through a method called a *time slice*.

- **Time slice:** A very short interval of time that gets allocated to a process for CPU execution.
  - So short you can't notice it. As in milliseconds.

- **Kernel:** Creates processes, efficiently schedules them, and manages how processes are terminated.
[Q: what does the kernel do?]

#### Memory Management

- Memory is less plentiful than hard disk drive, so *virtual memory* is a way to generate more memory than the computer physically has.

- **Virtual Memory** is the combination of hard drive space and RAM that acts like memory that our processes can use.

[Pages stored in virtual memory]

- *"When we execute a process, we take the data of the program in chunks we call pages. We store these pages in virtual memory. If we want to read and execute these pages, they have to be sent to physical memory or RAM."*
  - Virtual memory stores pages that are currently not in use by physical memory.

- When virtual memory is stored on the hard drive, the allocated space is called *swap space*.

#### I/O Management

- **I/O devices** are devices that perform input and output.
  - Includes monitors, speakers, mouse/keyboard, webcams, and hard disk drives.

- The kernel needs to be able to load drivers, so the computer can recognize and communicate with different types of hardware.

- The kernel also handles the transfer of data in and out of the devices.

- Devices also need to be able to talk to each other (like a webcam and microphone)

- The kernel handles all intercommunication between devices.

- *When you're troubleshooting or solving a problem with a slow machine, it's usually some sort of hardware resource deficiency.*
  - If you don't have enough RAM, you can't load up as many processes.
  - If you don't have enough CPU, you can't execute programs fast enough.
  - If you have too much input coming into the device--or too much output going somewhere--other data will be blocked from being sent or received.

- *"It's slow!"* Is one of the most common problems you'll solve as in an IT support role.

#### Interacting with the OS: User Space

- There are two ways users can interact with the OS:
  1. Shell
  2. Graphical user interface (GUI)

- **Shell:** A program that interprets text commands and sends them to the OS to execute.

- A **GUI** is a visual way to interact with a computer, and implements much abstraction. 

- Some shells use a GUI, but IT professionals need to be familiar with the **command line interface (CLI) shell**.

- The most common shell is **BASH (Born Again Shell)**
  - The Windows shell is **Powershell**

#### Logs

- **Logs** are files that record system events on our computer, just like a system's diary.

- Logs are kept so we can refer to them, when we need to find out something that happened.

#### The Boot Process

- When you start up a computer, you use the term **boot**.

- **Booting** means to start from nothing, and follow a series of steps to arrive at a fully-operational system.

- A rundown of the boot process:
  1. The computer is powered on
  2. The BIOS/UEFI runs the **POST** to ensure the computer is in proper working order.
  3. A boot device is selected (hard drives, USB drives, or CD drives)
    - The computer then searches for a bootloader. 
  4. After a quick series of programs, the computer then loads the operating system.
  5. After the bootloader loads the operating system, the kernel gets loaded.
  6. The kernel allocates the computer's resources, loads drivers, and transfers data from hardware to software.
  7. Essential system processes and user space items are launched
    - Processes such as user login, desktop environments, etc.

- **BIOS/UEFI:** A low-level software that initializes our computer's hardware to make sure everything is good to go.

- **Bootloader:** A small program that loads the operating system.

#### Mobile Operating Systems

- Mobile operating systems are optimized to use as little power as possible, by removing OS features that the device doesn't need.

- Mobile user interfaces (such as touch and voice) require adding device drivers and support to the mobile operating system.




#### Choosing an Operating System

The operating systems in use by an organization have a lot to do with the applications and systems that they need to run.

- When choosing an operating system, ask:
  - Are you working with an organization or service that requires the use of a specific operating system?
  - What software will need to be run on this device?

  - What hardware will be used?

- Choose the operating system that matches your CPU
  - For example, a 64-bit operating system for a 64-bit processor.

- You can use different media for installing operating system (like disk or USB)
  - As an IT Support Specialist, you'll install an operating system many times, so using one single disk won't be time efficient or scalable. 

#### Virtual Machines

- **Virtual machine (VM):** Just a copy of a real machine.

#### Installing Windows

- Pretty straightforward.

#### Installing Linux

- A host name should follow a certain standardization.
  - Username-Location (ex: cindy-nyc)

#### What is Chrome OS?

- *Unlike other operating systems, Chrome OS has one main purpose: To be a secure and simple way for the user to interact with the web.*

The power of the web browser, and advancement in web browser applications, have legitimized an operating system centered around running a web browser. 

- Today, you can do many things through just a web browser:
  - Communicate through email
  - Create and share documents
  - Edit photos
  - Connect remotely to another computer

- Chrome can also run Android and Linux applications inside containers.

- Chrome's UI is set up so you only see the Chrome web browser's interface; but process management, memory, and input/output are still happening behind the scenes.

- When you log into a Chrome OS machine, you're also signing into the Chrome browser.

- *Chrome OS machines are interchangeable because most data is stored in the cloud, not locally.*

- Chrome users **don't** have administrator rights, and the OS has an auto-update feature. In other words, there's no meddling required by users.
  - The auto-update also includes a failsafe, in case things go wrong.
  - *This means that the user doesn't need to worry about problems or hacks in the system because it's designed to stay up and running.*
  - As a result, Chrome has powerful security.

[Content](#content)
-----------------------------------------------------------------------------------------------------Network----------------------------------------------------

### Networking

#### Basics of Networking

*"The Internet is just an interconnection of computers around the world, like a giant spider web that brings all of us together."*

- We call the interconnection of computers a **network**.

The Internet is *not* the World Wide Web.

- **The Internet** is the physical connection of computers and wires around the world.

- **The Web** is the information on the Internet.

**Networking** in the IT field is managing, building, and designing networks.

- You don't connect to the Internet directly; instead, computers called *servers* connect directly to the Internet.
  - These machines serve content like websites, hence the name.
  - **Clients** request the content from servers. 
  - Clients don't connect directly to the Internet; they connect to an **internet server provider (ISP)**.

- Computers on a network have an identifier called an **IP address**.

- Devices that can connect to a network have another unique identifier called a MAC address.
  - ***Media access control (MAC) addresses** are generally permanent and hard-coded onto a device.*

- When you send or receive data through a network, you need to have both an *IP* and a **MAC** address.

- An analogy is the addresses on a letter:
  - The IP address is your home address;
  - The MAC address is the name of the recipient (making sure it gets to the right location and right person)

- Data sent through a network is sent through a network is sent through **packets**
  - Little bits of data, in 1s and 0s.
  - When a packet gets to its destination, it will rearrange itself back in order.


#### Networking Hardware

- **Ethernet cable** lets you physically connect to the network through a cable.

- **Wi-Fi** is wireless networking.

- **Fiber-optic cables** allow greater speeds than all other methods. Named for its glass fibers that transfer 1s and 0s through light, not electrical current.

Computers connect to a few different devices that help organize our network together:
- **Router:** Connects lots of different devices together and helps route network traffic (through *network protocols*).
- **Switches** are like mailrooms in a building.
  - Routers get our letters to the building; 
  - But once we're inside, we use the mailroom to figure out where to send a letter.
- **Hubs** are like company memos.
  - They don't know who to send the memo to, so they send it to everyone.

- **Network stack:** A set of hardware or software that provides the infrastructure for a computer.
  - It is all the components that makes up computer networking.

*"You might need to investigate the networks stack and your job. You'd start with making sure the end user computers are working properly. Then you'd turn your attention to other possible points of failure like the cabling, switches and routers, that work together to access the Internet."*


#### Language of the Internet

- Network protocols have rules that ensure your data packets:
  - Are routed efficiently;
  - Aren't corrupted;
  - Are secure;
  - Go to the right machine;
  - Are named appropriately.

**TCP/IP** have become the predominant protocols of the Internet.

- The **Internet Protocol (IP)** is responsible for delivering packets to the right computers.
  - The IP helps us route information, through the use of IP addresses.

- The **Transmission Control Protocol (TCP)** is responsible for delivering information from one network to another. 


#### The Web

- **Websites** are basically text documents formatted with *HTML*.

- **Hypertext Markup Language (HTML)** is a coding language used by web browsers.

- **Uniform Resource Locator (URL)** is a web address, similar to a home address.

- The part after `www.` in a web address is called the **domain name**.
  - Once a domain name is registered with the Internet Corporation for Assigned Names and Numbers (ICANN), no one else can take that name unless it becomes available again.

- **Domain name system (DNS)** acts like the Internet's directory, using human-readable words to map to an IP address.
  -*"Every time you go on a website, your computer is performing a DNS lookup to find the IP address of the website name you typed in."*

- The source of Internet requests are usually identified by IP addresses and server logs. 


#### Limitations of the Internet

#### History of the Internet

- The United States initiated the DARPA project in the 1960s
  - This would create the ARPANET, the earliest version of the Internet
  - Programmers could now remotely access a computer; but networks still couldn't talk to each other.
- In the 1970s, computer scientists Vinton Cerf and Bob Kahn created the TCP/IP.
  - *The TCP/IP protocol is what allowed computers to share information outside their network, which stemmed the creation of the Internet as we know it today.*
  - Over the next 50 years, TCP/IP would grow as the standard, and it remains so today.
  - But the data sent was just text, and not centralized.
- The 1990s, Tim Berners-Lee creates the World Wide Web, which used different protocols for displaying information in webpages.

#### Limitations of the Internet

- Finite IP addresses

- The current protocol of IP, **Internet Protocol version 4 (IPv4)** is an address that made up of 32 bits separated into 4 groups (four bytes).
  - Remember that 1 byte can store up to 256 values (0 - 255).
  - Thus, an example of an IPv4 address would be `73.55.242.3`
- This is limited, since there are less than 4.3 billion IPv4 addresses, and *over* 4.3 billion websites on the web today.

- IPv6 addresses consist of 128 bits -- four times more than IPv4.
  - Adoption of IPv6 is slow, but steady.

- **Network Address Translation (NAT)** lets organizations use one public IP address and many private IP addresses within the network.
  - Think of it like a business's receptionist, who transfers calls to private numbers inside the business.


#### Impact of the Internet

#### Impact

- **Globalization** is the movement that lets governments, businesses, and organizations communicate and integrate together on an international scale.

### Internet of Things

- The **Internet of Things** refers to the integration and interconnection of smart devices.

- Further reading: [What is the Internet of Things? WIRED explains](https://www.wired.co.uk/article/internet-of-things-what-is-explained-iot)

#### Privacy and Security

- Privacy is no longer a personal issue, it's a matter of national security.

- **Children's Online Privacy Protection Act (COPPA)** regulates the information you show to children under the age of 13.

- Copyright and intellectual property theft is also a massive subject of online policy.

- Computer security is no longer the job of specialist engineers--it's the job of *everybody*.

*Prepare for being hacked, by understanding how hacking works.*

[Content](#content)

------------------------------------------------------------------------------------Software-------------------------------------------------------------------------------
### Software

*As an IT Support Specialist, you'll be in a position to not only know how a given piece of technology functions, but also how to help fix it when it breaks.*

- **Software** is how we, as users, directly interact with our computer.

- If *hardware* is the physical stuff that you can pick up and hold, *software* is the intangible instructions that tell the hardware what to do.


#### What is Software?

#### Common software-related terms

- **Coding:** Translating one language to another.
  - Can be English to Spanish, or English to Morse Code, or English to binary.
  - When someone builds an application, we refer to it as *coding* an application.

- **Scripting:** Coding in a scripting language.
  - **Scripts** are mainly used to perform a single or limited-range task.

- **Programming:** Coding in a programming language.
  - **Programming languages** are special languages that software developers use to write instructions for computers to execute.

- The term *software* generally refers to something that was programmed.


#### Types of Software

- **Copyright** is used when creating original work.

- **Open-source software (OSS)** is a type of software that can allow freedom of use, modification, and sharing.
  - A good example is the Linux kernel. 
  - LibreOffice, GIMP, and FireFox are other examples of OSS.

- Open-source projects are usually contributed to by developers who work on the project for free on their own time.
  - Some of the greatest software efforts were built by a community of volunteers.

- **Application software** is any software created to fulfill a specific need, like a text editor, web browser, or graphic editor.

- **System software** is software used to keep our core system running, like operating system tools and utilities.

- **Firmware** is software that's permanently stored on a computer component.
  - An example would be the BIOS.

- Sequential numbering trend is used when categorizing software versions.
  - Further reading: [Software versioning](https://en.wikipedia.org/wiki/Software_versioning)


#### Revisiting Abstraction

*We can send binary code or bits to our CPU, then they'll use an instruction set to run those commands. But these CPUs might be from different manufacturers and may have different instructions.*

*[T]hanks to the efforts of computer scientists and the principle of abstraction, we can now use programming languages to write instructions that can be run on any hardware.*


#### Recipe for Computing

- In the early days of computing, scientists needed to replace the tedious system of punchcards.
  - Eventually, they invented a new language: Assembly.

- **Assembly language** allowed computer scientists to use human readable instructions, assembled into code, that the machines could understand.
  - Assembly allowed computer scientists to provide instructions not in binary code, but in human-readable language.

- But during that time, a program written for a specific CPU could only be run on that CPU (or CPU family).
  - The need for a program that could run on many different types of CPUs led to the development of compiled programming languages.

- **Compiled programming languages** use human readable instructions, then send them through a compiler.
  - The compiler converts the human readable instructions and converts them into machine readable instructions.
  - This technique was invented by Admiral Grace Hopper in 1959 to make programming easier.

- Along the way, another language was invented that was interpreted, rather than compiled.
  - Interpreted languages aren't compiled ahead of time.
  - A file written in one of these languages is usually called a script.
 - *The script is run by an interpreter, which interprets the code into CPU instructions just in time to run them.*

*Along the way, another type of language emerged that was interpreted rather than compiled. Interpreted languages aren't compiled ahead of time. A file that has code written in one of these languages is usually called a Script. The script is run by an interpreter, which interprets the code into CPU instructions just in time to run them.*

#### What's the difference between compiled language and interpreted language?
*Interpreted languages are not broken into machine instructions beforehand, like compiled languages are.*

#### What's the benefit of scripting?
*As an IT support specialist, scripting can help you by harnessing the power of a computer to perform tasks on your behalf, allowing you to solve a problem once and then move on to the next thing.*


#### Interacting with Software

#### Managing Software

- Programs, software, and applications are synonymous with each other.

- There are different types of software, that perform specific functions.
  - *Drivers* which let us interact with our hardware.
  - *Applications* we use for our day-to-day job functions.
  - *Utilities* we use, such as calculators, settings, and other tools.

- You should always test new software before letting your company use it.

- Old software is another problem.
  - When you run old software on your machine, you expose yourself to cybersecurity attacks that take advantage of software bugs.
  - **Software bugs** are errors in software that causes unexpected results.

- Update your software constantly.

- **Software management** includes many tasks such as installing, updating, and removing software.
  - You want to make sure a worker's computer has all the software required for their job.


#### Installing, Updating, and Removing Software on Windows

- **Git** is a version control system that helps keep track of changes made to files and directories.

- Remember to mirror the bit architecture of your CPU (32-bit or 64-bit) and mirror accordingly.

- **.exe** is a file extension found in Windows for an executable file.

- Sometimes after installing new software, your system prompts you to reboot. Make sure you do.
  - There might be system files or processes that also need to restart for your new software to work correctly.

- To verify you've installed a new program in Windows, navigate to `Add or remove programs` (or "Apps & features") 
  - From there, search in the text field in the "Apps & features" card.


#### Installing, Updating, and Removing Software on Linux

- Unlike using the GUI shell to manage software in Windows, you use the CLI shell in Linux:
  - `apt install git`
    - `apt` is the command used in Ubuntu's package manager
    - `The `install` option will let you install something. 

- You need authorization to install on Linux, which requires the `sudo` command.
  - `sudo` stands for "superuser do," basically saying you are the administrator.

- To uninstall, run `sudo apt remove` followed by the program.


#### Software Automation

It's easy to manage software on one machine; but what if you need to manage software across many machines?
- A solution to this is automation.

- **Automation** Makes processes work automatically.
  - Through automation, you can use programs and scripts to help with troubleshooting issues.
  - For example, reading hundreds of lines log files to discover an error, you can write a script to read the log for you; and print out only the relevant line.

[Content](#content)


---------------------------------------------------------------------------------Troubleshooting--------------------------------------------------------------------

### Troubleshooting

Ask great questions to understand a problem;
Isolate the problem to an effective area;
Look at the cookie crumbs in that area.

#### Troubleshooting Best Practices

*"Knowing how to analyze an issue, identifying the causes and effects, and use the information to find potential solutions are skills that everyone from I.T. support specialists, to doctors can use."*

#### Ask Questions!

- **Troubleshooting** is the ability to diagnose and resolve a problem.

- The first thing to do in troubleshooting is to *ask questions*.

- Never. *Never* make the user feel silly or dumb.
  - IT Support is about working in the service of others.
  - Always try to create a positive experience for the user.

#### Isolating the Problem

- The *isolate the problem* method shrinks the scope of the potential issue.
  - Narrow the scope.
  - After continually isolating the problem, you arrive at the root cause.

- **Root cause:** The main factor that's causing a range of issues.


#### Follow the Cookie Crumbs

- Logs are a great starting point.

- Error messages are extremely helpful indicators that can point you in the right direction.
  - Start from the first error


#### Start with the Quickest First Step

- Sometimes, there are multiple options you can use to isolate something. Which tho try first?
  - Try whatever is fastest, first.


#### Troubleshooting Pitfalls to Avoid

You may encounter the same issue over, and over again.

#### Going into autopilot
- Don't default to "autopilot mode"
- Don't move through issues out of habit/muscle memory, and without careful thought
- Small variables can change the problem entirely
- Ask questions and gather data, so you fully and accurately understand the problem

#### Not finding the root cause
- Don't get distracted by small problems that emerge
- There's probably a big problem causing all the small problems
- Spend a little time investigating the issue, instead of fixing small holes

---

*"Remember, when tasked with a problem, don't jump to conclusions. Ask questions first and gather more information. The issue be an incorrect login, a poor network connection, a server issue with the bank, or something else. Always ask questions first!"*

*"Since you've already gathered information about the problem, it's time to start figuring out what the issue is. There are two things that could be wrong: either the computer is having issues or it's the network. You can rule one out by testing whether or not someone else is able to connect to the network."*

*"Remember to ask questions in order to try to figure out what happened before the issue came up."*

*"A reboot might be required for the software to be fully installed. In this case, a reboot is also the quickest troubleshooting step to take."*



#### Customer Service

*Good customer service builds brand loyalty.*

#### Intro to Soft Skills

- Whenever possible, acknowledge the user
  - Provide feedback

- Empathy and acknowledgement are critical to building trust with the user

- Be honest with the user, even when you think they won't be happy about it

#### Anatomy of an Interaction

1. Set a good first impression
  - Be professional, acknowledge the user, and show them respect
2. Responding to users' question
  - Integrate information into the conversation, show active listening
3. Clarify the issue before you troubleshoot
  - Don't waste the user's time
4. End on a positive note
  - The last five minutes of the interaction set the tone for how the user feels walking away from the interaction
  - Make it positive by reiterating the resolution, state the next steps, and ask for any more questions

#### How to Deal with Difficult Situations

- When you identify your "reboot" action, write it down!

- Be patient!

- Break steps down into smaller, digestible points for the user

- Try to see things from other peoples' point of view

- It's easy to want to give up on a user when they're upset; but you need to put yourself in their shoes
  - They may not be thinking rationally, and may be under a significant amount of stress


#### Documentation

#### Ticketing Systems and Documenting Your Work

- There are two main ways of documenting information in the IT industry
  - The *ticketing* or *bug system*
  - ?

#### The Ticketing System
- **Tickets** are a common way of documenting an issue.
- **Bugs** are issues with the system that weren't caused by an external source.

- There are several IT industry-specialized systems to keep track of issues, such as:
  - [Bugzilla](https://www.bugzilla.org/)
  - [JIRA](https://www.atlassian.com/software/jira)
  - [Redmine](https://www.redmine.org/)

- Update the ticket with what the issue is, the steps/procedures you're trying to resolve, and the solution you arrived at.
  - This is important for two reasons:
    1. It keeps the user in the loop;
    2. It helps audit your steps, in case you need to revisit the issue.

- But when documenting, be concise.
  - You aren't writing a story--don't be creative or cute.
  - Be technical, accurate, and let the reader quickly figure things out.

#### Process Documentation

- No documentation is the *worst* documentation.

- Good documentation:
  - Starts with a clear problem;
  - It gives you background information on what the issue is;
  - And it gives you exact instructions on how to fix the issue
    - "Including which settings to navigate to and where."

#### Documenting in Ticketing Systems

- You don't have to leave a full example of processed documentation for every issue you handled.
  - If you encounter the same issue, just write the documentation once, and refer back to it.

- One of the more important aspects of documentation for a ticket or bug is leaving an audit trail to see what worked and what didn't.

- An example of good documentation in a ticketing system:
Tech described what the issue is; what caused the issue; and the specific steps they took to resolve it.


#### Getting Through a Technical Interview

#### Standing Out from the Crowd

- Your resume is your first introduction to a new company.

- Research the company that you're applying to.

#### Getting Ready for the Interview

- Pretending you're in an interview, even if it's not real, will help you perform your best.

- Articulating yourself clearly is key to nailing the interview.

- It's not about knowing the answers--you need to show your ideas clearly and concisely.

- Take some general technical subjects (DHCP, DNS, Active Directory, etc), and explain it.
  - What's it for?
  - How's it used?

- Learn to explain the same concepts in different ways.
  - This will help you adapt your answers in the actual interview.

- But you *should* memorize your elevator pitch.
  - **Elevator pitch** A short summary of who you are and what kind of career you're looking for.
  - Include your passions, how you'd like to grow, and what you're looking for in a new role.
  - Practice delivering this pitch to different people, and see how it sounds.
  - Stay flexible with it.

- The key to getting interviews right is *practice, practice, practice*.

#### Creating Your Elevator Pitch

#### What to Expect During the Technical Interview

- These interviews may take the form of technical troubleshooting scenarios or explanations of technical concepts and subjects.

- You need a solid foundation in all the fundamental concepts:
  - Networking
  - Operating systems
  - System administration
  - Security

- Having a good problem-solving strategy is more important than knowing all the answers.

- When you mention concepts or technologies, you should be ready to explain them and articulate why you may choose one thing over another.

- Clarify the question's constraints.
  -It's okay--and even expected--to ask the interviewer follow-up questions to ensure that the problem is correctly framed.

#### Showing Your Best Self During the Interview

- Get a good night's sleep

- Eat a proper breakfast

- Be fully present for the duration of the interview.

- Don't forget to be yourself.

- Ask questions about the things that you care about.
  - Found out if this is the company you want to work for, or if you can meet your career goals there.

- Remember to slow down.

[Content](#content)