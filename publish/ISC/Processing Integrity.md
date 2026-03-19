Detecting Design Deficiencies in Processing Integrity S2M2

- Processing Integrity - sys ability to initiate/complete transaction so that its
	- valid
	- accurate
	- timely
	- authorized to meet objective
- Integrity - confidentiality/privacy of deets related to transactions involv data that id customers, patient health records, emplee, fin accts
	- 1/5 AICPA Trust Services Criteria

- AICPA SOC2 'deficiencies in ***design*** (suitability) of control' definition
	- necessary controls missing, or
	- existing controls not designed prop
- apply trust services criteria to id whether deficiency in design exists related to processing integrity
	- service auditor must
		- understand mgmt risk assessment process
		- eval link bw controls in sys description and relevant trust services criteria
		- det whether approp controls in place
		- det whether those controls implemented
	- Trust Services Criteria: ex how to eval deficiencies
		1. Security
			- id transaction processing methods compromising confidentiality, privacy, availability, and can be circumvented for unauth access
		2. Availability
			- search for dataflow bottlenecks, other processes preventing data availability
		3. Processing Integrity
			- survey processing methods/transactions not completed timely/at all, faulty results, dont meet objectives
		4. Confidentiality
			- eval emplee/process handling confidential data to id potential data leak, mishandling, other pracs exposing confidential info
		5. Privacy
			- anal methods to collect, store, use, dispose of personal data being processed to id potential for data breach/leak
- another way to id deficiencies, use AICPA *Description Criteria for a Description of a Service Org's Sys in a Soc 2* to compare w org's sys design documentation
	- set of benchmarks in implementation guide
		- strong tool for eval sys descriptions of service orgs
		- can specifically be used for detecting deficiencies in suitability/design of controls related to an info sys's processing integrity
	- 2 items guide recc to rev are principle service commitment, principle sys req, which are req to be disclosed by mgmt to support understanding of
		- sys
		- services provided
		- design of controls
	- understand how/why mgmt disclosed certain sys attributes w.in these descrip, particularly those related to processing integrity, will help assess suitability of sys ctrl design 


- AICPA SOC2 'deficiency in **op** of ctrl' definition
	- properly designed ctrl that either
		- doesn't op as designed
		- performed by person lacking authority/competence to perform ctrl effectively
- ctrls suitably designed if (potential to) meet trust services criteria bc prov reasonable assurance that sys req/service commitments achieved 
- Performing Tests of Ctrls
	- to test op effectiveness of ctrls based on trust services criteria, service auditor should obtain proper evidence
		- how ctrls applied
		- consistency of application
		- personnel resp for applying ctrls
	- doc chngs to service orgs, if possible test ctrls before/after chng to det whether modified ctrl meets service commitments relating to trust service criteria
	- if deficiencies alr id, service auditor not req to test effectiveness of those ctrls
	- service auditor resp for designing/performing test of ctrls, may incl
		- making inquiries
		- reperforming ctrls
		- observing service org personnel performing ctrls
		- reviewing documentation
	- allows service auditor to obtain evidence, whether ctrls dependent on other ctrls
	- timing critical when designing, understand
		- period in which data will be available
		- potential for data to be overwritten if not obtained timely
	- testing can be performed at 
		- interim dates
		- at end of examination period
		- after examination period if ctrls in op don't leave evidence until after period end
	- size/freq of sampling when testing ctrls, consider variables
		- how often ctrl performed
		- expectation that ctrl will actually deviate
		- testing period length
		- reliability of evidence
- Ctrls that didnt need to op
	- some ctrls, due to nature of op/circumstance
		- cannot op during testing period
		- not prudent to op
	- ex: ctrls relating to authenticating new emplee id, but no new emplee
	- service auditor doesn't need to modify opinion on op effectiveness of ctrls
- ID deviations in op effectiveness of ctrls
	- service auditor should accum doc of occurrences of deviations in op effectiveness of ctrls as discovered
	- if service auditor can't obtain reasonable assurance that sys req/service commitment being met, deficiency = material
	- if deviations bc fraud, assess risk that
		- sys description doesn't accurately reflect sys that was designed
		- op ctrls not op effectively
	- consider applicable noncompliance w regulations, may be approp for service auditor to do following:
		- hold discussions w approp parties
		- request approp party consult legal counsel, regulator, qualified 3rd party
		- consider implications related to other engagement aspects
		- obtain legal advice about diff courses of action, consequences
		- comms directly w regulators, approp 3rd party
		- withdraw from engagement
	- if service auditor id other sys not w/in scope of audit that are affected by sys incident, auditor should understand nature/cause of incident bc could be result of ineffective ctrls of sys being audited
		- if incident result of security breach, then auditor should det
			- whether inherent risks of sys env are diff from originally assessed
			- whether sys compromised
	- reassessment of risk may req additional procedures performed, or new evidence obtained of additional ctrls that are suitably designed that do provide reasonable assurance that service req/commitments were met based on trust services criteria
	- service auditor ult decides whether the id'ed deviations, indiv/combined, are material
		- 