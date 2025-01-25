# Nmap utility (MacOS)

### Description
Shellog is a logging utility designed for use in **Shell** scripts.
It is designed to write messages to a log file with support for different logging levels (INFO, ALERT, ERROR),
and to output logs to the terminal with color highlighting depending on the logging level. The logger automatically records messages with timestamp and operating system.

![Stars](https://img.shields.io/github/stars/interl1nk/shellog?style=social)
![Shell](https://img.shields.io/badge/language-shell-blue.svg)
![License](https://img.shields.io/github/license/interl1nk/freelog)
![Contributors](https://img.shields.io/badge/contributors-welcome-orange)
![Issues](https://img.shields.io/github/issues/interl1nk/shellog)
![Forks](https://img.shields.io/github/forks/interl1nk/shellog?style=social)
![Shell Version](https://img.shields.io/badge/shell-%3E%3D%204.0-brightgreen)


---

### How to run

#### Unix/Linux/Windows

Follow these steps:

1. Clone the repository:
```bash
git clone https://github.com/interl1nk/shellog.git
```

2. Import main file shellog.sh:
```bash
source ./shellog.sh
```

3. Define logs:
```bash
log INFO "This is an info message"
log ALERT "This is an alert message"
log ERROR "This is an error message"
```

