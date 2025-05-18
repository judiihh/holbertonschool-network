# 🖧 Network Basics #1

This project focuses on basic networking concepts and operations in Linux/Ubuntu systems.

## 🎯 Learning Objectives
* Understanding localhost and IP addresses (127.0.0.1, 0.0.0.0)
* The purpose and structure of /etc/hosts file
* How to display active network interfaces

## 📝 Tasks

### 0️⃣ Change your home IP
A Bash script that configures an Ubuntu server with specific requirements:
- localhost resolves to 127.0.0.2
- facebook.com resolves to 8.8.8.8

The script modifies the /etc/hosts file to implement these changes.

### 1️⃣ Show attached IPs
A Bash script that displays all active IPv4 IPs on the machine.

### 2️⃣ Port listening on localhost
A Bash script that listens on port 98 on localhost and prints received text.

## 📋 Requirements
- All scripts must be executable
- All scripts must pass Shellcheck without errors
- All scripts must have the shebang line `#!/usr/bin/env bash`
- All scripts must include a comment explaining their purpose 