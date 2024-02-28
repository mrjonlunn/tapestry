# Tapestry
An example of metadata driven spark notebooks, for loading data using Microsoft Fabric.

![image](https://github.com/mrjonlunn/tapestry/assets/36087739/0eec235d-b26b-4b6b-a139-6d9cecd11ff1)


How to use Tapestry is now on the [Wiki](https://github.com/mrjonlunn/tapestry/wiki "Take me to the wiki")

## The why of Tapestry
There are two reasons why I've decided to create and release this.

### Reason One
I help run the Power BI User Group in Birmingham, and in chatting with the people that attend, they have the same issue. Loads of Azure Data Factory (ADF) pipelines, or Azure Databricks, Synapse notebooks, which are very specific to a single dataset, but mostly doing the same function. I mention maybe they can move to some sort of generic pipeline, using meta data to drive it. If you have a new dataset, you just have to add a config file, and a few other settings and away you go. Less time repeating code and you only have to manage one thing and not many. They normally go 'Wait! What?', and then we sit down and using a piece of A4 and pen draw out the outline. So I have now created this as a base for people to look at.
It is no means by perfect but should give someone and idea or starting point, for those dev's or citizen dev's to play with.

### Reason Two
The other reason is for me to play with Fabric, and get better at Python/PySpark, I said it is no means the right way of doing it. I have basicly tired to come up with very basic idea and see where it goes.

## Roadmap
### Raw
* Move to YAML rather than use JSON, as you get cool things like multi-line supoort
* Add schema vaildation and create variables direct from the file, not hardcode
* Restructure the main Raw Processing note book
* Add error handling
* Add Clean column names

### Sliver
This will be updated once I get to the Silver Layer and Bronze is complete

### Gold
This will be updated once I get to the Gold Layer and Silver is complete

## Notes on the Medaillon layout
I'll be using the Medaillon approuch to building a Data Lake in MS Fabric, using Bronze, Silver and Gold. However, these will be further sub-divided by a layers, such as raw, cleaned, conformed and reporting.
I would check out the video by Simon Whiteley [Behind the Hype - The Medallion Architecture Doesn't Work](https://www.youtube.com/watch?v=fz4tax6nKZM "Take me to YouTube")
