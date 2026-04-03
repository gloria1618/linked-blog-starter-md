- Vulnerability Mgmt
	- proactive sec practice designed to prevent exploitation of IT vuln
	- involv id, classify, mitigate, fixing known vuln
	- integral part of computer, network security and plays important role in IT risk mgmt
	- to meet obj, org may use detection/monitoring proc to id chngs to config resulting in
		- intro of new vuln
		- susceptibilities to newly discovered vuln
	- org may also conduct periodic vuln scans designed to id potential vuln, misconfigurations after any sig env chng
	- subs, org remediate id deficiencies in timely manner
- Vuln Tools
	- like vuln assessments/scanners
	- application of frameworks, like NIST Cybersec Framework
- Applying NIST Cybersec Framework
	1. Govern
		- use CSF to est, monitor cybersec risk mgmt strat, expectations, policy
	2. Identify
		- use CSF to id resource vuln present in sys, data A, emplee
		- apply framework to understand business env in which those A op, understand pol est regarding those resources to define how governance executed 
	3. Protect
		- create safeguards against vuln by est measures to
			- manage id, access ctrls
			- keep A secure
			- inform emplee of threats
	4. Detect
		- use framework to define relevant activ that can id vuln quickly 
		- activ may incl
			- searching for anomalies
			- performing cont monitoring
			- verifying results of protective measures are effective
	5. Respond
		- use CSF to put activ in place that will react to discovered vuln, incl
			- analysis of issue so approp response is delivered
			- executing mitigating activ to prevent vuln affecting other org parts
			- comms to org what issue is as well as chosen response
	6. Recover
		- helps org transition from current state in which vuln exists to where vuln mitigated
			- implementing recovery plan
			- improvements
			- delivering internal comms to approp staff abt recovery

Vuln Scanners
- apps testing orgs sys for known sec risks
- checks results against database of known threats
	- database periodically updated so current w recent threats
- scanners work by 
	- scanning for open network ports that can be exploited
	- anal data pkts transmitted across sys
	- id protocols being used
	- fingerprinting, id's type of op sys n apps running on victims sys
- attackers can also use scanners to id weakness, exploit
	- wait to launch attacks after databases updated n rolled out to customers
	- w larger org, updates predictable, attackers can plan so dangerous

Vuln Assessments
- typ don part of initial risk anal, then subs performed quart/annually
- vuln scanners often
	- used in these assessments
	- obsv over time to det if threats still linger 
- sometimes org cant implement sol bc could hinder op
	- cont op while exposed until sol that allows mitigate n op efficiently
- assessments involv obsv of mult IT processes n emplee interviews across orgs that may not normally be eval collectively 
- agg view of org allows mgmt op to see how sys n processes in one part of org creates vuln in other parts

Common Vuln n Exposures CVE Dictionary
- database of sec vuln prov unique identifiers for diff vuln/risk exposures
- new vuln added to dict by MITRE Corp
- helps standardize recog/naming of vuln 
- CVE identifiers are 
	- used by various cybersec products
	- denoted as ''CVE Compatible'' so customers know vuln have been mitigated

Patch Mgmt
- important part of min sec threats that work in conjuction w vuln mgmt sol
- effective patch mgmt involv
	- IT admin assessing update for applicability to org
	- testing patch on isolated sys, planning w mgmt to implement patch 
	- deploy patch
	- validating successfully implemented
- org may be expected to maintain chng mgmt log
- SOC2, patch mgmt process normally subj to inspection