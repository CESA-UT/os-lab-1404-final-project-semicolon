# Sys-Monitor
### CPU & RAM Monitoring Tool for Linux

## 📌 Introduction
`Sys-Monitor` is a Linux command-line monitoring tool that displays real-time information about system resource usage, including CPU and RAM consumption.

This project is developed as the final project for the Operating Systems Lab course.  
The tool is designed to be lightweight, terminal-based, and compatible with standard Linux environments.

---

## ✨ Features
- Displays current CPU usage percentage
- Displays current RAM usage (used / total)
- Shows top processes by CPU usage
- Shows top processes by RAM usage
- Real-time terminal output
- Simple and readable interface
- Supports Linux systems

---

## 🛠 Installation
This project is distributed as a Debian package (`.deb`).

### Prerequisites
Make sure `git` is installed:
```bash
sudo apt install git
```
After downloading the (.deb) file, install it using:
```bash
sudo dpkg -i sys-monitor_1.0_all.deb
```
After installation, the command sys-monitor will be available system-wide.

## ▶️ Usage
To run the system monitor, simply execute:
```bash
sys-monitor
```
```md
The program will display:
- CPU usage percentage
- RAM usage (used / total)
- Top CPU-consuming processes
- Top RAM-consuming processes
```

To exit the program, press:
```text
Ctrl + C
```
## 📖 Manual Page
A complete manual page (man page) is provided for this tool.
After installation, you can access the manual using:
```bash
man sys-monitor
```
The man page includes:
- Command description
- Usage syntax
- Available options
- Practical usage examples


## 📂 Project Structure
```text
.
├── src/
│   └── sys-monitor.sh
├── man/
│   └── sys-monitor.1
├── debian/
│   ├── control
│   ├── install
│   └── manpages
├── README.md
```
## 👥 Team Members
Member 1 – Core implementation
Member 2 – Documentation (README & man page)
Member 3 – Debian packaging
Member 4 – Testing and validation

## 📝 Notes
This project is developed for educational purposes.
The tool follows standard Linux command-line conventions.
Command name, Debian package name, and man page are kept consistent to ensure proper system integration.
