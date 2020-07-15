# Analysis Project: A Twist of Freight 

Development Team: Anastasia Valdes, Saya Uchiyama, Ally Qi, Madison Jenkins, Michael V Harris

A Twist of Freight
Freight is the backbone of our economy. As such, there is an endless supply of data on this subject and companies are constantly using this data to identify past, present, and future trends to identify supply chain transportation opportunities. We are interested in analyzing the movement of freight into, within, and outside of each state in terms of tonnage, specific commodities, and value. 

## Our project focuses on analyzing the movement of freight, what's being hauled and who's hauling it. So without any delay, let's delve into our key findings. 

### View 1: Transportation Modes
 
Finding #1: You will get the biggest bang for your buck focusing on the top four transportation modes
 
## Top 4 (# of Tons Transported, Commodity Value, Ton-miles)
  1.	Single Modes (11.5B tons)
  2.	Trucks (9.0B tons)
  3.	For-hire trucks (5.6B tons)
  4.	Company-owned trucks
 
Takeaway 1: There is a direct correlation between # of tons transported, commodity value and ton-miles (i.e. the number of tons shipped per mile traveled)
 
Takeaway 2: For logistical costing purposes if the key considerations are expediency and modal availability, go with the top 4 modes; if not, consider the remaining modes based on cost

## We've provided additional information in order to help you and your team visualize the market

### View 2: Transportation Mode Characteristics
 
In view 1 we identified Single Modes, Trucks, For-hire trucks, and Company-owned trucks as the top 4 transportation modes
 
In view 2, we'll examine the correlation between average miles per shipment and total ton miles related to these transportation modes
 
Based on our data, the average miles per shipment and total ton-miles trended downward for high-value, high-tonnage shipments, averaging less than 400 miles per shipment and less than 400 million ton-miles per transportation mode


### View 3: Commodities
 
We've included commodity data in order to help you better stratify the market. It's worth pointing out that the commodity data will require additional future research in order to be actionable but is a good starting point for isolating key market movers.
 
#### Average miles per shipment
 
Top 4
  1.	Tobacco products (1,209)
  2.	Textiles/Leather (1,009)
  3.	Misc Manufactured products (978)
  4.	Precision instruments and apparatus (902)

Takeaway: Transportation costs will have a greater impact on the retail cost of these commodities than on other commodities that are shipped shorter distances
 
#### Commodity Value
Top 4
  1.	Mixed Freight ($1.5 trillion)
  2.	Motorized and other vehicles (includes parts) -> $1.3 trillion
  3.	Pharmaceutical products ($1.17 trillion)
  4.	Electronic/electrical equipment ($1.14 trillion)

Takeaway: Wholesale costs of these commodities will likely trend higher based on their relative intrinsic value and will likely result in smaller margins for transporters

#### Number of Tons Shipped
  1.	Gasoline/Aviation fuel (1.6 billion)
  2.	Gravel/crushed stone (1.5 billion)
  3.	Coal (956.3 million)
  4.	Non-metallic mineral products (815 million)

Takeway: Impacts total ton-miles, which could have emission impacts (i.e. the more tons you ship, the more pollutants from the transportation mode enter the atmosphere, causing health concerns; environmental fines can be substantial)

### View 4: Inbound vs. Outbound Freight
 
TX and CA have the highest inbound freight tonnage, inbound freight value, and outbound freight value respectively
 
TN has the 10th highest inbound freight tonnage, inbound freight value and outbound freight value
 
Takeaway: Bulk commodities may ship cheaper than specialized commodities
 
 
## Based on our analysis, we recommend you focus your market research efforts on the top four transportation modes (single modes, trucks, for-hire trucks, company-owned trucks


## Project Requirements:
Visualization must include: 
•	Python Flask RESTful API, HTML, CSS, and JavaScript; and 
•	At least one database (MongoDB, SQLite, etc.); and
•	Powered by a dataset with at least 100 records; and
•	At least one JS Library that we did not cover; and
•	Some level of user-driven interaction (e.g. menus, dropdowns, textboxes); and
•	At least 3 views in final presentation.
Project must fall into one of the following 3 tracks:
•	A custom creative D3.js project (nonstandard graph or chart)
•	A combination of web scraping and Leaflet or Plotly
•	A dashboard page with multiple charts that update from the same data

## Source Data:
Bureau of Transportation Statistics
•	https://www.bts.gov/topics/freight-transportation/freight-shipments-value
•	Value of Freight Shipments by State: 2017
Economic Census
•	https://data.census.gov/cedsci/table?q=cf1700&tid=CFSPRELIM2017.CF1700P6&vintage=2017&layer=VT_2017_040_00_PP_D1
•	CFS Preliminary Report 2017
•	Shipment Characteristics by Mode of Transportation: 2017
o	Table: CFSPRELIM2017.CF1700P1
•	Shipment Characteristics by Total Modal Activity: 2017
o	Table: CFSPRELIM2017.CF1700P2
•	Shipment Characteristics by 2-digit Commodity
o	Table: CFSPRELIM2017.CF1700P6
Data Set Up Tools: 
•	(HTML, Javascript, Python (Flask app), SQLite, CSS)

