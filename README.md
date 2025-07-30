# Hello, I'm Larkin
<a href="https://www.linkedin.com/in/larkin-petrelles-591a05174/" ><img src="https://img.shields.io/badge/-LinkedIn-0072b1?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>

I am a current student working towards completing my bachelors degree in Fall 2025 majoring in CyberSecurity Technology. I have a profound interest in technology, a dedication to solving complex problems, and curiousity to learn more about these systems to ensure our security throughout our ever changing world.

## **Objective**

My journey has led me to develop a passion for cybersecurity.I am eager to transition into this field fully from the finance field. As I'm looking to transition, I welcome any IT role to start my career and gain foundational experience. Whether it is in security or another aspect of IT. 

---

## **IT & Cybersecurity Homelab Projects**

A collection of projects demonstrating hands-on skills in virtualization, networking, and system administration. These projects highlight practical implementations and foundational knowledge in IT and cybersecurity.

---

## **Skills Highlight**

- **Virtualization**:  
  - Set up and managed virtual machines using Oracle VM VirtualBox.  
  - Installed and configured Windows OS for multiple virtual environments.  

- **Active Directory**:  
  - Configured a Windows-based domain controller and linked another VM via Active Directory.  
  - Managed user accounts, permissions, and group policies.  

- **Networking**:  
  - Created and configured VLANs with static IPs for secure and efficient communication.  
  - Integrated VLAN with a secondary VM to enhance connectivity and security.  

- **System Administration**:  
  - Enforced security rules and configurations on linked VMs.  
  - Managed domain connections and monitored resource access.  
  - Configured a Windows Firewall in the domain controller VM using Server Manager.  
  - Defined and managed blocked and allowed ports to enhance network security.  

- **Penetration Testing**:  
  - Conducted network reconnaissance and service enumeration using Zenmap and Nmap tools.  
  - Executed vulnerability scans with OpenVAS to identify critical misconfigurations and CVEs.  
  - Gained unauthorized access through Telnet exploitation and performed file system exploration.  
  - Simulated data exfiltration and documented findings in professional red team reporting formats.  
  - Troubleshot and reconfigured Kali Linux network adapter to restore OpenVAS functionality.

---

## **Projects**

### **1. Domain Controller Setup**
- **Objective**: Configure a Windows domain controller to manage network resources.  
- **Key Steps**:  
  1. Created a VM with Windows Server.  
  2. Installed and set up Active Directory Domain Services.  
  3. Linked a second VM to the domain.  

---

### **2. Network Segmentation with VLANs**
- **Objective**: Isolate and secure network traffic between virtual machines.  
- **Key Steps**:  
  1. Configured VLANs with static IPs.  
  2. Integrated VLAN into a secondary VM.  

---

### **3. Active Directory Integration**
- **Objective**: Enforce domain policies across networked machines.  
- **Key Steps**:  
  1. Created and managed user accounts.  
  2. Applied group policies to impose security rules on the second VM.  

---

### **4. Firewall Configuration on Domain Controller and other VMs connected to Domain Controller**
- **Objective**: Enhance network security by configuring a firewall in the domain controller.  
- **Key Steps**:  
  1. Configured Windows Firewall through Server Manager on the domain controller VM.  
  2. Defined inbound and outbound rules for blocked and allowed ports.  
  3. Tested connectivity and verified that access control policies were functioning as intended.  

---

### **5. Red Team Penetration Testing**
- **Objective**: Perform a simulated penetration test against a vulnerable Linux-based target machine within a controlled network to identify vulnerabilities, exploit services, and exfiltrate sensitive data.  
- **Key Steps**:  
  1. Conducted network reconnaissance using Zenmap to discover live hosts and open ports.  
  2. Performed vulnerability scanning with OpenVAS, identifying misconfigurations and exploitable services (notably Telnet on port 23).  
  3. Exploited the Telnet service using Kali Linux tools to gain shell access to the target machine.  
  4. Navigated the filesystem to locate and exfiltrate data from the `/redteam4/student4` directory, simulating a real-world breach.  
  5. Authored both a System Scan Report and Penetration Test Report, documenting methodology, findings (including CVEs), exploited vector, and remediation strategies.  
  6. Troubleshot network adapter issues in Kali VM and reconfigured settings to restore scanner connectivity for OpenVAS.  

---

## **Tools & Technologies**
- Oracle VM VirtualBox  
- Windows OS & Windows Server  
- Active Directory Domain Services  
- VLAN Configuration  
- Windows Firewall Configuration (Server Manager)  
- Kali Linux (Red Team Tools)  
- Zenmap (Nmap Frontend)  
- OpenVAS (Vulnerability Scanner)  
- Metasploit Framework  
- Telnet, Bash, and Netcat

---

## **Next Steps**
- Automate VM provisioning and configurations using tools like Ansible.  
- Explore intrusion detection systems (IDS) and monitoring tools like Snort or ELK Stack.  
- Expand homelab to include Linux-based systems for cross-platform management and log review.  
- Simulate advanced attack chains with custom payloads and C2 frameworks in red team labs.  
- Deepen exploitation techniques and integrate reporting automation for red team operations.

---

Feel free to explore the repository to learn more about the configurations and scripts used in these projects!




