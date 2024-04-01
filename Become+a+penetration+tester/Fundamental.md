# Penteration Testing
"A method of testing where tester target individual components or the application as whole to determine whether . . .vulnerabilites can be explioted to comprise the application, its data, or its environmental resources" ~NIST

Another Words:
a hands-on examination by a real person who tries to detect weaknesses in a system and determine how they could affect the business

`Kind of tester who work on security `

Penetration testers need to make the case for business consequences or else the need to change will not be taken seriously.

## Skills
1. General Knowledge
2. Operating System
3. Web Application
4. Databases
5. Knowledge of Tools
6. Methods of testing
7. Security testing

# Intersection Skills
Talk with Stake holder and explain them the architect

## What to know about clients
- What does the organization value
- How fo they make money
- What are the threats to said values and revenue

## What you should know
- Client and server basics
- client and server establishes a connection of three way handshake
- Differenence between TCP and UDP
- Layer 7 protocol
- Whay are they important

## Job
- Break into system
- Know what you are looking for
- Know where its located
- know how to access it
- Know how system is structured

## Question to Ask 
- Where the passwords are stored
- where web files are stored
- What kind of access do you need to be able to assess the files
- How do you cover your tracks

_____

- **Vulnerability**: A flaw or weakness in system, its security procedures, its internal control, or its design and implementation that can be explioted to violate the system security policy
_____

## You must know
- Along with insecure coding practices and misconfigurations, web application pen testers should know the OWASP Top 10 (Open Web Application Security Project)
- How mobile application are compiled, reverse engineered, decompiled, and recompiled
- Common types of vulnerabilities

# OS Fundamental

- **Operating System Fundamentals**:
  - Essential for a lasting career in penetration testing.
  - Key concepts include operating systems, risk, and web network fundamentals.

- **Market Share Insights**:
  - Windows dominates desktop OS market share (75%), followed by OSX (15%) and Linux (2.5%).
  - Android leads mobile OS market share (72%), with iOS at 27%.
  - Linux is prominent in web application penetration testing (48%).

- **Relevance to Penetration Testing**:
  - Understanding OS market share helps target testing efforts effectively.
  - Linux proficiency is crucial for mobile and web app penetration testers.
  - Windows expertise is valuable for network penetration testers.

- **Attack Machine Operating Systems**:
  - Top attack boxes for penetration testing mostly use Linux distributions.
  - Linux features a monolithic kernel and a treelike file structure.
  - Windows utilizes a DOS-based kernel with a different file storage system.

- **Fundamentals Importance**:
    - Where the passwords are stored
    - where web files are stored
    - What kind of access do you need to be able to assess the files
    - How do you cover your tracks
    - Knowing the differences between Windows and Linux services is crucial for penetration testing.


| **Operating System** | **Kernel Type**    | **File Structure** | **Key Features**       |
|----------------------|---------------------|--------------------|-------------------------|
| **Linux**            | Monolithic          | Tree-like           | Root directory, Subdirectories |
| **Windows**          | DOS-based           | Different drives    | Directory and folder structure |

- **Linux** 
    - monolithic kernel
    - tree structure
    - root directory
    - Sub Directories
- **Windows**
    - DOS- based kernel (Disk Operating System)
    - different drives
    - Directory and folder structure


___

1. **Disk Operating System (DOS)**:
   - **Definition**:
     - DOS is an early operating system that gained popularity in the 1980s.
     - It was primarily used on personal computers before graphical user interfaces (GUIs) became widespread.
   - **Architecture**:
     - DOS follows a **monolithic architecture**.
     - All components (device management, memory management, file management, etc.) are bundled together in a single binary.
     - The entire operating system runs in the **kernel space** without any separation between kernel and user-level processes.
   - **Example**:
     - Imagine DOS as a **toolbox** where all the tools (functions) are packed into a single box.
     - When you need to perform a task (like copying files or formatting a disk), you open the toolbox and use the appropriate tool.
     - DOS provides a command-line interface (CLI) where you type commands like `copy`, `dir`, or `format`.

2. **Monolithic Operating System**:
   - **Definition**:
     - A monolithic operating system provides all services within a single, large binary (the kernel).
     - It lacks separation between kernel and user-level processes.
     - All code runs in the kernel space.
   - **Example**:
     - Think of a monolithic OS as a **centralized control room** in a building.
     - In this control room, you have switches, buttons, and monitors to manage everything: lights, elevators, HVAC, security, and more.
     - Similarly, in a monolithic OS, the kernel controls everything directly—memory, processes, file systems, and devices.

Remember, both DOS and monolithic systems have their place in computing history, but modern operating systems have evolved significantly with more modular and layered designs! 


## Linux: Root type
```
/
├── bin
│   ├── ls
│   ├── cp
│   └── ...
├── home
│   ├── user
│   │   ├── Documents
│   │   │   ├── report.txt
│   │   │   └── notes.txt
│   │   ├── Pictures
│   │   │   ├── sunset.jpg
│   │   │   └── mountains.png
│   │   └── ...
├── etc
│   ├── passwd
│   ├── hosts
│   └── ...
├── var
│   ├── log
│   │   ├── syslog
│   │   └── messages
│   └── ...
├── usr
│   ├── bin
│   ├── lib
│   └── ...
└── ...

```

In this example:
- The **root directory** (`/`) is at the top level.
- Directories like `/bin`, `/home`, `/etc`, and `/var` contain various system files and user data.
- The `user` directory under `/home` represents a user's home directory.
- Inside the `user` directory, we have subdirectories like `Documents`, `Pictures`, and more.
- Files such as `report.txt`, `sunset.jpg`, and system executables (`ls`, `cp`) are organized within these directories.


# Windows: Drives

```
C:\
├── Program Files
│   ├── Common Files
│   └── WindowsApps
├── Users
│   ├── User1
│   │   ├── Documents
│   │   ├── Downloads
│   │   └── Pictures
│   ├── User2
│   └── ...
├── Windows
│   ├── System32
│   ├── SysWOW64
│   └── ...
├── ProgramData
├── AppData
│   ├── Local
│   ├── Roaming
│   └── ...
├── Temp
├── Recycle Bin
└── ...

D:\
├── Games
│   ├── Steam
│   └── Origin
├── Media
│   ├── Music
│   └── Videos
├── Backups
└── ...

E:\
├── Work
│   ├── Projects
│   └── Reports
├── Personal
│   ├── Photos
│   └── Documents
└── ...

F:\
├── External Drive
│   ├── Backup
│   └── Archives
└── ...
```

In this example:
- Each drive (C:, D:, E:, F:) represents a different storage location.
- The **C:** drive typically contains the operating system and user-specific data.
- The **Users** folder houses individual user profiles (User1, User2, etc.).
- System files reside in the **Windows** folder.
- **Program Files** stores installed applications.
- **AppData** contains application-specific data.
- **Recycle Bin** holds deleted files temporarily.

