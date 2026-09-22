 # 🔎 Python Network Scanner

A lightweight Python-based TCP network scanner designed for **authorized security testing and educational lab environments**.

The project was built to strengthen practical understanding of **computer networking, TCP/IP, socket programming, network reconnaissance, Python development, error handling, logging, and security analysis**.

## 🎯 Project Objective

The goal of this project is to develop a simple, transparent network-scanning tool while learning how TCP connections and exposed network services can be identified programmatically.

Rather than relying entirely on existing security tools, this project implements core scanning functionality using Python's networking capabilities.

## ✨ Features

* TCP port scanning
* Configurable target and port range
* Connection timeout control
* Input validation
* Open-port detection
* Scan statistics
* Structured terminal output
* Scan-result export
* Logging
* Error handling
* Automated tests
* Beginner-friendly architecture

## 🛠️ Technologies

* Python 3
* Python `socket`
* `argparse`
* `logging`
* `pytest`
* Linux / Kali Linux
* Git & GitHub

## 🧠 Concepts Demonstrated

* IPv4 addressing
* TCP connections
* Network ports
* Client-server communication
* Socket programming
* Network reconnaissance
* Input validation
* Exception handling
* Logging
* Software testing
* Security-focused programming

## 📂 Project Structure

```text
python-network-scanner/
│
├── scanner.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── results/
├── screenshots/
└── tests/
    └── test_scanner.py
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/python-network-scanner.git
cd python-network-scanner
```

Create a virtual environment:

```bash
python3 -m venv venv
source venv/bin/activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

## 🚀 Usage

Display available options:

```bash
python3 scanner.py --help
```

Example authorized lab scan:

```bash
python3 scanner.py --target 127.0.0.1 --start-port 1 --end-port 100
```

Example with a custom timeout:

```bash
python3 scanner.py --target 127.0.0.1 --start-port 1 --end-port 100 --timeout 0.5
```

## 📊 Example Output

```text
================================
PYTHON NETWORK SCANNER
================================

Target       : 127.0.0.1
Port range   : 1-100
Timeout      : 1.0 seconds

Scanning...

[OPEN] Port 22
[OPEN] Port 80

--------------------------------
Scan completed
Ports scanned : 100
Open ports    : 2
--------------------------------
```

## 🧪 Testing

The project includes tests for input validation, scanning behavior, error handling, and other core functionality.

Run the tests with:

```bash
pytest
```

## 🔐 Responsible Use

This project is intended for **educational purposes and authorized security testing only**.

Only scan systems, networks, and devices that you own or have explicit permission to test.

Do not use this tool to scan third-party systems without authorization.

## 📚 Learning Outcomes

Through this project I practiced:

* Python network programming
* TCP/IP fundamentals
* Socket programming
* Network reconnaissance concepts
* CLI application development
* Error handling
* Logging
* Automated testing
* Git/GitHub workflow
* Security-focused software development

## 🔮 Future Improvements

Planned improvements include:

* Concurrent scanning for authorized lab environments
* Improved result formatting
* JSON report generation
* Basic common-service identification
* More comprehensive test coverage
* Improved scan performance
* Modular scanner architecture

## 👨‍💻 Author

**Shivam Kumar**

B.Sc. Physical Science with Electronics
Cybersecurity & Digital Forensics Learner

## 📌 Disclaimer

This project was developed as part of my cybersecurity learning and portfolio development. It is intended for controlled laboratory environments and authorized security testing.
