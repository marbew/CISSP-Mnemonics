# CISSP-Mnemonics and Tips


##### Asymmetric Encryption  
> Also known as public key encryption (public key can be publicized without compromising security)<br>
  Remember: <ins>DEREK</ins>   
  * <ins>D</ins>iffie-Hellman/<ins>D</ins>SA 
  * <ins>E</ins>l-Gamal 
  * <ins>R</ins>SA
  * <ins>E</ins>lleptical Curve Cryptography (ECC)
  * <ins>K</ins>napsack
--------------------------------------------------------------------------------------------------------------------------
##### Symmetric Encryption  
> Also known as [s]hared key or [s]ecret key encryption.  Private key can be sent out-of-band<br>
  Remember: <ins>23BRAIDS</ins>   
  * <ins>2</ins>TwoFish
  * <ins>3</ins>DES
  * <ins>B</ins>lowfish
  * <ins>R</ins>C5
  * <ins>A</ins>ES
  * <ins>I</ins>DEA
  * <ins>D</ins>ES
  * <ins>S</ins>AFER
--------------------------------------------------------------------------------------------------------------------------
##### Hash Functions: 
> Think of the good doctor: <ins>SHA HAVAL, MD</ins>

--------------------------------------------------------------------------------------------------------------------------  
##### OSI Model:  
> Physical (Level 1), Datalink, Network, Transport, Session, Presentation, Application (Level 7)<br>
  Remember: 
  * "Please Do Not Throw Sausage Pizza Away" (going up)
  * "All People Seem To Need Data Processing" (going down)
--------------------------------------------------------------------------------------------------------------------------
##### Risk Management
  * ALE = ARO x SLE   *think  "Ale causes arousle" 
  * SLE = AV x EF     *think Italian magician (or Mario) saying "I've got something up my sleav-ef"
  
--------------------------------------------------------------------------------------------------------------------------  
##### 4 D's of Physical Security: 

> [D]eter → [D]eny → [D]etect → [D]elay

--------------------------------------------------------------------------------------------------------------------------
##### Multi-Factor Authentiation:  

> Something you <ins>know</ins>, something you <ins>have</ins>, something you <ins>are</ins>

--------------------------------------------------------------------------------------------------------------------------
TCP Header Flags:  **URG  ACK  PSH  RST  SYN  FIN**
  *think "<ins>U</ins>nskilled <ins>A</ins>ttackers <ins>P</ins>ester <ins>R</ins>eal <ins>S</ins>ecurity <ins>F</ins>olks"
  
--------------------------------------------------------------------------------------------------------------------------
Confidentiality and Integrity Models
* <ins>Simple</ins> Property: for read "Reading is simpler than writing."
* <ins>Star</ins> Property:  for write  "It's written in the stars."

Biba and Clark Wilson have the letter **i** in them, so Integrity Models
Bell-LaPadula is confidential:  No read up and No write down.  (said another way, **Bell is WURD**) 
  * Remember:  You don't want someone read up above their security level
  
Biba will be opposite:  No read down and no write up  (**Biba is NO WURD**) 
  * Remember: you can't write up as it would "pollute" the data
--------------------------------------------------------------------------------------------------------------------------             
##### System Security Modes 

>that is, for systems that process classified data, what each user is required to have

  * <ins>Dedicated mode</ins> - have a security clearance, access approval, and valid need to know for **ALL** data processed by Dedicated system 
  
  * <ins>System High mode</ins> - have a security clearance and access approval for **ALL** data processed by System high mode system.  Also, valid need to know for data **PERSONALLY** accessed.
  
  * <ins>Compartmented mode</ins> - have a security clearance for **ALL** data processed by compartmented mode system.  Also, access approval and a valid need to know for data **PERSONALLY** accessed.
  
  * <ins>Multilevel mode</ins> - have a security clearance, access approval, and valid need to know for data **PERSONALLY** accessed.  (Requirements are enforced primarily by hardware or software on the system, not by limiting physical access)
--------------------------------------------------------------------------------------------------------------------------
Retinal scan is most intrusive to privacy  (*think ret-inal = anal, intrusive!  It's inappropriate, but you remember it!) 

Using a condom is **due care**, taking the steps to decide whether to use the condom is **due diligence**. (Source: Luke Ahmed)

**Entrapment** is when law enforcement persuades someone to commit a crime that they otherwise would not have committed. **Enticement** is when the person would have committed (or intended to commit the crime) anyway.   (Source: Sybex OSG 7th Ed.)
  (Think: You can entice a criminal, but only entrap an otherwise honest person.)

--------------------------------------------------------------------------------------------------------------------------
##### Network Topologies
* <ins>ring</ins> topology is most **secure**. (if it is dedicated with no external connections)
* <ins>bus</ins> topology is cheap, easy to set up, and good for small LANs. (If the single line of cable breaks, the network is down, devices can see others' packets)
* <ins>star</ins> topology is most **common**.  (more resilient than two above if a device fails, but still dependent on central switch or hub)
* <ins>mesh</ins> topology is best for **redundancy**.  (with **Full mesh** if a node fails, network traffic can be directed to any of the other nodes) 
              
Note: There is also **partial mesh**, some nodes are organized in a full-mesh scheme, but others are connected to only one or two in the network. Partial mesh topology is commonly found in peripheral networks connected to a full meshed backbone network.)
   

--------------------------------------------------------------------------------------------------------------------------
##### DR Recovery Sites 

* <ins>Hot site</ins>- Organization needs site activation **immediately**; ready to go

* <ins>Warm site</ins>- Organization has alt. site with equipment and data circuits available but nothing is connected and everything needs to be set up.  The main requirement in bringing a warm site to full operational status is the transportation of appropriate backup media to the site and restoration of critical data on the standby servers.  This can take from a a **few hours to a couple days.**  (Sybex says 12 hrs., other sources 24-48 hrs.)

* <ins>Cold site</ins>- Organization has alternate site with power and cooling, but equipment needs to be ordered and may take a **few days to several weeks** to arrive, be configured, and then restoration of backup media.
          
--------------------------------------------------------------------------------------------------------------------------
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
          
#### WTFPL License

> **Disclaimer:** Some of my mnemonics and tips are my own creations.  Some are freely given on Reddit.  I strive to give credit to original source when and where applicable.

This program is free software. It comes without any warranty,
to the extent permitted by applicable law.
You can redistribute it and/or modify it under the terms of the
Do What The Fuck You Want To Public License,
Version 2, as published by Sam Hocevar.
See http://www.wtfpl.net/ for more details.

   DO WHAT THE FUCK YOU WANT TO PUBLIC LICENSE
                   Version 2, December 2004
 
Copyright (C) 2004 Sam Hocevar <sam@hocevar.net>
