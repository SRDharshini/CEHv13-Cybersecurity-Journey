					                                           MODULE – 1
  			                                    INTRODUCTION TO ETHICAL HACKING
                                            


•	WHAT IS HACKING ?

-	Gaining unauthorized access to computer system.
-	Exploiting system vulnerabilities & compromising security.


ATTACK = VULNERABILITY + METHOD + GOAL

	ATTACK – An attempt to harm, break, steal or disrupt a computer system, network or data.
	VULNERABILITY – A flaw or weak point in a system or person that can be misused
Ex : Back door of the house is unlocked and no security camera is available.
	METHOD – The technique used to reach the goal (Phishing, Scanning, Malware, Brute force etc. <= which we’ll discuss later).
Ex : Enter the back door at midnight.
	GOAL – The final result is the attacker is trying to get access (to steal, damage, access or disrupt)
Ex : Robber wants to steal the gold jewellery from the unlocked house.




•	ADDITIONAL TERMINOLOGIES

	EXPLOIT – The action or code that takes advantage of a vulnerability.
Ex : Opens the unlocked back door and sneaks inside.
	PAYLOAD – The actual malicious content delivered during an attack (like malware, script, command, or backdoor).
Ex : Uses a crowbar/hammer to break the cupboard and grab the jewellery.

FLOW OF PROCESS : Vulnerability -> Method -> Exploit -> Payload -> Gain Access




•	FEW MORE TERMS 

	HACK VALUE – The worth or attractiveness of a target for an attacker (Ex : money, fame etc).
Ex : Gold or Cash – is the hack value for the robber.
	ZERO DAY – A new vulnerability that no one knows or fixed yet, even the software developer. Attackers discovered and abused it before a patch exist
Ex : A secret loophole in a lock design that the lock company hasn’t discovered yet – only the robber knows it, so he can open the door with out the key.




•	HACKERS 

	UNETHICAL HACKER – A person who breaks into the system to find, use or expose weakness without proper authorization illegally (also known as Hacker / Black-hat Hacker).
	ETHICAL HACKER   – A legal, permission-based hacker who finds security flaws to help in fixing them.




•	TYPES OF HACKERS

1.	BLACK-HAT         – 	Hacks illegally to steal, damage or cause harm.

2.	WHITE-HAT 		    –  	Hacks legally with permission to protect and fix  systems.


3.	GREY-HAT		      –  	Hacks without permissions, but usually not for harm – may report the flaw later.

4.	SUICIDE-HACKERS   –	  Individual who aims to bring down critical infrastructure for a cause and are not worried about facing punishment.


5.	SCRIPT KIDDIES 	  – 	Beginners who use ready-made tools without deep knowledge.

6.	CYBER TERRORISTS	– 	Attack digitally to create fear, disruption, or damage for political or ideological purposes.


7.	HACKTIVISTS	      – 	Hack to support a cause or ideology, not mainly for money.

8.	GOVERNMENT-SPONSORED HACKERS – Hackers funded by a country to attack or spy on other nations.




•	FOR YOUR ADDITIONAL KNOWLEDGE 

	ESPIONAGE	             –     Secretly stealing information for advantage.
	EAVESDROPPING          –     Secretly listening to communication.
	SABOTAGE 	             –     Destroying or disrupting a system or resource intentionally.




•	PHASES OF HACKING

              INFORMATION GATHERING / RECONNAISANCE / FOOTPRINTING
				                              |
			                             SCANNING
				                              |
			                           GAINING ACCESS
				                              |
    		                       MAINTAINING ACCESS
				                              |
                           	CLEARING TRACES / REPORTING


                            
1.	INFORMATION GATHERING        -	The attacker gathers information about the target system, network, or organization.
2.	SCANNING			               -	In this phase, the attacker scans the target to identify open ports, services, operating systems, and vulnerabilities.
3.	GAINING  ACCESS              -	The attacker exploits identified vulnerabilities to gain access to the target system.
4.	MAINTAINING ACCESS	         -	After gaining access, the attacker attempts to maintain persistent access for future exploitation.
5.	CLEARING TRACES/ REPORTING	 -  (*)  Attack – Clears the traces (ex : logs).
                                    (*) Ethical hacker – Provides the report of assessment done.




•	CYBER KILL CHAIN

-	It’s a concept developed by LOCKHEED MARTIN to describe the stages of a cyberattack.


		                            RECONNAISANCE
				                              |
			                          WEAPONIZATION
				                              |      
		                               DELIVERY
				                              |
              			             EXPLOITATION
				                              |
		                             INSTALLATION
				                              |
		                           COMMAND & CONTROL
				                              |
  				                    ACTION ON OBJECTIVES



1.	RECONNAISANCE			      -       Gathering information about the target before launching an attack.
2.	WEAPONIZATION			      -       Creating a malicious payload or exploit to attack the target.
3.	DELIVERY				        -       Transmitting the malicious payload to the victim system.
4.	EXPLOITATION			      -       Exploiting a vulnerability to execute malicious code.
5.	INSTALLAION			        -       Installing malware or backdoors on the target system.
6.	COMMAND & CONTROL		    -       Establishing remote communication with the compromised system. 
7.	ACTION ON OBJECTIVES		-       Performing the intended attack activities such as data theft or system disruption.




•	ELEMENTS OF INFORMATION SECURITY

1.	CONFIDENTIALITY		-	  Keep data secret, reveal only for intended user.
2.	INTEGRITY			    -	  Data should not be changed or tampered.
3.	AVAILABILITY		  -	  Data / System should be accessible whenever needed.
4.	AUTHENTICATION		-	  Confirm that the user or data is genuine using credentials. (ex : user name & password).
5.	AUTHORIZATION		  -	  Give access / permissions based on their roles.
6.	NON-REPUDIATION		-	  A user can’t deny the actions done by them later (ex : any bank transaction actually done by them through their account with their credentials).


•	INFORMATION SECURITY vs CYBER SECURITY

o	Information security – Securing information from both physical & digital threats.
o	Cyber security	     – Securing information only from digital threats. It’s a part of Information security.




•	LINUX BRIEF

-	Linux is an open-source and Unix-based operating system widely used in servers, cybersecurity, cloud computing, networking, and ethical hacking environments. It provides strong security, stability, flexibility, and command-line control, making it one of the most preferred operating systems for cybersecurity professionals and system administrators.

-	Essential Linux commands are discussed in the sub-module named [] – PLEASE DO REFER THAT FOR BASIC UNDERSTANDING OF ESSENTIAL LINUX COMMANDS.




•	PRIVACY & ANOMITY TECHNOLOGIES

1.	VPN
2.	PROXY
3.	TOR BROWSER

NOTE : PURPOSE OF IP – Communication & Identification (IP – Internet Protocol).

1)	VPN (Virtual Private Network) 

o	VPN creates a private encrypted tunnel so no one (ISP / Hacker) can see your data, and it also changes(spoofs) / hides your IP.
o	Note these changes is ONLY FOR PUBLIC IP NOT FOR PRIVATE IP.
o	Some VPN providers claim to follow a “no-log policy,” meaning they do not store user activity logs.
TOOL : PROTON VPN (Try out this tool t0 better understanding of VPN).


2)	PROXY
      
o	A proxy is an intermediary server that forwards your request & can hide your IP from the destination.
TOOL : CROXYPROXY (Try out this tool to get better understanding of PROXY).


3)	TOR BROWSER (THE ONION ROUTING)

o	TOR is a privacy network that hides your identity by routing your traffic through multiple volunteer servers & encrypting the traffic in multiple layers.
BROWSER : TOR (Try tor browser to get better understanding).




•	DARK WEB

-	It’s a hidden part of the internet that can be accessed using special tools like the TOR Browser, not regular browsers.
-	DARK WEB doesn’t mean always illegal, but often misused for illegal activities.


	INTERNET = SURFACE WEB + DEEP WEB + DARK WEB

	SURFACE WEB
•	Facebook, Google, Youtube etc.
•	Legal.
•	Only 4% of Internet. (Approximately).


	DEEP WEB
•	Bank accounts, Private cloud storage, Government entities etc. 
•	Underwater but legal.
•	90% of Internet. (Approximately).

	DARK WEB
•	Used Illegally.
•	6% of Internet. (Approximately).


			
