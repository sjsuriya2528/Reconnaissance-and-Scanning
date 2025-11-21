# **Task 1 – Reconnaissance & Scanning**

This task involves gathering information about a target network using basic reconnaissance tools in Kali Linux. Tools like **Netdiscover** and **Nmap** are used to identify live hosts, open ports, running services, and OS details.

---

## 🔍 **Tools Used**

* **Netdiscover** – To find live hosts in the network
* **Nmap** – To scan ports, services, and OS information

---

## 🛠 **Commands Executed**

### **1️⃣ Network Discovery (Netdiscover)**

```
sudo netdiscover -r  <ip>
```

Used to scan the local network and identify active hosts along with their MAC addresses and vendors.

---

### **2️⃣ Basic Nmap Scan**

```
nmap <target-ip>
```

### **3️⃣ Service & Version Detection**

```
nmap -sV <target-ip>
```

### **4️⃣ Operating System Detection**

```
nmap -O <target-ip>
```

### **5️⃣ Aggressive Scan (OS + services + scripts)**

```
nmap -A <target-ip>
```

---

## 📌 **What I Observed**

* Identified active hosts in the network using **Netdiscover**
* Found open ports and services using **Nmap**
* Detected the Operating System of the target machine
* Gathered useful information for further analysis in penetration testing

---

## ⚠️ **Note**

This reconnaissance was performed only on systems where I have permission. Unauthorized scanning is illegal.

---
