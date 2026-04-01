[[DFD]]
Business Process Modeling Notation
- creates flowcharts aka activity models
- improve effectivness/efficiency, id potential automation

Symbols
- flow activities
	- primary purpose of BPMN activity model is 
		- to describe orgs involved
		- w.in orgs how process separated across roles/duties
- Pools
	- orgs
	- one pool min - internal org
- Swim lanes
	- separates w.in pool
	- segregation of duties w.in org
- Events
	- how process begin/end
	- not actions
	- start
		- circle
		- every pool w.in BPMN has only one start
		- not based not swim lanes
	- end
		- thick circle
		- every pool at least one end 
	- intermediate
		- double lined circle
		- not req
		- indicates when smthn changes course of process, like delay/error
- Tasks
	- rectangle, round edges
	- each and every step
	- only one seq flow exiting
- Sequence Flow
	- smooth lined arrows 
	- every obj w.in one pool must be connected w seq flow
	- read from L to R
- Mssg Flows
	- dashed arrow
	- when 1+ pool, occasional req comms bw int/ext orgs
	- comms indicated by mssg flow only bw separate pools
- Gateway
	- diamond
	- question, not task, no action verbs
	- if more than one seq flow exiting
![[Pasted image 20260331173227.png]]