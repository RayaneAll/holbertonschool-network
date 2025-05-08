# Networking Basics #1  

## Description  
This project is part of the Holberton School curriculum, focusing on foundational networking concepts. It introduces key topics such as localhost, IP addresses, and network interfaces. Through hands-on tasks, you will learn how to manipulate and understand basic networking configurations on an Ubuntu server.  

## Learning Objectives  
By the end of this project, you should be able to explain:  
- What is `localhost`/`127.0.0.1`  
- What is `0.0.0.0`  
- What is `/etc/hosts`  
- How to display your machine’s active network interfaces  

## Resources  
- **Read or watch:**  
    - [What is localhost](https://en.wikipedia.org/wiki/Localhost)  
    - [What is 0.0.0.0](https://en.wikipedia.org/wiki/0.0.0.0)  
    - [What is the hosts file](https://en.wikipedia.org/wiki/Hosts_(file))  
    - [Netcat examples](https://www.digitalocean.com/community/tutorials/how-to-use-netcat)  
- **Commands to explore:**  
    - `ifconfig`  
    - `telnet`  
    - `nc`  
    - `cut`  

## Requirements  
- Use allowed editors: `vi`, `vim`, `emacs`  
- All files will be interpreted on Ubuntu 22.04  
- All files must end with a new line  
- A `README.md` file is mandatory  
- Bash scripts must be executable and pass Shellcheck (version 0.7.0) without errors  
- The first line of all Bash scripts must be `#!/usr/bin/env bash`  
- The second line of all Bash scripts must describe the script’s functionality  

## Tasks  

### 0. Change your home IP  
Write a Bash script to configure an Ubuntu server so that:  
- `localhost` resolves to `127.0.0.2`  
- `facebook.com` resolves to `8.8.8.8`  

**File:** `0-change_your_home_IP`  

### 1. Show attached IPs  
Write a Bash script to display all active IPv4 IPs on the machine.  

**File:** `1-show_attached_IPs`  

### 2. Port listening on localhost  
Write a Bash script to listen on port `98` on `localhost`.  

**File:** `2-port_listening_on_localhost`  

## Repository  
- **GitHub Repository:** `holbertonschool-network`  
- **Directory:** `basics_1`  

Enjoy learning and debugging networking concepts!  