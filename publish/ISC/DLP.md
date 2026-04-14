Data Loss Prevention
- to detect/prevent attempts by emplee/unauth users to transfer sensitive info out of org electronically across mult protocols, ports, comms methods
- DLP sys often use pattern matching methods/word recog tech to scan files for certain patterns, such as way in which data formatted/sequenced
- ex
	- sys designed to comply w regulatory stndrds like HIPAA, PCIDSS, GDPR, may deploy pattern matching tech searching for strings of 9 chara # s w dashes after 3rd # n 5th # to id potential SS # s
	- software may then either prevent mssg from being sent or encrypt it 
- main obj/best prac of DLP is to dev program to 
	- implement centralized DLP program, w collab from various deps, overseeing data for entire org
	- def, create enterprise data usage pol, report data loss incidents, est incident response capability to enable corrective actions to remediate violations 
	- eval diff data forms, def diff sensitivity lvls, create inv of sensitive data, id where sensitive data, id where sensitive data stored, manage data cleanup
	- monitor use of sensitive data, understand usage patterns, gain enterprise visibility
	- enforce sec policies to proactively secure data, prevent sensitive data from leaving enterprise
	- emplee edu programs
- Records of DLP pol violations typ archived in database that id data moved n where it went on network
- Network based DLP sys
	- scan outgoing data meeting specific criteria, and
	- are transmitted using means like email, file transfer protocol (ftp sites facilitating file transfer), and direct mssging
- Cloud based DLP
	- same protection as network based DLP but to cloud env
	- data loss prevented when transferring sensitive data across virtual machines/platforms rather than an org's private on premises network
- Endpt based DLP
	- scan files stored/sent to devices that might be outside network
		- printer, USB drive, other device to which data can transfer
	- data transfer to such devices prevented by scanning for specific keywords, patterns, file types, such as MP4 files
- ![[Pasted image 20260404220315.png]]


Protecting Data at Rest
- storing sensitive data req robust storage infra that prov
	- phys sec
	- digital sec ctrl
		- incl encrypted hard/USB drives, or sec file sys that are encrypted
	- authorization, proper AC
		- incl ctrl mech such as role/rule/discretionary based AC, multifactor authentication
	- chng mgmt ctrls
		- procedural ctrls that req there to be processes in place for requesting changes to a sys or data, rev/approval, implementaiton, reversion, documenation
	- backup/recovery mechanisms
		- redundancy defenses protecting data so not lost, can restore, if disaster, attack, accidental deletion/modification

Deleting Confidential Information
- done thru
	- phys destruction
		- phys disassemble, changing chemical construct of data
	- overwriting/clearing
		- prep media for reuse by replacing old data w unclassified data
	- deleting
	- purging
		- perm removes data from drive/sys to improve sys performance, purged data could be archived outside of sys (eg cloud ERP data retrieved by user before ERP provider purged all data)
		- repeats clearing process mult times, may combine w another method like 
		- degaussing
			- strong magnetic field to erase data on storage devices that use magnetism like magnetic tapes
	- erasing
		- permanent delete op of file/data
		- completely unrecoverable/destroyed
- residual magnetic flux/imprint may remain when data removed, incl data remanence 
	- common on media storage devices using magnetism 
- if erased/overwritten, degaussing usually will remove remanence, therefore confidential info cannot be retrieved from device
- even if degaussing, tools avail may be able to undelete/reverse wiping effects
- phys destruction may be only means to compeltely purge confidential data
