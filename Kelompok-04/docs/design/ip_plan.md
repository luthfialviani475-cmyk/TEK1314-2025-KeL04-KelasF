# IP Address Plan - Kelompok 4 Siber (Data Integrity Shield)

## Network Information

- **Subnet** : 192.168.4.0/24  
- **Subnet Mask** : 255.255.255.0  
- **Core Switch / Gateway** : 192.168.4.1  
- **Usable IP Range** : 192.168.4.1 - 192.168.4.254  
- **Broadcast Address** : 192.168.4.255  

---

## Attacker Nodes

| Hostname   | Role     | IP Address      | Operating System |
|------------|----------|----------------|------------------|
| attacker-1 | Attacker | 192.168.4.100  | Kali Linux       |
| attacker-2 | Attacker | 192.168.4.200  | Kali Linux       |

---

## Target Nodes

| Hostname           | Role              | IP Address      | Operating System      |
|--------------------|-------------------|----------------|-----------------------|
| target-ubuntu      | Web Server        | 192.168.4.20   | Ubuntu Server CLI     |
| target-metasploit  | Vulnerable Server | 192.168.4.30   | Metasploitable        |

---

## Monitoring Node

| Hostname   | Role        | IP Address     | Operating System |
|------------|------------|---------------|------------------|
| monitor-k4 | IDS / SIEM | 192.168.4.5   | Security Onion   |
