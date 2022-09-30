# MY Notes-On-Computer-System-Fundamentals

#### Chapter 0   Preface
#### 0.1. About OpenCSF
#### 0.2. How to Use this System
#### Chapter 1   Introduction to Computer Systems
#### 1.1. Introduction to Concurrent Systems
#### 1.2. Systems and Models
#### 1.2.1. Models as Representations
#### 1.2.2. From Models to Implementations
#### 1.3. Themes and Guiding Principles
#### 1.3.1. Systems as Foundations of Computing
#### 1.3.2. Systems and Complexity
#### 1.3.3. The Semiotics of Computer Systems
#### 1.4. System Architectures
#### 1.4.1. Client/Server Architectures
#### 1.4.2. Peer-to-peer (P2P) Architectures
#### 1.4.3. Layered Architectures
#### 1.4.4. Pipe-and-filter Architectures
#### 1.4.5. Event-driven Architectures
#### 1.4.6. Hybrid Architectures
#### 1.5. State Models in UML
#### 1.5.1. State Space Explosion
#### 1.5.2. Implementing Finite State Machines
#### 1.6. Sequence Models in UML
#### 1.6.1. Summary Questions
#### 1.7. Extended Example: Text Parser State Machine
#### Chapter 2   Processes and OS Basics
#### 2.1. Processes and OS Basics
#### 2.2. Processes and Multiprogramming
#### 2.2.1. Uniprogramming and Utilization
#### 2.2.2. Multiprogramming and Concurrency
#### 2.2.3. Context Switches and Overhead Costs
#### 2.3. Kernel Mechanics
#### 2.3.1. Kernel Memory Structure and Protections
#### 2.3.2. The Boot Procedure
#### 2.3.3. Kernel Invocation
#### 2.3.4. Mode Switches and Privileged Instructions
#### 2.4. System Call Interface
#### 2.4.1. System Calls vs. Function Calls
#### 2.4.2. Linux System Calls
#### 2.4.3. Calling System Calls in Assembly
#### 2.4.4. Calling System Calls with syscall()
#### 2.5. Process Life Cycle
#### 2.5.1. Process Creation
#### 2.5.2. Switching Program Code
#### 2.5.3. POSIX Spawn Interface
#### 2.5.4. Process Destruction
#### 2.6. The UNIX File Abstraction
#### 2.6.1. Basic File Access
#### 2.6.2. Working with Files
#### 2.6.3. Accessing File Metadata
#### 2.7. Events and Signals
#### 2.7.1. Sending Process Signals
#### 2.7.2. Custom Signal Handlers
#### 2.8. Extended Example: Listing Files with Processes
#### Chapter 3   Concurrency with IPC
#### 3.1. Concurrency with IPC
#### 3.2. IPC Models
#### 3.2.1. Advantages and Disadvantages
#### 3.2.2. An IPC Taxonomy
#### 3.3. Pipes and FIFOs
#### 3.3.1. Basic Pipes
#### 3.3.2. Pipes and Shell Commands
#### 3.3.3. FIFOs
#### 3.4. Shared Memory With Memory-mapped Files
#### 3.4.1. Memory-mapped Files
#### 3.4.2. Region Protections and Privacy
#### 3.5. POSIX vs. System V IPC
#### 3.5.1. POSIX IPC Fundamentals
#### 3.6. Message Passing With Message Queues
#### 3.6.1. POSIX Message Queues
#### 3.7. Shared Memory
#### 3.7.1. POSIX Shared Memory
#### 3.8. Semaphores
#### 3.8.1. POSIX vs. System V Semaphores
#### 3.8.2. POSIX Named Semaphores
#### 3.8.3. POSIX Unnamed Semaphores
#### 3.9. Extended Example: Bash-lite: A Simple Command-line Shell
#### Chapter 4   Networked Concurrency
#### 4.1. Networked Concurrency
#### 4.2. The TCP/IP Internet Model
#### 4.2.1. Internet Model
#### 4.2.2. Packet Encapsulation and Nomenclature
#### 4.3. Network Applications and Protocols
#### 4.3.1. Naming and Addressing
#### 4.3.2. Protocol Specifications and RFCs
#### 4.4. The Socket Interface
#### 4.4.1. Networking Data Structures
#### 4.4.2. Client Socket Interface
#### 4.4.3. Server Socket Interface
#### 4.4.4. Socket Communication
#### 4.5. TCP Socket Programming: HTTP
#### 4.5.1. Hypertext Transfer Protocol (HTTP)
#### 4.5.2. BNF Protocol Specification
#### 4.5.3. HTTP/1.1 Persistent Connections
#### 4.5.4. Processing HTTP Headers
#### 4.5.5. Persistent State with Cookies
#### 4.6. UDP Socket Programming: DNS
#### 4.6.1. Resolving DNS Queries
#### 4.6.2. DNS Resource Record Structure
#### 4.6.3. DNS Protocol Messages
#### 4.6.4. Constructing DNS Queries with Sockets
#### 4.6.5. Processing DNS Query Responses
#### 4.7. Application-Layer Broadcasting: DHCP
#### 4.7.1. DHCP Overview
#### 4.7.2. DHCP Protocol Messages
#### 4.8. Extended Example: CGI Web Server
#### Chapter 5   The Internet and Connectivity
#### 5.1. The Internet and Connectivity
#### 5.2. Application Layer: Overlay Networks
#### 5.2.1. Characteristics of Peer-to-Peer Networks
#### 5.3. Transport Layer
#### 5.3.1. Unreliable Transport: UDP
#### 5.3.2. Reliable Transport: TCP
#### 5.3.3. TCP Handshake and Connections
#### 5.3.4. TCP Timeout and Packet Loss
#### 5.4. Network Security Fundamentals
#### 5.4.1. Symmetric Key Encryption
#### 5.4.2. Public Key Encryption
#### 5.4.3. Cryptographic Hash Functions
#### 5.4.4. Transport-Layer Security (TLS)
#### 5.4.5. TLS in Practice: HTTPS
#### 5.5. Internet Layer: IP
#### 5.5.1. IP Addresses and Subnets
#### 5.5.2. IP Packet Formats
#### 5.5.3. Network Routing Protocols
#### 5.6. Link Layer
#### 5.6.1. LAN Packet Transmission: Ethernet
#### 5.6.2. LAN Packet Transmission: ARP
#### 5.6.3. What Lies Beneath: Carrier Signals
#### 5.7. Wireless Connectivity: Wi-Fi, Bluetooth, and Zigbee
#### 5.7.1. Wireless Protocol Stacks and Uses
#### 5.8. Extended Example: DNS Client
#### Chapter 6   Concurrency with Multithreading
#### 6.1. Concurrency with Multithreading
#### 6.2. Processes vs. Threads
#### 6.2.1. Multithreading
#### 6.2.2. Advantages and Disadvantages of Threads
#### 6.2.3. Thread Models
#### 6.3. Race Conditions and Critical Sections
#### 6.3.1. Race Conditions
#### 6.3.2. Critical Sections
#### 6.3.3. Thread Safety and Reentrancy
#### 6.4. POSIX Thread Library
#### 6.4.1. Creating and Joining Threads
#### 6.4.2. Attached and Detached Threads
#### 6.5. Thread Arguments and Return Values
#### 6.5.1. Passing a Single Argument to Threads
#### 6.5.2. Passing Multiple Arguments to Threads
#### 6.5.3. Returning Values from Threads
#### 6.6. Implicit Threading and Language-based Threads
#### 6.6.1. Implicit Threading with OpenMP
#### 6.6.2. Threads as Objects
#### 6.6.2.1. Java Threads
#### 6.6.2.2. Python Threads
#### 6.6.3. Concurrency as Language Design
#### 6.6.3.1. Goroutines
#### 6.6.3.2. Rust Concurrency
#### 6.7. Extended Example: Keyboard Input Listener
#### 6.8. Extended Example: Concurrent Prime Number Search
#### Chapter 7   Synchronization Primitives
#### 7.1. Synchronization Primitives
#### 7.2. Critical Sections and Peterson’s Solution
#### 7.2.1. Peterson’s Solution
#### 7.2.2. Synchronization Properties
#### 7.2.3. Peterson’s Solution and Modern Hardware
#### 7.3. Locks
#### 7.3.1. POSIX Mutexes
#### 7.3.2. Spinlocks
#### 7.3.3. Defining Critical Sections
#### 7.4. Semaphores
#### 7.4.1. Semaphores as Signaling
#### 7.4.2. Mutual Exclusion with Semaphores
#### 7.4.3. Multiplexing with Semaphores
#### 7.5. Barriers
#### 7.5.1. Concurrent Calculations with Barriers
#### 7.6. Condition Variables
#### 7.6.1. Condition Variables vs. Semaphores
#### 7.6.2. How to Use a Condition Variable
#### 7.6.3. A Condition Variable Example
#### 7.6.4. Monitors and Synchronized Methods
#### 7.7. Deadlock
#### 7.7.1. Necessary Conditions
#### 7.7.2. Livelock and False Solutions
#### 7.7.3. Avoiding Deadlock
#### 7.8. Extended Example: Event Log File
#### Chapter 8   Synchronization Patterns and Problems
#### 8.1. Synchronization Patterns and Problems
#### 8.2. Basic Synchronization Design Patterns
#### 8.2.1. Signaling
#### 8.2.2. Turnstiles
#### 8.2.3. Rendezvous
#### 8.2.4. Multiplexing
#### 8.2.5. Lightswitches
#### 8.3. Producer-Consumer Problem
#### 8.3.1. Producer-Consumer with Unbounded Queue
#### 8.3.2. Single Producer-Single Consumer Solution Using a Bounded Queue
#### 8.3.3. Multiple Producers Solution Using a Bounded Queue
#### 8.4. Readers-Writers Problem
#### 8.4.1. A Solution Using Lightswitches
#### 8.4.2. Fairness to Writers
#### 8.4.3. Search-Insert-Delete Problem
#### 8.5. Dining Philosophers Problem and Deadlock
#### 8.5.1. Solution of Limiting Accesses
#### 8.5.2. Solution by Breaking Hold-and-wait
#### 8.5.3. Solution by Imposing Order
#### 8.6. Cigarette Smokers Problem and the Limits of Semaphores and Locks
#### 8.6.1. Implications of the Cigarette Smokers Problem
#### 8.6.2. On Cigarette Smokers and Dining Philosophers
#### 8.7. Extended Example: Parallel Modular Exponentiation
#### Chapter 9   Parallel and Distributed Systems
#### 9.1. Parallel and Distributed Systems
#### 9.2. Parallelism vs. Concurrency
#### 9.2.1. Multiprocessing Systems
#### 9.3. Parallel Design Patterns
#### 9.3.1. Algorithmic Strategy Patterns
#### 9.3.2. Implementation Strategy Patterns
#### 9.3.3. Parallel Execution Patterns
#### 9.4. Limits of Parallelism and Scaling
#### 9.4.1. Amdahl’s Law and Strong Scaling
#### 9.4.2. Gustafson’s Law and Weak Scaling
#### 9.5. Timing in Distributed Environments
#### 9.5.1. Clock Synchronization
#### 9.5.2. Logical Clocks and Lamport Timestamps
#### 9.5.3. Vector Clocks
#### 9.6. Reliable Data Storage and Location
#### 9.6.1. Google File System
#### 9.6.2. Distributed Hash Tables
#### 9.7. Consensus in Distributed Systems
#### 9.7.1. Byzantine Generals Problem
#### 9.7.2. Limits on Consensus
#### 9.7.3. Practical Byzantine Fault Tolerance
#### 9.8. Extended Example: Blockchain Proof-of-Work
#### Appendix A
#### 10.1. C Language Reintroduction
#### 10.2. Documentation and Debugging
#### 10.2.1. Man Pages
#### 10.2.2. Debugging with GDB
#### 10.2.2.1. Breakpoints and Watchpoints
#### 10.2.2.2. Backtrace
#### 10.2.2.3. Tracing multiple processes
#### 10.3. Basic Types and Pointers
#### 10.3.1. C99 Fixed-width Types
#### 10.3.2. Pointer Basics
#### 10.4. Arrays, Structs, Enums, and Type Definitions
#### 10.4.1. Two-dimensional Arrays
#### 10.4.2. Structs and Packing
#### 10.4.3. Enums and Type Definitions
#### 10.5. Functions and Scope
#### 10.5.1. Function Parameters and Return Values
#### 10.5.2. Call-by-Reference Parameters
#### 10.5.3. Arrays as Parameters
#### 10.6. Pointers and Dynamic Allocation
#### 10.7. Strings
#### 10.7.1. Investigating String Contents
#### 10.7.2. Common String Manipulations
#### 10.7.3. Converting Between Strings and Integers
#### 10.8. Function Pointers
#### 10.8.1. Passing Function Pointers as Arguments
#### 10.8.2. Function Pointer Lookup Tables
#### 10.9. Files
#### 10.9.1. File Permissions and Ownership
#### 10.9.2. Persistent Storage
#### 10.9.3. Directories and Links
#### 10.9.4. Advisory Locks
#### Appendix B
#### 11.1. Glossary
#### 11.2. Bibliography
#### Index
