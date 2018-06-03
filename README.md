## Creating a multi-sports event dashboard in Microsoft PowerBI ##

This demo will provide an introduction in  
- loading flat files (.csv) into PowerBI 
- creating New Measures in PowerBI
- creating custom sorting order in PowerBI
- creating different visualisations to build a dashboard 

The data used are pre-scraped from the 8th Asean ParaGames website using the free tier of [import.io](https://www.import.io/)  

### Part 1: Inserting Data - medals.csv ###

Load the flat files into PowerBI by clicking on "Get Data" > "Text/CSV" > and select "medals.csv".

![jpg](images/InsertData.jpg)

On the preview window click on the "load" button to import the data into PowerBI

![jpg](images/InsertData2.jpg)

### Part 2: Inserting Data - medalSort.csv ###

Repeat the steps in **Part 1** and import the medalSort.csv data into PowerBI

Navigate to the **Relationship Viewer** last tab on the left hand panel to see the relationship between the two loaded dataset

### Part 3: Creating New Measures ###

Four new measures needs to be created in order to present the information in the final dashboard
- total event count
- total medal count
- cumulative event count
- cumulative medal count 

Navigate to the **Query Editor** middle tab on the left hand panel and add the four new measures to the medal dataset as shown below:

**total event count**
![jpg](images/NewMeasure-EventCount.jpg)

**total medal count**
![jpg](images/NewMeasure-MedalCount.jpg)

**cumulative event count**
![jpg](images/NewMeasures-CumulativeEventCount.jpg)

**cumulative medal count**
![jpg](images/NewMeasures-CumulativeMedalCount.jpg)

