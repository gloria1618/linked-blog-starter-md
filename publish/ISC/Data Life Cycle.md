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
			- steps to validate captured data
				1. compare # of records u intended to capture to # in source database for potential missing rows
				2. compare descriptive stats for numeric fields if privy to checksums of original, for missing/incorrect format
				3. validate field formats consisted w source (string, date, time, #)
				4. compare character limits for attributes in source file to new file to ensure data not lost due to mismatched character limits
		- Data integration 
	4. Synthesis
	5. Analytics/Usage
	6. Publication
	7. Archival
	8. Purging