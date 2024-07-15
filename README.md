# Understanding the OSI Model

A guide to the 7 layers of network communication.

## Introduction to OSI Model

The OSI (Open Systems Interconnection) model is a conceptual framework used to standardize network communication. It has 7 layers, each defining a specific function in the data transfer process.

| **Layer** | **Name**        | **Function**                                       | **Data Unit** | **Hardware**          | **Protocols**             |
|-----------|-----------------|----------------------------------------------------|---------------|-----------------------|---------------------------|
| 7         | Application     | Provides network services to end-user applications | Data          | -                     | HTTP, FTP, SMTP           |
| 6         | Presentation    | Translates data between application and network formats, handles encryption/decryption | Data          | -                     | SSL/TLS                   |
| 5         | Session         | Manages sessions between applications              | Data          | -                     | APIs, Sockets, RPC        |
| 4         | Transport       | Ensures end-to-end data transfer, error recovery, and flow control | Segment       | -                     | TCP, UDP                  |
| 3         | Network         | Routes data packets between devices across different networks | Packet        | Routers               | IP                        |
| 2         | Data Link       | Provides node-to-node data transfer and error detection | Frame         | Switches, Bridges     | Ethernet, PPP             |
| 1         | Physical        | Transmits raw bit streams over a physical medium   | Bits          | Cables, Hubs, NICs    | -                         |

### Layer 1: Physical Layer
- **Function**: Transmits raw data bits over a physical medium.
- **Data Unit**: Bits
- **Hardware**: Cables, Hubs, Network Interface Cards (NICs)
- **Protocols**: -

### Layer 2: Data Link Layer
- **Function**: Ensures reliable node-to-node data transfer, error detection, and correction.
- **Data Unit**: Frame
- **Hardware**: Switches, Bridges
- **Protocols**: Ethernet, PPP (Point-to-Point Protocol)

### Layer 3: Network Layer
- **Function**: Manages data routing between networks using logical addressing (IP addresses).
- **Data Unit**: Packet
- **Hardware**: Routers
- **Protocols**: IP (Internet Protocol)

### Layer 4: Transport Layer
- **Function**: Ensures end-to-end communication, error-free data delivery, flow control.
- **Data Unit**: Segment
- **Hardware**: -
- **Protocols**: TCP (Transmission Control Protocol), UDP (User Datagram Protocol)

### Layer 5: Session Layer
- **Function**: Manages sessions and connections between applications.
- **Data Unit**: Data
- **Hardware**: -
- **Protocols**: APIs, Sockets, RPC (Remote Procedure Call)

### Layer 6: Presentation Layer
- **Function**: Translates data between application and network formats, handles encryption/decryption.
- **Data Unit**: Data
- **Hardware**: -
- **Protocols**: SSL (Secure Sockets Layer), TLS (Transport Layer Security)

### Layer 7: Application Layer
- **Function**: Provides network services directly to end-user applications.
- **Data Unit**: Data
- **Hardware**: -
- **Protocols**: HTTP (Hypertext Transfer Protocol), FTP (File Transfer Protocol), SMTP (Simple Mail Transfer Protocol)

---

## About Me

Hi, I'm Vishesh Dhiman (Chotu Dhiman). I'm passionate about networking and cybersecurity. Follow me for more tech insights and tutorials.

### Connect with me:
- **Instagram**: [HackinGyan](https://instagram.com/HackinGyan)
- **Telegram**: [CyberHackerZone](https://t.me/CyberHackerZone)
- **GitHub**: [Your GitHub Profile](https://github.com/Vishesh-Dhiman)

### Learn more about the OSI Model:
- None
---

Thank you for reading! If you have any questions or want to collaborate, feel free to reach out.
