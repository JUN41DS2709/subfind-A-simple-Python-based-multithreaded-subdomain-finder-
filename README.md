# Subdomain Finder

A simple Python-based multithreaded subdomain finder that discovers subdomains using a wordlist.

## Features

- Wordlist-based subdomain enumeration
- Multithreading for faster scanning
- Custom wordlist support
- Custom thread count
- Verbose output mode
- Displays total subdomains found
- Displays scan time

## Requirements

- Python 3
- `requests`

Install the dependency:

```bash
pip install requests
```
## Usage

Basic scan :
```bash
python3 subfind.py example.com
```
Use a custom wordlist:
```bash
python3 subfind.py example.com -w wordlist.txt
```
Specify the number of threads:
```bash
python3 subfind.py example.com -t 100
```
Enable verbose output:
```bash
python3 subfind.py example.com -V
```
Show version:
```bash
python3 subfind.py -v
```
## Arguments
Argument	Description
domain	Target domain

- -w, --wordlist	Wordlist to use
- -t, --threads	Number of threads
- -V, --verbose	Show discovered subdomains
- -v, --version	Show version

## Screenshots

Verbose Output

Project Structure
```
subfind/
├── subfind.py
├── wordlist.txt
├── screenshots/
│   ├── scan.png
│   └── verbose.png
└── README.md
Disclaimer
```
**This tool is intended for educational purposes and authorized security testing only.
Only scan domains that you have permission to test.**

## Credits
Inspired by and learned from **The Cyber Expert**.

Thanks for the tutorial and guidance that helped me understand the concepts used in this project.
