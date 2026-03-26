[[Data Collection]]
- helps org understand what data they have access to, how to use resp
- data constantly made thru
	- transactional sys
	-  AI
	- IoT
	- manual creation
- steps business data gotta go thru
	1. Definition
		- define data org needs, where to capture/retrieve data
		- helps select relevant data to goals of data collection
	2. Capture/creation
		-  internal data - digital A created by org
			- manually (eg key in sales order)
			- automatically (eg sys loc)
			- semi auto - (eg emplee rev'ed sales order record created thru optical character recognition of customer's recognition purchase order PDF)
		- when data from ext source, complexity of integrity, safety, copyrights
		- when internal data gen (semi) manual, input checks to maintain integrity/accuracy
			- Field checks
				- checks input types to ensure consistency w field req (date,time,etc)
			- Reasonableness check
				- compares input against expected norms based on context
			- Completeness check
				- missing mandatory fields
			- Validity check
				- verifies data against predefined rules/reference data
			- Limit Check
				- checks data values against predefined upper/lower limit
			- Size Check
				- checks if # of characters exceeds max allowed for field
	3. Prep
		- det if data complete, clean, current, encrypted, user-friendly
		- Enhancing completeness/integrity
			- whenever data moved one loc to another, some req data could've been lost during capture process
			- integrity (not manipulated, tampered, duplicated)
			- Validation
				1. compare # of records u intended to capture to # in source database for potential missing rows
				2. compare descriptive stats for numeric fields if privy to checksums of original, for missing/incorrect format
				3. validate field formats consisted w source (string, date, time, #)
				4. compare character limits for attributes in source file to new file to ensure data not lost due to mismatched character limits
		- Data integration - when data sourced ext, crit to design architecture to
			- ensure data pipeline integrated w target loc/database
			- ensure any ongoing updates of ext source loaded timely/accurate
		- Cleaning
			1.  remove unnecessary heading/subtotals otherwise obstructing data synthesis/analysis
			2. clean leading 0s, nonprintable characters
			3. format negative #'s to ensure consistency
			4. id, correct inconsistencies
				- inconsistencies will need to be replaced by common value if anal req grouping based on that attribute
				- CA, Cal, Ca > CA
			5. address inconsistent data types (datetime, doubles, string, integer)
		- Data encryption - transit+storage
	4. Synthesis
		- creating calc fields to prep data for quicker usage/anal
		- not always necessary
		- ex: creation of calc for netsales on existing gross sales and sales returns, allowances, discount fields
	5. Analytics/Usage
		- create reports/inform decisions
		- for long as data useful to internal org
			- not being shared w ext user/stakeholders
	6. Publication
		- ex:
			- sending monthly stmts to clients
			- publish FS
			- sending quotes to customers
		- shared ext = published, internal org no longer has sole control of how data used, further shared, archived, purged
	7. Archival
		- following decline in need of specific data sets, they're moved from active sys to passive sys for archiving
			- free up storage for active sys
			- enhance active sys performance
			- reduce security risks
		- optimally, archived data tested for accuracy/completeness prior to removal
	8. Purging
		- data completely removed from storage sys (archive n otherwise)
		- crit to ensure 
			- data truly reached end of its use
			- no req (legal, etc) to maintain archived data
			- once time to purge, its completely purged

