- cybersec involv safety of computer sys which incl
	- tech infra supporting comp sys (network, computer, etc)
	- digital data contained w.in
- IRP must distinguish bw recog/responding to event/cybersec incident
	-COMBE BACK
	- Event
		- observable occurrence in sys/network
		- ex incl user connecting to shared file server, server rec request for web pg, user sending email, firewall blocking connection attempt
		- also incl cybersec chngs that have effect on orgs ops, mission, manuf capabilities, reputation
	- Adverse Event
		- neg consequence
		- sys crash, pkt flood, unauth sys priv use, unauth access to sensitive data, malware execution destroy data
		- incl both 
			- un/intentional events
			- human/env inflicted events
	- Computer Sec Incident
		- adverse events that are
			- computer sec related
			- caused by malicious human intent (not env/indirect human factors like power failure/natural disaster)
		- any violation/imminent threat of computer sec pol, acceptable use policies, standard sec practices
		- ex
			- attacker floods web server w requests > site crash
			- phishing emails, downloading tools infecting computer
			- ransomware data hostage
			- adverse events seemingly harmless as exposing sensitive info to unintended parties bc of careless use practices 

- Steps in Responding to Incident
	1. Preparation
		- prep for incidents
		- assemble key personnel, tools, processes
		- tools/methods adopted in prep
			- vuln assessment software
			- intrusion detection/preventinon app (vuln scanners)
			- anti malware software
			- training for end users/specialists directly involv in response
	2. Detection
		- detect/id incidents
		- recog deviations from normal op
		- eval deviatins
		- classify as acceptable event/problematic cybersec incident
	3. Containment
		- contain incident from spreading
		- allows cybersec response team time to det best approach to eliminate threat
		- technical measures such as isolating network segment, take exposed workstations out of use, remove infected servers from production n rerouting those to backup/failover equip
		- nontech like inform emplee so certain routine op stop
	4. Eradication
		- eradicate threats
		- extract threat, restore affected sys
		- simple like restore infected files w clean backup copies or complex like using specialized software/forensic anal to help decrypt/remove infected files
		- sys logging/network monitoring performed company wide to det if breadth/depth of eradication efforts adequate 
		- sig incident may req sys be rebuilt entirely > crit data loss
	5. Reporting
		- report/comms status
		- to mgmt, IT personnel, affected emplees
		- tailor mssging w only relevant info/nxt steps to each group
	6. Recovery
		- recover/restore normal op
		- phased approach
			- early days on inc overall sec, implement high impact chngs
			- then holistic LT phase that may involve stat chngs, like shift in infra to prevent sim cybersec incidents from reoccurring 
	7. Learning
		- learn/improve
		- senior mgmt n directly affected emplee
			- examine incident
			- understand how it occurred
			- dev ways to improve response
		- eval response may involve
			- measuring how long it took to perform each step
			- id areas of missteps 
		- IR team may issue report after completion, modify IRP

Org/Frameworks
- SysAdmin , Audit, Network, n Sec (SANS) Institute
	- Incident Handlers Handbook
	- guidance given on applying diff commands to id unusual
		- processes, files, registry keys
	- also explains methods to scan for abnormal network activ, irregularities in sch tasks, unexplained accts, suspicioius user behavior
- NIST
	- Computer Sec Incident Handling Guide
	- info on organizing incident response efforts like prov guidance on dev pol/proc
	- recc on composition IR team
	- detailed action plans, scenarios w applied guidance in appendix
- ISO Int Org for Standardization
	- ISO/IEC 27000 family of stndrds
- ![[Pasted image 20260406011019.png]]
- Other IRP Org/Frameworks
	- ITIL Info Tech Infra Lib
		- lib og created by brit gov, now mnged by join venture Axelos
		- outlines incident mgmt process integrated w service mgmt principles, issue certifications often sought by 3rd party IT providers, which is why IR tied closely to serving clients 
	- US-CERT US Computer Emergency Readiness Team
		- org collabing w gov entities/academia/priv sector to issue guidance related to IRP
	- PCI DSS Data Sec Stndrd
		- issues incident response plans specific to responding to cybersec incidents related to pmts/transactions 

- IRPs Tailored to Specific Attacks
	- many org have multipronged IRP tailored to specific cybersec assaults
	- = having mult IRP specifically designed to deal w a num of unique incidents, usually attacks to which org must vuln
	- IBM id attacks most often aligned w IRP, in order of most freq implemented
		1. DDoS attacks
		2. Mobile code like mal/spyware, virus, trojan, worm
		3. Phishing
		4. Insider incident
		5. BEC
		6. Disaster recovery
		7. SC attack
		8. Adv persistent threat