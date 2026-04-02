- process of id, anal, mitigate threats to network/sys/app
- goal
	- understand all risks sys could face
	- dev ctrl/countermeasures to min risk impact or prevent

Phases of Threat Modeling
1. ID As
	- inventory all A to protect using CIA (confidentiality, integrity, availability)
	- eval threat landscape
		- tot range of potential threats of org/IT infra
		- regularly assess bc threats evolving
		- a way to assess is to use threat intelligence platforms, helping orgs get info on latest threats/vuln so org can prioritize 
		- elements to consider when eval
			- diff attack vector/methods
			- magnitude of impact of threat
			- existing vuln
			- types of threats (social eng, insider, network attacks, etc. )
2. ID Threats
	- id threat types/characteristics like intent, target, method
3. Reduction Analysis
	- decomposing A being protected
	- to understand how A interacts w potential threats whether in sys/app/netwrk
	- understand trust/security chngs, data flow, where input received, sec clearances, related policy/proc
4. Analyze Attack Impact
	- quantify impact in $ to prioritize sol
	- other qualitative effects
5. Dev Countermeasures/Ctrls
	- may incl implementing sec ctrls like intrusion detection sys, contingency plans, sec protocol in event of successful attack
	- responses prioritized based on threat w greatest risk
6. Rev/Eval


Threat Methodologies for Threat Models
- PASTA Process for Attack Simulation n Threat Analysis
	- focuses on risk, countermeasures prioritized by A value
	1. DO definition of objectives for risk analysis
	2. DTS def of technical scope
	3. ADA application of decomposition n anal
	4. TA threat analysis
	5. WVA weakness/vuln anal
	6. AMS attack modeling n simulation
	7. RAM risk anal n mgmt
- VAST Visual, Agile, Simple Threat
	- based on agile proj mgmt
	- integrate threat mgmt into programming env on scalable basis
- STRIDE Spoofing, Tampering, Repudiation, Info Disclosure, DoS, Elevation of privilege 
	- dev by Microsoft to assess threats related to app/op sys
	- 6 threat concepts in name broad enough to cover threat concerns other than apps like network/social eng