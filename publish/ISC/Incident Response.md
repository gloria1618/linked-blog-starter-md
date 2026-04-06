[[in Accord w IRP]]
[[q-followed]]
[[Insurance]]
- doc of set of proc, ppl, info to detect/respond/limit consequnces of cyberattack
- have formal/coord plan for responding to incidents, incl roadmap for implementing response capabilities detailing method of
	- detection
	- response timeline
	- incident response teams resp
- plan should meet unique req related to org incl
	- mission
	- size
	- structure
	- op function
- NIST key elements that most pol contain
	- mission
	- strat, goals
	- senior mgmt approval/stmt of commitment
	- org approach to incident response
	- purpose/obj policy 
	- policy scope
	- metrics to measure incident response capability/effectiveness
	- roadmap to maturing IRP
	- def computer sec incidents, related terms
	- org structure, def of roles/resp/authority lvls
	- prioritization/severity ratings of incidents
	- int/ext comms methods
- robust IRP req recovery timeline be charted
	- when incident occurs
	- when detected, contained, eradicated
	- when normal business op restored
	- often gantt chart
	- ![[Pasted image 20260405223504.png]]
- Detection Methods
	- methods deployed should be listed in IRP contents
	- vuln scanning software
	- anomaly detection
	- EDR endpt detection n response sol
	- file integrity monitoring
	- log anal
	- IDS intrusion detection sys
	- IPS intrusion prevention sys
	- phys sec monitoring
	- sec info, SIEM sec info n event mgmt sol
	- threat intelligence software 
	- UBA user behavior anal tools

Incident Response Personnel, Roles, Resp
- ppl most crit part of IRP designated to respond to an incident
- coop thruout org, specialized emplee, guidance/support of senior mgmt, 
- NIST recc models
	- Centralized Incident Response Team
		- single IR team tasked w mng incidents across org
		- effective for smaller org, w computing env not dist geo
	- Dist Incident Response Team
		- mult IR teams resp for specific logical/phys segments of network
		- effective if computing resources widespread geo
	- Coordinating Team
		- 2ndary func of either centralized/dist IR team is coord w other dep w.o having authority over those teams
- NIST Computer Sec Incident Handling Guide recc org consider 5 when selecting approp structure/staffing model for IR team
	1. 24/7 Availability
		- most org need IR staff available 24/7 by phone/onsite
	2. FT v PT team members
		- funding
		- other staffing need/constraints
		- industry 
		- indiv org needs
		- outsourcing to virtual IR team may be viable alt to FT staff
	3. Emplee Moral
		- IR work demanding bc often req on call resp of most team mem > stress
		- diff to find willing, available, skilled ppl to hire esp for 24hr support
		- segregate roles as option to combat fatigue
	4. Cost
		- 24/7 expensive
		- bc works w many IT facets, members req broader knowledge than most IT emplee
		- n understand how to use IR tools like digital forensics software
	5. Staff Expertise
		- req mix of specialized knowledge/experience in non/tech
		- deeper, up to date knowledge of detection, forensics, vuln, exploits
		- often logical to outsource to MSP who can spread expense across client base
- Common for IR team to perform additional duties
	1. Edu/Awareness
		- emplee outside IT team know about detecting, reporting, responding to incidents, less of a burden it will be on incident response team
		- workshops, intranet sites, newsletters, posters, paraphernalia w sec tips/reminders
	2. Advisory Distribution
		- issue cyber briefings/newsletters to inform rest of org regarding new vuln/threats id by teams
	3. Info Sharing
		- IR teams may participate in info sharing groups, mng incident info sharing efforts in broader cybersec community
		- info abt past incidents, response selected, response results, resulting org chngs