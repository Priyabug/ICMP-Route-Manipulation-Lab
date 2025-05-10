# 🔄 ICMP Redirect Lab: Understanding Routing Path Manipulation

---

## 🧾 Overview  
An ICMP Redirect is a control message issued by a router to inform a host that there is a more efficient route available for a given destination. This mechanism helps optimize routing by advising hosts to update their routing tables accordingly.

While intended for efficiency, improper configuration or lack of filtering can lead to unintended consequences, such as rerouting traffic through untrusted paths.

---

## 🎯 Objective  
The purpose of this lab is to demonstrate how ICMP Redirect messages can alter the routing behavior of a host in a local network.

Specifically, the goal is to configure a scenario where a device is instructed to forward packets destined for `192.168.60.5` through an alternate router located at `10.9.0.111`. This router is under observation for educational purposes to understand:

- ✅ How routing tables can be influenced via ICMP  
- ✅ How network traffic can be transparently forwarded  
- ✅ How communication paths may be modified without alerting the sender or receiver  
- ✅ How third-party systems can monitor the flow of traffic in such scenarios  

---

## 📘 Topics Covered

- 📌 Understanding IP and ICMP Protocols  
- 📌 Route Management via ICMP Redirect Messages  
- 📌 Dynamic Routing Table Updates  
- 📌 Traffic Redirection in Local Networks  

---

## 🧪 Tools and Technologies

- 🐍 **Python**  
- 🖥 **Ubuntu 20.04 Virtual Machine**  
- 💻 **Windows 11 Home (Host Environment)**  

---

## 🛠️ Lab Tasks

### 🔹 Task 1: Send ICMP Redirect Message to Influence Routing  
Simulate an ICMP redirect to guide traffic through the chosen router.

### 🔹 Task 2: Monitor Redirected Traffic  
Inspect how the traffic is routed and analyze the modified communication path.

---

## 📌 Key Learning Outcomes

By the end of this lab, participants will:

- ✔ Understand the role of ICMP Redirects in network communication  
- ✔ Recognize how routing behaviors can be influenced within a subnet  
- ✔ Gain hands-on experience with packet crafting and routing diagnostics  
- ✔ Learn the importance of securing routing protocols and filtering control messages  

---

## ✅ Conclusion  
This lab emphasizes the importance of cautious network configuration and control message handling. ICMP redirects, though helpful in theory, can lead to misrouted traffic if not properly managed. Network administrators must implement appropriate safeguards, such as filtering redirect messages from untrusted sources and enforcing strict routing policies.

🔒 **Understanding network behavior is the first step toward building secure and resilient systems.**
