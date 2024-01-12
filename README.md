# Tapestry
An example of metadata driven spark notebooks, for loading data in Microsoft Fabric

## The why of Tapestry
There are two reasons why I've descided to create and release this.

### Reason One
I help run a Power BI User Group in Birmingham, and in chatting with the people that attend, they have the same issue. Loads of Azure Data Factory (ADF) pipelines, or Azure Databricks, Synapse notebooks, which are very specific to a single dataset, but mostly doing the same function. I mention maybe they can move to some sort of generic pipeline, using meta data to drive it. If you have a new dataset, you just have to add a config file, and a few other setting and away you go. Less time repeating code and you only have to manage one thing and not many. They normally go 'Wait! What?', and then we sit down and using a piece of A4 and pen draw out the outline. So I have now created this as a base for people to look at.
It is no means by perfect but should give someone and idea or starting point, for those dev's or citizen dev's to play with.

### Reason Two
The other reason is for me to play with Fabric, and get better at Python/PySpark, I said it is no means the right way of doing it. I have basicly tired to come up with very base idea and see where it goes.

## Releases
-  v0.1 - Intital release
    - Basic notobooks to get file from a landing area to the Bronze-Raw Layer

## Roadmap
### Raw
Move to YAML rather than use JSON, as you get cool things like multi-line supoort
Add error handling
Add YAML file vailadtion
Add Clean column names

### Sliver
This will be updated once I get to the Silver Layer and Bronze is complete

### Gold
This will be updated once I get to the Gold Layer and Silver is complete

## Notes not the Medaillon layout
I'll be using the Medaillon approuch to building the Data Lake in MS Fabric, using Bronze, Silver and Gold. However, However these will be further sub-divided by a schema.
I would check out Simon Whiteley video on [Behind the Hype - The Medallion Architecture Doesn't Work](https://www.youtube.com/watch?v=fz4tax6nKZM "Take me to YouTube")
