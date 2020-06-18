# CISSP-Mnemonics

Asymmetric Encryption:  Also known as public key encryption (public key can be publicized without compromising security)
  * Remember: DEREK   Diffie-Hellman, El-Gamal, RSA, Elleptical Curve Cryptography (ECC), Knapsack
--------------------------------------------------------------------------------------------------------------------------
Symmetric Encryption:  Also known as shared key or secret key encryption.  Private key can be sent out-of-band
  * Remember: 23BRAIDS   TwoFish, 3DES, Blowfish, RC5, AES, IDEA, DES, SAFER
--------------------------------------------------------------------------------------------------------------------------
Hash Functions: *think of the doctor: SHA HAVAL, MD

--------------------------------------------------------------------------------------------------------------------------  
OSI Model:  Physical (Level 1), Datalink, Network, Transport, Session, Presentation, Application (Level 7)
  * Remember: "Please Do Not Throw Sausage Pizza Away" (going up)
               "All People Seem To Need Data Processing" (going down)
--------------------------------------------------------------------------------------------------------------------------
Risk Management
  ALE = ARO x SLE   *think  "Ale causes arousle" 
  SLE = AV x EF
  
--------------------------------------------------------------------------------------------------------------------------  
4 D's of Physical Security: Deter → Deny → Detect → Delay

--------------------------------------------------------------------------------------------------------------------------
Multi-Factor Authentiation:  Something you know, something you have, something you are

--------------------------------------------------------------------------------------------------------------------------
TCP Header Flags:  URG  ACK  PSH  RST  SYN  FIN
  *think "Unskilled Attackers Pester Real Security Folks"
  
--------------------------------------------------------------------------------------------------------------------------
Confidentiality and Integrity Models
Simple Property: for read "Reading is simpler than writing."
Star Property:  for write  "It's written in the stars."

Biba and Clark Wilson have the letter "i" in them, so Integrity Models
Bell-LaPadula is confidential:  No read up and No write down.  "WURD"  
  * Remember:  You don't want someone read up above their security level
  
Biba will be opposite 
  * Remember: you can't write up as it would "pollute" the data
--------------------------------------------------------------------------------------------------------------------------             
System Security Modes (for systems that process classified data, what each user is required to have)

  * Dedicated mode - have a security clearance, access approval, and valid need to know for **ALL** data processed by Dedicated system 
  
  * System High mode - have a security clearance and access approval for **ALL** data processed by System high mode system.  Also, valid need to know for data **PERSONALLY** accessed.
  
  * Compartmented mode - have a security clearance for **ALL** data processed by compartmented mode system.  Also, access approval and a valid need to know for data **PERSONALLY** accessed.
  
  * Multilevel mode - have a security clearance, access approval, and valid need to know for data **PERSONALLY** accessed.  (Requirements are enforced primarily by hardware or software on the system, not by limiting physical access)
          
