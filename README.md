<h1>ICMP Redirect Attack Lab</h1>

<body>
    <p>
       An ICMP redirect is an error message issued by a router to the sender of an IP packet, indicating that the packet is being routed inefficiently. The purpose of this message is to inform the sender to use a different router for future packets destined for the same address. However, ICMP redirects can be exploited by attackers to manipulate a victim’s routing table, redirecting their traffic through a malicious router.

The goal of this task is to execute an ICMP redirect attack, forcing the victim to route packets intended for 192.168.60.5 through a compromised router at 10.9.0.111, controlled by the attacker. Since the attacker has control over this router, they can intercept, modify, and forward the victim’s packets, effectively performing a Man-in-the-Middle (MITM) attack. This allows the attacker to monitor, alter, or inject malicious content into the communication flow, potentially compromising the integrity and confidentiality of the transmitted data.
    </p>
    <p>
        In this lab, students will conduct several attacks on TCP. This lab covers the following topics:
    </p>
    <ul>
        <li> The IP and ICMP protocols</li>
        <li> ICMP redirect attack</li>
        <li> Routing</li>
        
    </ul>
</body>

![image](https://github.com/user-attachments/assets/5373e937-1c12-4639-89e4-bb971edeeb54)



<h2>Languages and Utilities Used</h2>

- <b>Python</b> 
- <b>Ubuntu 20.04 VM</b>

<h2>Environments Used </h2>

- <b>Windows 11 Home</b> 

<h2>Program walk-through:</h2>

- <b> Task 1: Launching ICMP Redirect Attack</b></br>
- <b> Task 2: Launching the MITM Attack</b>





