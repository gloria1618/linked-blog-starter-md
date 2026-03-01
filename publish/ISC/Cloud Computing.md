[[COSO]]
- computing model using shared resources over internet
- customers rent storage space, processing power, proprietary software, combo on remote servers from another company
- 
own infrastructure instead of renting
- purchase enough resource to cover peak usage
- low volume periods, costly infra idle
- resp for maintenance, tech support on hardware
customers
- infra elasticity - rent only as needed on min to min basis
- processing/storage rented in increments of computing power used per time unit
- provider usually performs all maintenance/tech support of hardware
- instead of purchase/build costly solutions
- org data in one virtual loc esp if org op in many loc
	- data processign more efficiently from single virtual loc, IT support reduced thruout org
- distributed redundancy among many data centers, reduced likelihood data lost in attack/disaster
cloud computing services offered by some org w large computing infra to either
- lease excess capacity during off peak
- use purpose built infra to support their customers

![[Pasted image 20260228234231.png]]
Models
- IaaS Infra
	- prov entire virtual data center of resources, org can outsource servers, storage, hardware, networking services, networking components to 3rd party providers
	- gen billed on per use basis 
	- company resp for
		- keeping env in which it op consistently up for users
		- virtually mnging performance of physical infra
	- CSP resp for phys mgmt of infra
	- degree to which org has control over certain functions vary across CSP and orgs
	- some companies may only use op sys/firewalls but not update/patch/maintain while others do
- PaaS Platform
	- prov proprietary tool/sol remotely that are to fulfill specific business purpose
	- tools facilitate creation of programs, delivery of services such as
		- building online platform to sell merchandise
		- advertise products
		- build other websites, running on CSP hosted infrastructure
	- CSP rep for keeping app's uptime acceptable by maintaining all back end infra
- SaaS Software
	- prov business app/software org use to perform specific function/process
	- gen purchase thru licensing
	- offers access via internet, resp for upgrades, sec enhancements, other support func
	- BPaaS
		- 3rd parties use SaaS software to deliver specific business func like outsourced payroll, billing, logistic services

Deployment Models
- Public
	- own/mgned by CSP making cloud services available to ppl/org who want to use/purchase
- Private
	- created for single org, mgned by org/CSP
	- cloud infra on/off premises
- Hybrid
	- 2+ clouds, w at least one private cloud, that remain unique cloud entities but w tech in place that facilitates portability of data/apps bw each entity 
- Community
	- shared by mult org to support common interest
		- companies banding together for regulatory compliance
		- common mission
		- collab w industry peers

CSP
- 3rd party prov cloud computing services such as 
	- application delivery
	- hosting
	- monitoring to customers
- performs all maintenance/tech support on hardware
- have adv skill/exp mnging cloud infra/env
- could be company using purpose built infra to support customer or one w large computing infra that leases excess capacity during off peak
- multi tenant
	- serve mult cloud customers at once n use common resources/tech for all customers
- Cloud Controls Matrix
	- framework designed for best prac regarding cloud security, data protection, compliance in cloud env
	- issued by Cloud Sec Alliance
- SOC 2
	-  info about CSP regarding compliance reg/standard
	- interested in controls implemented by service org to comply w HIPAA/Cloud Controls Matrix