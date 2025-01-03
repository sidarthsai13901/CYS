# Soc Analyst 1

Hash Values 
MD5( Message Digest,defined by RFC 1321) 128-BIT HASH
VALUE .MD5 HASHES ARE NOT CONSIDERRED CRYPTOGRAPHICALLY SECURE 
SHA-1 SHA-1 TAKES AN INPUT AND PRODUCES A 160-BIT HASH VALUE STRING AS A 40 DIGIT HEXADECIMAL NUMBER 
Security professionals usually use the hash values to gain insight into a specific malware sample, 
a malicious or a suspicious file, and as a way to uniquely identify and reference the malicious artifact.

Virus Total Metadefender Cloud-OPWAT
As you might have noticed, it is really easy to spot a malicious file if we have the hash in our arsenal.
However, as an attacker, modifying a file by even a single bit is trivial,
which would produce a different hash value. 
With so many variations and instances of known malware or ransomware,
threat hunting using file hashes as the IOC (Indicators of Compromise) can become difficult.

IP Adddress 
An IP address is used to identify any device connected to a network.
From a defense standpoint, knowledge of the IP addresses an adversary uses can be valuable. 
A common defense tactic is to block, drop, or deny inbound requests from IP addresses on your parameter or external firewall. 

Fast Flux is a DNS technique used by botnets to hide phishing, web proxying, malware delivery, and malware communication activities behind compromised hosts acting as proxies. 
The purpose of using the Fast Flux network is to make the communication between malware and 
its command and control server (C&C) challenging to be discovered by security professionals. 
https://unit42.paloaltonetworks.com/fast-flux-101/

Domain Names can be a little more of a pain for the attacker to change as they would most likely need to purchase the domain, register it and modify DNS records. 
Unfortunately for defenders, many DNS providers have loose standards and provide APIs to make it even easier for the attacker to change the domain.
