Quality Data:
- Complete
- Consistent
- Valid
- Accurate

Data Governance:
- Incorporates strategies to create secure and quality data
- Accountability
- Transparency of data in organisation
### BI:
- Data and Business intelligence (BI) give you the information and ability to make intelligent decisions.
- Business define metrics to track health of organisation (KPIs)
- Can see anomalies in a data set, and use other data collected to see what could've caused the anomaly
### Business Analytics vs BI vs Data Analysis:
- Business Analytics:
	- Analysing data
	- Creating data
	- Trends
	- Potential performance
- Data Analysis:
	- Analysing and capturing data
	- Over time
	- Potential performance
- BI:
	- Comparison 
	- How you're performing today
### Data Driven Decision Making:
- Important to take in considering all data, not just data that suits your cause
- Cost, list, and margin all matter
- Potential Costs:
	- Sales process
	- Storage
	- Packaging
	- Delivery
	- Infrastructure of automation
	- Payroll
### Collecting Right Data:
- Overcoming Analysis Paralysis:
	- Build approach
	- Standard questions
	- Critical thinking
	- Active listening
- Some general questions to ask:
	- Ever profitable?
		- If yes, when?
		- if yes, what's different now?
			- Coset changes?
- Once you answer these, more detailed and related questions will pop up
- And finally, what can be changed
### Existing Data:
- There is data everywhere, but sometimes we just don't have access to it, or it could be incomplete/inaccurate
- Whether systems are connected or not, they should hold same record of information
### Data Sources and Structures:
- Data has:
	- Value
	- Type
	- Field name
	- 3 above make a record
- Data -> fields -> tables -> Record 
- Stored in:
	- Spreadsheets:
	- Database:
		- With only certain field needed for reporting
	- Data warehouses:
		- Has refined tables from production systems
		- Keeps safe
	- Data lake:
		- Stores before refined
### Best Practices:
- Make sure data is recognised as it should be by the software you are using
- Keys need to be unique, deal with duplicates
### Assessing and adapting the data for transformation
- High level profile of data's characteristics
- Learn about your data at a high level
- Tell us how much data
- Helps validate numbers
- Inform us steps we might need to take when transforming data
### Rules of Data:
- When to expect data
- What to do with data
- What needs to happen in the transformation of data
- Following specifications
### Transforming Data in Excel with Power Query:
- Queries and connections -> Edit Query
- Perform functions without having to create a function
- Use this to analyse your data
### Transforming Data in SQL:
- A relational database management system with the primary function of storing and retrieving data
- Basic queries allow you to select data from the database
	- SELECT - Fields from the table
	- FROM - Table name
	- WHERE - Filter data
	- ORDER BY - Sort data
	- You have to always filter data before sorting it
### Transforming Data in Power BI:
- Transforms data
- Presents data
- Great for visualisation
- Group by function for total orders
- Merge queries option to merge orders and products together
- Join kind (using video example):
	- Left order, all products and if ordered
	- Right order, all order details regardless of match to product
	- Full outer, if not matching all rows from both
	- Inner join, products with orders only
	- Left/right anti, null values
### Common Cleaning and Transformation:
- Spaces removed, leaning or trailing
	- Use functions like trim or clean
- Parsing text, breaking out text, for delimiters, basically into different columns
- Concatenate
- Changing case of text
- Making text into a format we want
- Remove duplicates
- Transform data types
### Relational Databases:
-  Relational Database Management System (RDBMS)
- Key fields are unique identifiers 
	- Used to create relations between tables/databases
- Effective storage rules $\neq$ Combining data for reporting rules
### Modelling Data for Power BI:
- Joints allows data to communicate
- Power BI joints automatically, AutoDetect
- Also shows cardinality of relationship, eg. 1 and * is 1 to many
- Cardinalities:
	- One to one is one record to one record between two tables
	- One to many/many to one is one record in one table tied to many records in another table
	- Many to many
### Master Data Management:
- Eg. Customer and address information
- Needs to be consistent
### Unstructured Data:
- Anything that doesn't neatly wit into tables/spreadsheets
- Requires brains to review and provide context
### Visualisation Best Practices:
- Documentation and training to make sure people understand
- Be consistent
- Keep it simple
- Title, label, and tooltips
### Creating Reports to Visualise your Data Over Pages:
- Report with many line items and several pages are not best suited for a dashboard representation
- Not all data is best consumed using a dashboard
- Power BII report builder allows you to build paginated reports
	- Allows you to connect to data, unlike dashboard
- Style depends to need
### Gathering Requirements for Visualisation:
- Use samples, eg. Power BI dashboards
- Frequent meetings and updates with recipient
- Think about:
	- Filters needed for data
	- Filters needed for consumer
### Presenting:
- Talk to leadership throughout the process
- Don't wait to communicate challenges
- Let the right person know if the data is missing
- Communicate what you see, to validate and understand gaps
- Double check everything
- Turn to leadership
