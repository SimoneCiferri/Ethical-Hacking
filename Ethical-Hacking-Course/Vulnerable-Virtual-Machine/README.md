# ⚠️ Vulnerable Virtual Machine

This subfolder contains a custom-designed vulnerable virtual machine (VM) created by our team as part of the Ethical Hacking exam. The team members are Simone Ciferri (me), Matteo Concutelli, Giorgio Pesce and Adele Mussari. The VM is intentionally configured with various vulnerabilities to simulate real-world scenarios, providing a hands-on experience in identifying and exploiting security weaknesses.

## Overview

The vulnerable VM is based on **Ubuntu Server 20.04 LTS 64-bit** and exposes several services, some of which contain hidden vulnerabilities that can be exploited to gain local access. Additionally, the VM offers multiple ways for a local user to escalate privileges and obtain root access. The vulnerabilities introduced in the VM are realistic, meaning they could be found in real systems.

### Services Installed

- **HTTP Server**
- **FTP Server**
- **SMB Server**
- **SSH Server**

### Vulnerability Paths

The VM provides three distinct paths (easy, medium, hard) to obtain local access and escalate privileges to root. Each path requires the attacker to first gain local access and then escalate privileges to root, offering challenges for different skill levels.

### Usage Instructions

1. **Setup:**
   - Import the VM into VirtualBox virtualization software.
   - Ensure the network settings allow for connectivity to the exposed services.

2. **Penetration Testing:**
   - Begin by enumerating the services running on the VM.
   - Identify and exploit vulnerabilities to gain local access.
   - Once local access is obtained, escalate privileges to root using the various provided paths.

3. **Learning Outcomes:**
   - Understand the importance of securing exposed services.
   - Practice identifying and exploiting common vulnerabilities.
   - Gain experience in privilege escalation techniques.

### Realism and Practicality

The vulnerabilities introduced in this VM are designed to be realistic and could be found in real-world systems. This approach ensures that the skills gained from practicing with this VM are applicable in real penetration testing scenarios.

## ❗ Disclaimer

All resources in this repository are for educational purposes only. Use the provided tools and machines responsibly and only in environments where you have explicit permission to test. Unauthorized hacking or penetration testing is illegal and unethical.

Happy Hacking!
