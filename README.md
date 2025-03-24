# **ICMP Redirect Attack Lab**  

## **Overview**  
An **ICMP redirect** is an error message issued by a router to the sender of an IP packet, indicating that the packet is being **routed inefficiently**. The purpose of this message is to inform the sender to use a **different router** for future packets destined for the same address.  

However, **ICMP redirects** can be **exploited by attackers** to manipulate a victim’s routing table, redirecting their traffic through a **malicious router**.  

---

## **Objective**  
The goal of this lab is to **execute an ICMP redirect attack**, forcing the victim to route packets intended for `192.168.60.5` through a **compromised router** at `10.9.0.111`, which is controlled by the attacker.  

Since the attacker has control over this router, they can:  
✅ **Intercept** the victim’s traffic  
✅ **Modify** or manipulate packets  
✅ **Forward** packets while remaining undetected  
✅ Perform a **Man-in-the-Middle (MITM) attack**  

This allows the attacker to **monitor, alter, or inject malicious content** into the communication flow, potentially **compromising the integrity and confidentiality** of the transmitted data.  

---

## **Topics Covered in This Lab**  
📌 **The IP and ICMP Protocols**  
📌 **ICMP Redirect Attack**  
📌 **Routing**  

Through this lab, students will gain **hands-on experience** in how attackers **exploit ICMP redirects** and understand the **associated risks** in real-world network scenarios.  

---


![image](https://github.com/user-attachments/assets/5373e937-1c12-4639-89e4-bb971edeeb54)



<h2>Languages and Utilities Used</h2>

- <b>Python</b> 
- <b>Ubuntu 20.04 VM</b>

<h2>Environments Used </h2>

- <b>Windows 11 Home</b> 

<h2>Program walk-through:</h2>

- <b> Task 1: Launching ICMP Redirect Attack</b></br>
- <b> Task 2: Launching the MITM Attack</b>




🔥 **Stay vigilant and secure your networks!** 🔥  


