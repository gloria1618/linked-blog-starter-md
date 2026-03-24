- every sys w/in org should be subj to ongoing chng mgmt testing to det whether newly installed sys/updates to existing sys do not lead to 
	- functional issues
	- security vulnerabilities
- testing should be
	- subj to rev
	- have mechanisms to reverse chng
- purpose of software testing
	- det whether software op as expected
	- discover errors, defects, missing components, gaps in software
	- verifies end product meets business/user req
- software testing process for chng mgmt 
	1. est testing plan incl roles, resp, timeline
	2. id, prioritize key areas of software to test
	3. det which type of test to run, specify test obj
	4. execute tests
	5. log results, id defects
	6. report findings, fix defects in timely manner
- Change Review
	- formal CAB Chng Advisory Board is recc so org can
		- adeq plan for chng
		- respond to unwanted chng outcomes
	- CAB can
		- approve chngs
		- doc chngs
		- notify users of upcoming/past chngs
		- deploy resources for testing/responding to chng
	- CABs should consider whether prop ctrl so there are sep env for testing, staging, prod
		- dev shouldnt have access to prod env, app operators shouldnt have access to dev env
	- auto notif so that chngs to code immediately sent to approp personnel, removing need to rely on human for chngs
	- code repository tools can be est so potential chngs can be
		- aggregated
		- reviewed
		- approved by CAB/approp staff
		- implemented
	- ![[Pasted image 20260323115341.png]]
- Rollback
	- upon discovery of unwanted chngs, org's CAB/IT team notify users prior to reverse/rolling back chngs to prevent productivity loss
	- req complete inv of sys configurations for apps, op sys so that sys can be restored to state that existed prior to chng
	- post implementation rev to det chng/rollback was correctly (un)installed
	- depending on extent of implementation, this can be
		- thru testing each chng on all devices/apps
		- thru validation sampling in which small subset tested
- Types of Testing Performed
	- sys tests to eval sys in dev to det if working
	- Unit Testing
		- examining smallest increment of app
		- can be broken down by func 
		- software dev dont have to consider broader sys issues like how one unit interacts w another
	- Integration Testing
		- aka thread/string testing
		- usually after unit testing so diff components/modules work cohesively 
		- helps plan for future sys maintenance/updates, allowing mngrs oppro to id weakness/security vuln that may req future patching
	- Sys Testing
		- verifies all combined modules of completed app work as designed in totality
		- may be eval by quality assurance team prior to releasing final prod
	- Acceptance Testing
		- in this quality assurance phase, dev assess app to det whether it meets end user req
		- may involve beta testing - sample of target customers tries application, could involve end-user testing in which emplee tests unfinished product