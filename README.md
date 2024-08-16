<h1>Implementation of ICMP redirect attack on the victim</h1>



<h2>Description</h2>
An error message that a router sends to the IP packet sender is known as an ICMP redirect. Redirects are used by routers to let senders know that their subsequent packets sent to the same destination should use a different router if they think a packet is being routed wrongly. Attackers can alter a victim's routing by using ICMP redirect.

The aim of this operation is to initiate an ICMP redirect attack against the victim, so that the malicious router container (10.9.0.111) will be used as the victim's router when it receives packets addressed to 192.168.60.5. Because the attacker controls the malicious router, the attacker has the ability to intercept packets, modify them, and then send the updated packets.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Python</b> 
- <b>Ununtu 20.04 VM</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)




