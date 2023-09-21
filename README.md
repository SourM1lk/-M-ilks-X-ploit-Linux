# (M)ilks (X)ploit Linux

## Overview

(M)ilks (X)ploit Linux is a bash script designed to streamline the setup process for turning a fresh MX Linux installation into a versatile environment for penetration testing and related activities. It automates the installation of essential tools, terminal configurations, and repository setups, allowing you to focus on your security testing tasks.

## Features

- **Terminal Enhancements:** (M)ilks (X)ploit Linux installs Guake Terminal, Zsh, Oh My Zsh, and Tmux with preconfigured settings.

- **Tool Installations:** The script installs a selection of commonly used security tools from both the default repositories and the Kali Linux repository.

Current list of Tool Installations:
```shell
    smbclient
    netcat-traditional
    nmap
    nmap-common
    john
    python3-impacket
    impacket-scripts
    wordlists
    seclists
    dirsearch
    metasploit-framework
    bloodhound
    bloodhound.py
    sqlmap
    ffuf
    wfuzz
    dnsrecon
    crackmapexec
    evil-winrm
    hashcat
```

- **Kali Linux Integration:** It adds the Kali Linux repository to your package sources and installs Kali tools, expanding your toolkit. However, 

To install tools from the Kali repo, run the following command:
```shell
    sudo apt install TOOL -y -t kali-rolling
```

- **Customization:** The script is designed for easy customization. You can expand the list of default tools or Kali tools to suit your specific needs. Just fork!

## Usage

1. Clone this repository to your MX Linux machine:

```shell
   git clone https://github.com/SourM1lk/-M-ilks-X-ploit-Linux.git
```

2. Navigate to the directory containing the script:

```shell
   cd -M-ilks-X-ploit-Linux
```

3. Make the script executable:

```shell
    chmod +x install.sh
```

4. Run the script:

```shell
    sudo ./install.sh
```

5. Follow the on-screen instructions and prompts to complete the installation process.

6. After the script finishes, you'll have a fully configured penetration testing environment.



