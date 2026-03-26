[[Relational Database]]

- ODS Operational Data Storage 
	- repository of transactional data from multiple sources, often interim area bw data source n data warehouse
	- captured transactional data could be related to op activities like
		- customer orders
		- sales
		- vendor pmts
	- could also be
		- sys related
		- measuring available storage
		- sys latency
		-  # of records processed by given sys 
- Data Warehouse
	- very large data repositories that are centralized, used for reporting/anal rather than transactional purposes
		- pulls data directly from enterprise sys w transactional data or ODS
		- data then combined into 1 repository for reporting, creating data marts, etc
	- predefined schema
- Data Mart
	- like warehouse, but specific purpose like mkt/logistics, subset of warehouse
		- helps indiv dep w tailored datamarts
- Data Lake
	- like warehouse, but both un/structured, mostly natural/raw format
	- doesn't have predefined data structure/schema, not indexed/prepped

- On premise v Cloud based storage
	- on premise storage
		- trad on physical drive/servers in data centers
		- onsite repositories - ODS, warehouse, mart, lake
		- w growth in vol n improving cloud computing tech - costly/cumbersome
	- Cloud
		- tech allows data to be securely stored/migrated to cloud
		- highly scalable, consume data w agility
		