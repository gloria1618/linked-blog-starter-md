[[Risks]]
[[Ctrls]]
[[Method]]
[[Patch Mgmt]]
[[Sys Conversion]]
[[Testing Strat]]
- Chng Mgmt
	- policies, proced, resources employed to govern chng in org
	- changes
		- may be initiated from w.in org, or imposed from outside
		- will usually have impact on IT infra such as internal hardware, software apps, governance
	- scope of chng to be managed can range
		- from smthn routine as implementing new software update
		- to complex/infreq like overhauling org's core switching architecture
- Chng Mgmt Process
	- do change w.o losing ability to op n achieve strat obj
	1. id, define need for sys changes
	2. design high lvl plan, incl goals to achieve bc of sys chng
	3. obtain approval from mgmt for change
	4. dev approp budget/timeline
	5. assign personnel resp for managing sys chng
	6. id, address potential risks during/after
	7. prov implementation road map
	8. procure necessary resources, train approp personnel
	9. test sys chng
	10. execute implementation plan
	11. rev, monitor chng implementation, test as needed to verify effective implementation

- Types of Env
	- chngs should be implemented in seg env w.in org so normal op not disrupted
	- diff forms of computing env incl
		- Development
			- software programmers write code to create app prototypes
			- source code editing tool to create.mod code syntax, automation tools that have preconfigured code, debugging tool to help fix errors
		- Testing
			- dev test/debug code to id errors to correct
			- may be considered same as Development
			- some org may keep Test separate to focus on debugging errors in app thats mostly complete
		- Staging
			- test programs in their final dev phases in a production like env
			- tests functionality, compatibility, security, performance prior to deployment
		- Production
			- env which app deployed
			- made available to end users
		- Disaster Recovery
			- set up to ensure apps can be restored quickly, save crit data/sys, notify mgmt, recover in event of outage/attack