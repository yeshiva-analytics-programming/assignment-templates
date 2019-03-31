*Aside for learners:*

-------

*It's a good idea to do as much of this assignment as you can before looking at the template -- that way you are building your own Python muscles, and only getting the smallest amount of help as possible.*

*Below, you'll find what an example README could look like.  It's just an idea, so feel free to make your own choices that are different than what's shown here.*

*You'll also see links to files within this folder -- things like pseudocode (optional for you to do), code, and data.  We suggest that if you're stuck in an assignment, you do the following:*

* *Re-read the assignment description in Canvas*
* *Take a look at the corresponding README in this repository to see if that is enough to help you get un-stuck*
* *Look at the [pseudocode](#pseudocode), to see just the logic, without the code*
* *Only if absolutely necessary: look at the [code sample](Assignment_5.ipynb)*

---------


# Module 5

## Problem Description

In this Module, I've been asked to do the following:

You are a data analyst for a brand-new New York City energy efficiency program.  Your role at this early stage of the project is to gather, explore, and describe the data coming from NYC data providers.  You should make a Jupyter notebook that is aimed at an intelligent layperson -- someone who isn't a data analyst like you.  They should understand what you're doing and why it matters, even if they don't totally understand the code itself.

Create a notebook that:

* Includes a DataFrame created by importing data from the New York City data portal.  Since we haven't covered data ingest formally yet, please include the following code that will import this data directly:
nyc_gas =  pd.read_csv("https://data.cityofnewyork.us/api/views/uedp-fegm/rows.csv?accessType=DOWNLOAD")
* Includes series and dataframe operations to determine:
  - The size of the data
  - The column labels.  Are there problematic or surprising column labels?  What would you suggest for column labels to use instead?  Rename the DataFrame with new labels that will be easier to use.  Use pd.DataFrame.rename to do this.  You may have to search online or use the question mark help utility in python to get the details on how to use rename.  This is an intentional stretch beyond what was covered in the chapter.
  - How many distinct building types are included, and their median energy consumption (in GJ).  Are there building types that should be combined?   One method you might consider (although you can use more advanced techniques if you want) is to make new data frames for each building type, then analyze these 'daughter' data frames.
  - What building type has the highest median GJ consumption?  The lowest?  Are you surprised?
  - How many utility data reporters are included, and the mean and standard deviation of their energy consumption.
* Suggestions for data improvement.  You may have noticed a few things that could have been done better in the data collection.  Mention them!

## Pseudocode

Here's some logic to help guide me:

* First, get the data, using the provided command.
* Use `head`, `shape`, and `columns` methods to do an initial first pass at looking at the data
* Use `rename` to change column labels.  I suspect they will be kind of bad, given the assignment description, so I should come up with better label ideas.
* Figure out how many building types there are, using `unique`
* For each building type:
  - Make a new DataFrame that includes only that building type
  - Isolate the consumption in GJ column and find the median value
* From all those building types, figure out which one has the highest and lowest median value
* Figure out how many utility reporters there are, using `unique`
* For each utility reporter:
  - Make a new DataFrame that includes only that utility
  - Get the mean and standard deviation of the GJ column
* Along the way, note things that surprise me or are difficult to work with, since I'm supposed to make suggestions for improvement for data collection.  

