Identification n Authentication Techniques


first person's id claimed, then authenticated
- user must first go thru initial registration process where user creates identity
- then authentication for user configured
	- typically done by submitting most foundational form of id like SS card, drivers license, passport
- username/password once common form of id/auth, awa org issued id cards w pics


- Identification
	- process of claiming/asserting identity, thru means like username/id card
- Authentication
	- validating that identity claim, thru like password/scanning id card
	- Context Aware Auth
		- used to id mobile device users w contextual data pts like time, geo loc, point of access (mobile app, desktop browser, call center, etc.) or IP address
	- Digital Signatures
		- e stamp of auth, usually encrypted n attached to mssg for non repudiation (proof of id)
		- cryptography w 
			- sender encrypting mssg w private key
			- receiver decrypting mssg w sender's public key
	- SSO Single Sign On
		- allow users to auth one time for single session on mult resources/devices
	- MFA Multi Factor Auth
		- uses 2+ factors to validated identity
		- often combines knowledge w possession
	- PIN Personal Identification #
		- numeric code that cardholder memorizes
		- most effective when combined w other authentication factors 
			- PIN serving as knowledge
			- phys device, token gen, etc as user possesses
		- PIN should be changed regularly, not be duplicated across other apps, be at least 6 characters, have limited entry attempts
	- Smart Cards
		- plastic cards w microprocessor enabling holder to 
			- process data, act as certificate that can be used to purchase goods
			- enter restricted areas
			- execute other activ only holder can perform (void sale, apply discount)
	- Token
		- devices that gen fixed digit passcodes that are carried w users as multfactor/2ndary auth
		- passcodes gen by token stored on auth server, so when entered its checked against server
		- Synchronous tokens - time based, req token/server to be sync (preferred) {bing}
		- asynchronous - dont use clock, create passcodes based on same algorithm, usually expire after short time {kpmg email}
	- Biometrics
		- uses human phys characteristics, impressions to verify identity
			- facial recog, fingerprint.palm scan, hand dimensions, voice recog, iris/retina, heart/pulse, keystroke, handwriting, signature dynamics


Password Mgmt
- crit bc
	- most common form of auth
	- most common method of attack for hackers
- weaknesses
	- ppl often use easily guessed, reuse for mult accts, share w others, never change em, write down
	- short PW can be guessed by brute force attacks 
	- PW saved by orgs in databases accessible by web are freq breached by attackesr
- counter
	- PW complexity standards recc
	- passphrases 
		- memorized seq of words/txt used to auth id
	- longer = more secure
	- NIST recc having at least 8 chara per SP 800-63B, but many have 12+
	- changing passwords freq recc, encouraged to be changed bw 45-90dys

Password Managers/Storage
- PW storage/mgmt apps 
	- store pw by hashing rather than as plaintxt
	- hashed pw then stored in databases, when user enters a pw, the hashing algorithm is computed using that word
	- computed hash value compared to hash value stored in database, access granted if match 
- Hashing
	- converting pw into illegible txt w hash algorithms like SHA secure hash algorithms
- hashed pw are 1way, not intended to be reversed tho possible
- so if attacker gains access to pw database that only has hashed pw, must det which hashing algorithm used
- to enhance sec, these used freq w hashing
	- salting 
		- adding random string of chara to pw input prior to running thru hashing algorithm
	- iteration count
		-  # of times a process (hashing algorithm) is being repeated to enhance security

Provisioning
- process in id mgmt when org creates users acct n provisions it w priv based on job roles
- often automated, yet protected processes, but crit in creating valid id that can auth
- may be part of emplee onboarding process when
	- other id, background checks performed
	- no rights should be provisioned to indiv that dont meet company standards
- orgs first register/auth new int/ext users, then sys credential issued, sys permissions granted
- for those users whose access is administered by org, user sys credentials need to be removed when user access no longer authorized
- SOC2, auditors may inspect access request forms for sample of new emplee who rec access to in scope sys components during a specified period
	- performed to det access provisioning request was approved prior to access being provisioned

Device Authentication
- validating user's id by verifying device making connection request 
- emphasis not on credentials/userid but id of device
	- IP address
	- MAC address
- weak as standalone method
- but strengthens multifactor approach where user req to enter login credentials, use valid device