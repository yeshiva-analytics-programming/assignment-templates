*Aside for learners:*

-------

*It's a good idea to do as much of this assignment as you can before looking at the template -- that way you are building your own Python muscles, and only getting the smallest amount of help as possible.*

*Below, you'll find what an example README could look like.  It's just an idea, so feel free to make your own choices that are different than what's shown here.*

*You'll also see links to files within this folder -- things like pseudocode (optional for you to do), code, and data.  We suggest that if you're stuck in an assignment, you do the following:*

* *Re-read the assignment description in Canvas*
* *Try writing out some pseudocode (logical steps that are small and break down the task, but don't use actual code)*
* *Take a look at the corresponding README in this repository to see if that is enough to help you get un-stuck*
* *Look at the [pseudocode](#pseudocode), to see just the logic, without the code*
* *Only if absolutely necessary: look at the [code sample for .arff](Assignment_6_arff.ipynb) or the [code sample for fixed width](Assignment_6_fixed_width.ipynb)*
* *Problems with GitHub rendering the code sample?  Use the [quick workaround described in this repo's README](../README.md#problems-in-github)
* *Make use of resources like Stack Overflow, to practice how to get help when you're not in a class situation*
* *Still stuck?  Ask for help in Canvas!*

---------


# Module 6

## Problem Description

In this Module, I've been asked to do the following:

### Assignment

***Part 1: .arff***

Create a notebook that:

* Ingests the .arff data found at https://archive.ics.uci.edu/ml/datasets/phishing+websites#
* Note: You'll want to go into the "Data Folder" section to find the Training Dataset.arff file.  Then you can either download that file locally and include that data in your GitHub (maybe in a 'data' subdirectory) or write code in your notebook that will grab the code directly from the website.
* Describes the data using metadata found in the documentation on the same website mentioned above.
* Uses pandas or numpy to support an analysis of the relationship between one or more characteristics and the outcome (phishing / non-phishing).  You might want to do a correlation, for example, or a table that shows a relationship, and describe what you find. 
* Splits the dataframe into two new dataframes -- one for phishing and one for non-phishing websites
* Saves those two dataframes into .csvs for later use
* Make sure you use markdown cells to begin your notebook with an appropriate header and explain to a naive stakeholder what you’re doing along the way.

***Part 2: Fixed Width***

Create a notebook that:

* Ingests fixed-with data at https://catalog.data.gov/dataset/climate-prediction-center-cpc-monthly-u-s-selected-cities-precipitation-summary 
* Note: You'll see two "text file" links, the second of which is what you want (the first one has a broken link!).  Stuck?  Try this link for the data itself: https://www.cpc.ncep.noaa.gov/products/analysis_monitoring/cdus/prcp_temp_tables/mctyprcp.txt.  Then you can either download that file locally and include that data in your GitHub (maybe in a 'data' subdirectory) or write code in your notebook that will grab the code directly from the website.
* Cleans up the data as required, removing any unwanted rows
* Describes the data using metadata found in the documentation on the same website
* Uses pandas to create a more easily read version of the data, with self-documenting variable names
* Aggregates data by state and presents state-by-state precipitation data in a pandas dataframe, in alphabetical order by state name
* Reports to a climate stakeholder which states stand out and why
* Make sure you use markdown cells to begin your notebook with an appropriate header and explain to a naive stakeholder what you’re doing along the way.

## Pseudocode

Here's some logic to help guide me:

First, the .arff part:

* First, I'll create a new notebook for the .arff file ingestion
* Then, I'll check out the documentation and do some Markdown description of the data, before diving in to trying to ingest the data.
* I'll check my textbook and StackOverflow if necessary to learn how to ingest an .arff file
* I'll bring that data into pandas and do a bit of analysis
* Using numpy, I'll do a correlation between one or two variables and my outcome (phishing or not)
* I'll use pandas to split the dataframe into just phishing rows, and save it to a file
* Then I will do the same for non-phishing

And now, the fixed width:

* I'll also create a notebook for the fixed width file
* Then, I'll check out the documentation and do some Markdown description of the data, before diving in to trying to ingest the data.
* I'll check my textbook and StackOverflow if necessary to learn how to ingest a fixed width file
* I'll bring that data into pandas and do a bit of analysis
* Next, I'll clean up the data, renaming variables, removing rows, etc.
* Aggregation comes next: I'll use pandas to group by state and get aggregate data
* I'll draw some conclusions for a naive stakeholder.

