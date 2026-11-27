🛡️ Linux Security & Reconnaissance Lab

Cybersecurity | Linux | Network Security | Security Tools

A beginner-friendly cybersecurity project focused on understanding Linux fundamentals, reconnaissance techniques, network enumeration, and essential security tools through controlled practical exercises.

---

🎯 Project Objectives

- Understand Linux commands, files, directories, and permissions.
- Learn Linux users, groups, and process management.
- Understand passive and active reconnaissance.
- Explore DNS and domain information gathering.
- Learn essential cybersecurity tools.
- Perform safe security experiments in an authorized lab environment.

🐧 1. Linux Fundamentals

Linux is an open-source operating system widely used in servers, cloud computing, and cybersecurity.

Essential Linux Commands

Command| Purpose
"pwd"| Display current directory
"ls"| List files and directories
"cd"| Change directory
"mkdir"| Create a directory
"touch"| Create an empty file
"cat"| Display file contents
"cp"| Copy files
"mv"| Move or rename files
"rm"| Remove files
"whoami"| Display current user
"ps"| Display running processes
"chmod"| Change file permissions
"sudo"| Execute authorized administrative commands

🔐 2. Linux File Permissions

Linux uses three main permission categories:

- Owner: The file owner.
- Group: Users belonging to the file's group.
- Others: All other users.

Permission Types

Permission| Meaning| Numeric Value
Read (r)| Read a file| 4
Write (w)| Modify a file| 2
Execute (x)| Execute a file| 1

Example:

"chmod 755 filename"

This grants read, write, and execute permissions to the owner, and read and execute permissions to the group and others.

🌐 3. Reconnaissance

Reconnaissance is the process of collecting information about a target before a security assessment.

Passive Reconnaissance

Collecting publicly available information without directly interacting with the target's systems.

Examples:

- Public domain registration information.
- Search engine information.
- Public DNS records.

Active Reconnaissance

Collecting information through direct interaction with a target system.

Examples:

- Authorized network discovery.
- Port scanning in a controlled lab.
- Service identification.

Important: Active reconnaissance must only be performed against systems for which explicit permission is available.

🔎 4. DNS and Domain Information Gathering

DNS stands for Domain Name System.

It translates domain names into IP addresses.

Useful commands:

nslookup example.com

dig example.com

whois example.com

These commands can help understand DNS resolution and publicly available domain information. Use authorized and appropriate targets.

🧰 5. Essential Cybersecurity Tools

Nmap

A network discovery and security auditing tool used to identify hosts, ports, and services in authorized environments.

Wireshark

A network protocol analyzer used to capture and inspect network traffic.

Burp Suite

A web application security testing platform used to inspect and test HTTP requests and responses.

OWASP ZAP

An open-source web application security testing tool that helps identify potential vulnerabilities.

🧪 6. Controlled Reconnaissance Lab

Lab Objective

To understand basic network discovery and information gathering in a safe and authorized environment.

Lab Activities

1. Review Linux commands.
2. Examine local network configuration.
3. Understand DNS resolution.
4. Explore Nmap in a local or authorized lab.
5. Observe network traffic using Wireshark.
6. Understand web request inspection using Burp Suite.
7. Explore OWASP ZAP using an intentionally vulnerable training application.

Safety Guidelines

- Use only personal or authorized lab systems.
- Do not scan public systems without permission.
- Do not attempt unauthorized access.
- Avoid collecting private information.
- Document findings responsibly.

📋 7. Learning Outcomes

After completing this project, I aim to:

- Understand basic Linux administration.
- Identify common Linux file permissions.
- Explain passive and active reconnaissance.
- Understand DNS and network enumeration.
- Identify the purpose of essential security tools.
- Follow safe and ethical security testing practices.

📚 8. References

- Linux Manual: https://man7.org/linux/man-pages/
- Nmap Documentation: https://nmap.org/book/man.html
- Wireshark Documentation: https://www.wireshark.org/docs/
- Burp Suite Documentation: https://portswigger.net/burp/documentation
- OWASP ZAP Documentation: https://www.zaproxy.org/docs/

---

👨‍💻 Author

Ajay M.
B.E. Computer Science and Engineering

Project Status

Learning and practical documentation in progress.

Learn • Explore • Secure 🛡️
