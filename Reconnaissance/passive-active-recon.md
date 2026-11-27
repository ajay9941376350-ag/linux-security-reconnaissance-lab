🔎 Reconnaissance Techniques

1. Introduction

Reconnaissance is the first phase of a cybersecurity assessment. It involves collecting information about a target to understand its digital presence and potential security exposure.

Reconnaissance is generally classified into two types:

1. Passive Reconnaissance
2. Active Reconnaissance

2. Passive Reconnaissance

Passive reconnaissance involves gathering publicly available information without directly interacting with the target's systems.

Examples

- Search engine research.
- Public domain information.
- Public DNS records.
- Public company websites.
- Publicly available documentation.

Advantages

- Low interaction with target systems.
- Helps understand public information exposure.
- Useful during the initial assessment phase.

3. Active Reconnaissance

Active reconnaissance involves directly interacting with a target system to collect technical information.

Examples

- Authorized network discovery.
- Port scanning.
- Service identification.
- Network enumeration.

Advantages

- Provides technical details about accessible services.
- Helps identify exposed network resources.
- Supports security assessment activities.

Important: Active reconnaissance must only be performed on systems owned by you or where explicit authorization has been provided.

4. Passive vs Active Reconnaissance

Passive Reconnaissance| Active Reconnaissance
Uses publicly available information| Interacts directly with target systems
No direct probing| Involves direct requests or probes
Generally lower detection risk| May be detected by monitoring systems
Example: Public DNS lookup| Example: Authorized Nmap scan

5. DNS Information Gathering

DNS stands for Domain Name System.

It translates domain names into IP addresses so that computers can locate services on a network.

Important DNS Record Types

Record| Purpose
A| Maps a domain to an IPv4 address
AAAA| Maps a domain to an IPv6 address
MX| Identifies mail servers
NS| Identifies authoritative name servers
CNAME| Defines an alias for another domain
TXT| Stores text information, often used for verification and email security

6. Useful DNS Commands

Command 1: nslookup

nslookup example.com

Purpose: Retrieves DNS information for a domain.

Command 2: dig

dig example.com

Purpose: Queries DNS servers and displays DNS response information.

Command 3: whois

whois example.com

Purpose: Retrieves available domain registration information, depending on registry access and privacy settings.

Use appropriate public domains and follow applicable terms and policies.

7. Network Enumeration

Network enumeration is the process of identifying available hosts, services, and network resources in an authorized environment.

It can help security professionals understand the network's structure and identify exposed services.

Common Information Collected

- Host information.
- IP addresses.
- Open ports.
- Running services.
- Network configuration.

8. Security Considerations

- Perform active reconnaissance only with permission.
- Do not scan unauthorized public systems.
- Avoid collecting private or sensitive information.
- Keep records of authorized testing activities.
- Follow responsible disclosure practices.

9. Learning Outcomes

After studying reconnaissance, I understand:

1. The meaning of reconnaissance.
2. The difference between passive and active reconnaissance.
3. DNS and its common record types.
4. Basic domain information gathering commands.
5. The purpose of network enumeration.
6. The importance of authorization in security testing.

10. Conclusion

Reconnaissance plays an important role in cybersecurity assessments. Passive and active techniques help security professionals understand the information exposure and technical environment of a target.

Understanding DNS and network enumeration provides a foundation for further security testing.

Author: Ajay M.
Project: Linux Security & Reconnaissance Lab
