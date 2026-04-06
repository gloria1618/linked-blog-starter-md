[[Walk Thru]]
[[SOC2 Deficient]]

- structured process to det info handled to be in compliance w 
	- legal, regulatory, policy req
	- risk/effect of collect, store, delete info
	- id/eval protections/alternative processes for handling info to mitigate potential priv risk
- to mitigate risks, common priv specific op safeguards n sec ctrls to manage PII, proprietary info


- Data Collection
	- Creating Pol/Proc
		- define following
			- specific confidential data collected from emplee/customers
			- how confidential data collect, access, retained
			- incident response
			- priv in dev cycle
			- sharing rules
			- violation consequences
	- Training
		- to understand guidelines, repercussions of violating
- Data Processing
	- De-identify Personal Info
		- by removing enough personal info to not id indiv
		- pseudonymization 
			- replace name w smthn like Patient 0
		- anonymization
			- remove ability to trace identifying data pts to person when full rec not needed 
- Data Storage
	- Use Access Enforcement
		- ctrl access to personal info thru AC pol, access enforcement mechanisms
	- Implement AC for Mobile Devices
		- prohibit/limit access to personal info from portable/mobile devices
	- Auditing Events
		- monitor events affecting confidentiality of personal info, such as inapprop access to PII
- Data Transmission
	- Prov Transmission Confidentiality 
		- encrypting comms, encrypting info before transmitted
- Data Deletion/Purging
	- Archiving, Purging Policies


- when new sys dev, tested, implemented, org often deploy methods protecting confidential data using data obfuscation 
- Obfuscation
	- replace production data/sensitive info w data less valuable to unauth users
	- [[Encryption]]
	- Tokenization
		- removes production data, replaces w surrogate value/token
		- fake/dummy data
		- tokens generated
			- using random # generators
			- hashing, transforming data using math algorithms
			- encryption
		- keys used to reverse stored in token vault, ctrlled by auth/access ctrls
		- sim to encryption but gen doesnt chng length/chara type
	- Masking
		- swaps data w other like data so og identifying chara masked, while maintaining sim structure to unmod data set
		- mod data sets agg value remains intact, allowing insights/data to be extracted
![[Pasted image 20260404140020.png]]