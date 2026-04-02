- computer lang to interact w relational databases
- records, tbls can be create, update, delete, view, extract
- retrieve data in more intuitive way for anla than way its stored

- SQL commands
	- case doesnt matter
	- SELECT, FROM
	- JOIN, ON
		- join on FK of one tbl to another PK 
		- Inner Join
			- FROM tbl1, INNER JOIN tbl 2, ON tbl1.samekey=tbl2.samekey
			- order of tbls dont matter
			- to select matching data from both tbls
				- SELECT * , FROM tbl1, INNER JOIN tbl2, ON tbl1.samekey=tbl2.samekey
			- only data common in both tables
				- SO records that have customer info
		- Left Join
			- FROM tbl1, LEFT JOIN tbl2, ON tbl1.samekey=tbl2.samekey
			- FROM tb1 means tb1 is the 'left' table
	- GROUP BY
		- How many sales orders for each customer?
			- SELECT CustomerID, COUNT(SalesOrderID)
			- FROM SalesOrders
			- GROUPBY CustomerID
		1. det which fields to agg
		2. det which field to group the agg by
		3. place descriptive attribute, agg func in SELECT
		4. FROM which tbl
		5. GROUPBY also contains descriptive attribute to groupby
	- HAVING
		- to filt based on agg measure bc WHERE cant do that
		- ![[Pasted image 20260328024112.png]]
	- WHERE
		- like filter
		- WHERE {attribute name}={criteria}
			- no quotes
			- text criteria should be in quotes
	- ORDER BY
	- agg func
		- SUM(), COUNT, AVG, MIN, MAX
		- Select COUNT(SalesorderID) FROM SalesOrder
- Database elements
	- references to tbls, attributes, criteria
	- case doesnt matter
- SQL clause
	- commands + database elements
	- typically begin w SELECT/FROM
		- SELECT Firstname, Lastname, State
			- can reorder
			- * = wildcard, select all in order in tbl
		- FROM Customers

![[Pasted image 20260326215912.png]]