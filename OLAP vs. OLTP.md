they are both data processing systems
- OLAP (online analytical processing) : 
	processing multi dimensional data (data that have several elements) in "OLAP cube" that allows fast querying, insertion and deletion of big data, it's good for [[Data Mining]] and complex analysis
	- it uses normalized databases more
	- uses RDMSs (CRUD)
	
- OLTP (online transactional processing)
	processing A LOT OF transactions(updating, inserting, ..) by a lot of people really quickly.
	- it uses denormalized databases more
	- uses data warehouses (write once, read many times)
	
many people use OLTP to provide data for OLAP system