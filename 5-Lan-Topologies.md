# LAN TOPOLOGIES – COMPLETE DEEP NOTES

## 1. Introduction to LAN Topology

LAN stands for **Local Area Network**. It is a computer network that connects computers and other devices within a limited geographical area, such as a home, school, college, office or building.

**Network topology** refers to the physical or logical arrangement of computers, cables and other networking devices in a network.

In simple words, LAN topology describes how computers and other devices are connected and communicate with each other in a network.

### Definition

LAN topology is the arrangement or structure of networking devices and connections within a Local Area Network (LAN). It defines how computers, servers, switches and other devices are interconnected.

### Examples of LAN:
- Computer networks in schools.
- Computer laboratories in colleges.
- Office computer networks.
- Networks in banks.
- Home Wi-Fi networks.

## 2. Types of Network Topologies

There are several types of network topologies used in computer networks.

The main types are:

1. Bus Topology
2. Star Topology
3. Ring Topology
4. Mesh Topology
5. Tree Topology
6. Hybrid Topology
7. Point-to-Point Topology

---

## 3. Bus Topology

### Definition

Bus topology is a type of network topology in which all computers and devices are connected to a single central cable called the backbone cable.

Data travels through the main cable, and each connected device receives the data. Only the device whose address matches the destination processes it.

### Working of Bus Topology

1. All computers are connected to a single main cable.
2. When a computer sends data, the data travels along the backbone cable.
3. All connected computers can detect the transmitted data.
4. The destination computer accepts the data.
5. Terminators are placed at both ends of the cable to prevent signal reflection.

### Diagram

```text
Terminator                         Terminator
    |                                   |
  [PC1]       [PC2]       [PC3]       [PC4]
    |           |           |           |
====|===========|===========|===========|====
              Backbone Cable
```

### Advantages of Bus Topology

1. Easy to install and configure.
2. Requires less cable compared to some other topologies.
3. Low installation cost.
4. Suitable for small networks.
5. Does not require a central networking device.

### Disadvantages of Bus Topology

1. If the backbone cable fails, the entire network stops working.
2. Network performance decreases when more devices are connected.
3. Troubleshooting is difficult.
4. Data collisions may occur.
5. Limited cable length and number of devices.

### Applications

- Small computer networks.
- Temporary networks.
- Older Ethernet networks.

---

## 4. Star Topology

### Definition

Star topology is a network topology in which all computers and devices are connected to a central networking device, such as a hub or switch.

All communication between devices passes through the central device.

### Working of Star Topology

1. Every computer is connected to a central hub or switch.
2. When one computer sends data, it first reaches the central device.
3. The switch forwards the data to the destination device.
4. Other devices remain unaffected by the communication.
5. Each computer has its own separate connection to the central device.

### Diagram

```text
                 [PC1]
                   |
       [PC2] --- [SWITCH] --- [PC3]
                   |
                 [PC4]
```

### Advantages of Star Topology

1. Easy to install and manage.
2. Easy to detect and troubleshoot faults.
3. Failure of one cable does not affect other computers.
4. Easy to add or remove devices.
5. Provides good network performance.
6. Suitable for large and small LANs.

### Disadvantages of Star Topology

1. If the central switch or hub fails, the entire network stops working.
2. Requires more cable than bus topology.
3. Installation cost is higher.
4. Network performance depends on the central device.

### Applications

- Schools and colleges.
- Computer laboratories.
- Offices.
- Banks.
- Home and business networks.

---

## 5. Ring Topology

### Definition

Ring topology is a type of network topology in which each computer is connected to two neighbouring computers, forming a closed circular path.

Data travels from one device to another around the ring until it reaches its destination.

### Working of Ring Topology

1. Every computer is connected to two neighbouring computers.
2. All computers form a circular network.
3. Data travels from one computer to the next.
4. Each device forwards the data to the next device.
5. The destination computer receives the data.

Some ring networks use a token-passing mechanism to control which device can transmit data.

### Diagram

```text
          [PC1] -------- [PC2]
            |              |
            |              |
          [PC4] -------- [PC3]
```

### Advantages of Ring Topology

1. Data transmission can be organized efficiently.
2. Token passing helps prevent data collisions.
3. Every computer gets an opportunity to transmit data.
4. Performs predictably under controlled traffic conditions.

### Disadvantages of Ring Topology

1. Failure of one device or connection can interrupt a basic single-ring network.
2. Adding or removing devices may interrupt communication.
3. Troubleshooting can be difficult.
4. Data may travel through multiple devices before reaching its destination.

### Applications

- Older Token Ring networks.
- Some fibre-optic communication networks.
- Specialized industrial networks.

---

## 6. Mesh Topology

### Definition

Mesh topology is a network topology in which devices are connected to multiple other devices.

In a full mesh topology, every device has a direct connection to every other device.

In a partial mesh topology, only some devices have direct connections to multiple devices.

### Types of Mesh Topology

**1. Full Mesh Topology**

In full mesh topology, every computer is directly connected to all other computers in the network.

**2. Partial Mesh Topology**

In partial mesh topology, some devices are connected to multiple devices, while others have fewer connections.

### Working