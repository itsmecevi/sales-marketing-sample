# sales-marketing-sample

This is a Doku for Sales & Markting analysis sample with Power BI.

Source: 
https://docs.microsoft.com/en-us/power-bi/sample-sales-and-marketing from http://obvience.com/

The dataset: [Click here](https://drive.google.com/file/d/1s15qKFObhzhwWJ6yW6hLmwCbiEUjdEfF/view?usp=sharing)

Before going further, we need understand the concept of the data model, please read the link below:
https://en.wikipedia.org/wiki/Data_model

This analysis contains 6 entity (table) and every table has attribute.

1. product
* Attribute: Manufacturer,	Category,	Segment,	Product,	ProductID,	isVanArsdel,	IsCompeteHide,	ManufacturerID,	IsCompete


2. date
* Attribute: Date,	MonthNo,	MonthName,	MonthID,	Month	Quarter,	Year,	RunningMonths,	Running Year,	Running Months,	Rolling Period,	Rolling Period Sort,	MonthIndex


3. geo
* Attribute: Zip,	City,	State,	Region,	District


4. sentiment
* Attribute: DateID,	StateID,	ManufacturerID,	Score,	Manufacturer,	Date,	State,	zip,	ProductID


5. manufacture
* Attribute: ManufacturerID,	Manufacturer,	MfgisVanArsdel


6. sales fact
* Attribute: ProductID,	Date,	Zip	, Units,	Revenue



### Let's make the data model from the 8 entity. Just drag every [Primary Key](https://en.wikipedia.org/wiki/Primary_key) of the entity in power pivot or power bi data model


![sales-marketing-data-model](https://user-images.githubusercontent.com/27078712/40890011-f5e38d46-676f-11e8-9a12-7403595c7410.PNG)



### After that, create [a measure in power bi or power pivot](https://docs.microsoft.com/en-us/power-bi/desktop-tutorial-create-measures)

Below are the measure of every graph,

Note! we use the format of table and attribut with [DAX language](https://docs.microsoft.com/en-us/power-bi/desktop-quickstart-learn-dax-basics) 

Extras: [Quick Guide DAX](https://support.office.com/en-us/article/quickstart-learn-dax-basics-in-30-minutes-51744643-c2a5-436a-bdf6-c895762bec1a?omkt=en-US&ui=en-US&rs=en-US&ad=US)

---------------------------------------------------------------------------
Drag this entity for every graph: 
.
.
.coming soon!



