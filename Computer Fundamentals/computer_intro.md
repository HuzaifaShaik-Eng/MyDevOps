# what is a computer?

   A computer is an electronic device that: Receives input --> Processes data --> stores data --> produces output.

   ##### Example: 
             Keyboard Input
                  ↓
                 CPU
                  ↓
            RAM ↔ Storage
                  ↓
            Monitor Output

  ##### For DevOps: 
               User Request
                    ↓
                Web Server
                    ↓
                Application
                    ↓
                 Database
                    ↓
                Response

A server is simply a computer designed to provide services to other computers.

  ---

## Components of a computer
A computer consists of two main components:
1. **Hardware** - The physical parts of acomputer that tou can touch and see.
2. **Software** - The programs and the instructions that run on the hardware.

### 1. Hardware Components
Think of a computer as a car. Just as a car has an engine, wheels, and fuel, a computer has different parts that work together:
- **CPU (Central Processing Unit)** – The *brain* of the computer, responsible for executing instructions.
- **RAM (Random Access Memory)** – The *short-term memory*, temporarily storing data that is currently in use.
- **Storage Devices** – The *long-term memory*, such as Hard Disk Drives (HDD) and Solid-State Drives (SSD), where files and programs are stored.
- **Input Devices** – Devices like a **keyboard** and **mouse**, which allow users to interact with the computer.
- **Output Devices** – Devices like a **monitor** and **printer**, which display or present information from the computer.

### 2. Software Components
Just like a car needs a driver and navigation system, a computer needs software to function properly:
- **Operating System (OS)** – Manages the hardware and allows users to interact with the computer.
- **Applications** – Programs that perform specific tasks, like web browsers and word processors.
- **Drivers** – Software that helps the OS communicate with hardware components.
- **Utilities** – Tools that help maintain the system, such as antivirus programs and disk cleanup software.

---
### Operating System (OS):
An Operating System (OS) is software that acts as an intermediary between applications and hardware that means it allows a computer's hardware and software to communicate with each other.
without an OS:

     Application
          ↓
      Hardware

Every application would need to directly communicate with the CPU, RAM, disk, and network devices, which is extremely difficult.
with an OS:

      Application
          ↓
      Operating System
          ↓
      Hardware

The OS manages all hardware resources and provides services to applications.

**Responsibilities of an Operating System:**

1. Process Management
2. Memory Management
3. File management
4. Device Management
5. Network Management

Operating Systems may also include other applications like text editors, file manager, graphical user interface, software manager etc.,

Example:
- Microft Windows
- MacOS
- Linux
- Android etc.,

---
### Virtualization:
Before cloud computing existed, Companies had a major problem:

                  1 Physical Server
                         ↓
                  1 Application

Most of the server's resources were wasted.
Example:
- Server capacity: CPU = 100%,
                 RAM = 32 GB
- Application uses:
                 CPU = 10%,
                 RAM = 4 GB
  
90% of the server remained idle.

Problems:
   - Expensive
   - Wasted resources
   - More power consumption
   - More maintenance

to solve this problem, **Virtualization** was introduced. 

With Virtualization

               Single Physical Server
                       ↓
               |--------------------|
               | Hypervisor         |
               |--------------------|
               | VM1 - App A        |
               | VM2 - App B        |
               | VM3 - App C        |
               |--------------------|


Benefits:

- Better resource utilization
- Lower cost
- Easier management

#### Virtual Machine (VM):
A VM is simply a computer running from within another computer(host). A VM shares the host resources and behaves exactly like a standalone physical machine.

**Virtualization** is the technology that allows multiple virtual computers (Virtual Machines) to run on a single physical computer.

             Physical Server
                   ↓
            Virtualization
                   ↓
                  VM1
                  VM2
                  VM3
                  VM4

Each VM behaves like a separate computer.

Example:


VM1
├── Ubuntu
├── 2 vCPUs
├── 4 GB RAM
└── 50 GB Disk

VM2
├── Windows Server
├── 4 vCPUs
├── 8 GB RAM
└── 100 GB Disk

All VMs share the same physical machine.
