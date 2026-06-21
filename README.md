# 🚀 Deep Packet Analyzer

A high-performance **Deep Packet Inspection (DPI)** and network traffic analysis system built in **C++**.

The project captures, parses, classifies, and filters network packets using modern networking concepts such as **Flow Tracking**, **TLS SNI Extraction**, and **Multi-threaded Packet Processing**.

Designed as a Computer Science project to explore real-world applications of **Cybersecurity**, **Networking**, and **System Programming**.

---

## ✨ Features

- 📡 PCAP packet capture and parsing
- 🔍 Deep Packet Inspection (DPI)
- 🌐 TLS SNI extraction for HTTPS traffic classification
- 🧠 Flow tracking using Five-Tuple identification
- 🚫 Rule-based blocking (IP, Domain, Application)
- ⚡ Multi-threaded architecture for high throughput
- 📊 Traffic statistics and application breakdown
- 🛠 Modular C++ design using CMake

---

## 🏗 Architecture

```text
Input PCAP
    │
    ▼
Packet Reader
    │
    ▼
Packet Parser
    │
    ▼
Flow Tracker (Five Tuple)
    │
    ▼
TLS SNI Extractor
    │
    ▼
Application Classification
    │
    ▼
Rule Engine
    │
 ┌──┴───┐
 │      │
Drop  Forward
 │      │
 ▼      ▼
Stats  Output PCAP
```

---

## 🛠 Tech Stack

| Category | Technology |
|----------|------------|
| Language | C++17 |
| Build System | CMake |
| Networking | TCP/IP, UDP |
| Concepts | DPI, TLS, Flow Tracking |
| Concurrency | Multi-threading |
| File Format | PCAP |

---

## 🚀 Getting Started

### Clone

```bash
git clone https://github.com/prithbiscoding/Deep_Packet_Analyzer.git
cd Deep_Packet_Analyzer
```

### Build

```bash
mkdir build
cd build

cmake ..
cmake --build .
```

### Run

```bash
./dpi_engine input.pcap output.pcap
```

---

## 🎯 Key Concepts Implemented

- Deep Packet Inspection (DPI)
- TLS Client Hello & SNI Extraction
- Five Tuple Flow Identification
- Packet Parsing (Ethernet, IPv4, TCP, UDP)
- Rule-Based Traffic Filtering
- Producer-Consumer Architecture
- Multi-threaded Processing Pipeline

---

## 📈 Future Improvements

- GUI Dashboard for live packet visualization
- Machine Learning based anomaly detection
- HTTP/3 and QUIC support
- Real-time packet capture from network interfaces
- Exportable analytics and reports

---

## 👨‍💻 Author

**Prithbi**  
Computer Science Engineering Student  

Interested in:

- Cybersecurity
- Networking
- System Programming
- Software Engineering

GitHub: https://github.com/prithbiscoding

---

⭐ If you find this project interesting, feel free to star the repository.
