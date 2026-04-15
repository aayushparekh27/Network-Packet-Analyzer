# 🌐 Advanced Packet Sniffer (Python Project)

A powerful **Packet Sniffer Tool** built using **Python** and the `scapy` library. This project captures live network packets, extracts useful information, and stores them for analysis.

---

## ⚠️ Important Disclaimer

This project is intended **strictly for educational and ethical purposes only**.
Do **NOT** use this tool on networks without proper authorization. Unauthorized packet sniffing may violate privacy laws.

---

## 🔥 Project Overview

This tool monitors network traffic in real-time and captures **TCP packets**, displaying important details such as source/destination IP, protocol, and payload. It also saves captured packets for further analysis.

---

## ✨ Features

✔️ Real-time packet capturing
✔️ Filters and captures only TCP packets
✔️ Displays packet details (IP, protocol, payload)
✔️ Logs packet data into a text file
✔️ Saves captured packets in `.pcap` format
✔️ Timestamp-based file naming

---

## 🛠️ Tech Stack

* **Language:** Python 🐍
* **Library:** scapy

---

## ⚙️ How It Works

* Sniffer listens to network traffic
* Filters TCP packets using `sniff()`
* Extracts:

  * Source IP
  * Destination IP
  * Protocol
  * Payload (partial)
* Logs data into a file
* Stores packets and saves them as `.pcap`

---

## 📂 Project Structure

```id="pkt112"
📁 Packet-Sniffer
│── sniffer.py            # Main script
│── packet_log.txt        # Log file (generated)
│── captured_packets.pcap # Captured packets (generated)
│── README.md             # Documentation
```

---

## 🖥️ Installation & Setup

### 1️⃣ Install Python

### 2️⃣ Install Required Library

```bash id="pip_pkt"
pip install scapy
```

---

## ▶️ How to Run

```bash id="run_pkt"
python sniffer.py
```

> ⚠️ Run with administrator/root privileges for packet capture

---

## 🧠 Learning Outcomes

* Network packet analysis
* Understanding TCP/IP protocols
* Using Scapy for packet sniffing
* Working with `.pcap` files
* Real-time data processing

---

## ⚠️ Requirements

* Root/Admin access required
* Works best on Linux (Kali, Ubuntu)
* Windows may require additional setup (Npcap)

---

## 🔐 Future Enhancements

🚀 Add GUI dashboard for live monitoring
🚀 Filter packets by IP/Port
🚀 Detect suspicious traffic patterns
🚀 Integrate with intrusion detection systems
🚀 Export logs in CSV/JSON format

---

## 👨‍💻 Author

**Aayush Parekh**
💻 Full Stack Developer | Ethical Hacker | Network Security Enthusiast

🛡️ *"Hack the bad, protect the good."*

---

## ⭐ Support

If you like this project, give it a ⭐ on GitHub!
