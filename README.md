# AutoRecon: Lightweight Web Vulnerability Scanner for Small Businesses

AutoRecon is an open-source, lightweight, and user-friendly web vulnerability scanner built for small businesses and beginner cybersecurity enthusiasts. It automates key reconnaissance tasks and detects common vulnerabilities such as missing HTTP security headers, outdated CMS versions, and potential XSS/SQLi points.

## 🚀 Features

- 🔍 Port and service detection using Python sockets/Nmap
- 🕵️ CMS fingerprinting via HTTP headers and HTML analysis
- 🛡️ Checks for common vulnerabilities:
  - SQL Injection (SQLi)
  - Cross-site Scripting (XSS)
  - Missing security headers
- 📁 Directory enumeration with a custom wordlist
- 📄 Clean, human-readable reports in Markdown or HTML format
- ⚙️ Configurable scan depth, timeouts, and modes

## 🧰 Built With

- Python
- `requests`, `beautifulsoup4`, `socket`, `argparse`
- Custom scripts: `recon.py`, `scanner.py`, `reporter.py`

## 🧪 Tested On

- DVWA (Damn Vulnerable Web Application)
- OWASP Juice Shop
- WordPress test sites

## 📊 Sample Output

- Detected outdated WordPress version
- Flagged missing headers like `Content-Security-Policy`
- Found test inputs vulnerable to XSS/SQLi patterns
- Completed scans in under 5 minutes for small sites

## 📎 Project Structure

AutoRecon/
├── recon.py # Domain recon, WHOIS, subdomain finding
├── scanner.py # Scans for vulnerabilities
├── reporter.py # Generates reports
├── config.json # Configurable options (optional)
├── wordlist.txt # Custom wordlist for dir enum
└── README.md # Project description


## 🎯 Intended Users

- Small businesses lacking enterprise-grade security tools
- Cybersecurity students and hobbyists
- Ethical hackers for non-intrusive testing

## 📈 Future Plans

- Web GUI using Flask
- AI-based CMS detection
- CVE threat feed integration
- Scheduled scans + email alerts

## ✅ Ethical Usage

AutoRecon is intended for **ethical** and **educational** use only. Always have proper authorization before scanning any target. This tool **does not exploit** vulnerabilities.

## 👥 Authors

Team Geeks:
- Sayooj Mohan
- Shruti Pawar
- Sahil Tambe

Internship under **Digisuraksha Parhari Foundation** (Powered by Infinisec Technologies Pvt. Ltd.)

## 📄 License

[MIT License](LICENSE) – Free to use with attribution.
