*Aside for learners:*

-------

*It's a good idea to do as much of this assignment as you can before looking at the template -- that way you are building your own Python muscles, and only getting the smallest amount of help as possible.*

*Below, you'll find what an example README could look like.  It's just an idea, so feel free to make your own choices that are different than what's shown here.*

*You'll also see links to files within this folder -- things like pseudocode (optional for you to do), code, and data.  We suggest that if you're stuck in an assignment, you do the following:*

* *Re-read the assignment description in Canvas*
* *Try writing out some pseudocode (logical steps that are small and break down the task, but don't use actual code)*
* *Take a look at the corresponding README in this repository to see if that is enough to help you get un-stuck*
* *Look at the [pseudocode](#pseudocode), to see just the logic, without the code*
* *Only if absolutely necessary: look at the [code sample](Assignment_9.ipynb)*
* *Problems with GitHub rendering the code sample?  Use the [quick workaround described in this repo's README](../README.md#problems-in-github)
* *Make use of resources like Stack Overflow, to practice how to get help when you're not in a class situation*
* *Still stuck?  Ask for help in Canvas!*

---------

## Pseudocode

Here are the steps we're doing in this module, according to the description for the Module 9 Muscle Builder:

* Use pd.read_csv to ingest https://data.cityofnewyork.us/Health/Community-Health-Survey/2r9r-m6j4
* Use pandas methods (.info, .describe, .dtypes, etc.) to understand data more fully.
* Use pandas column selection to make DataFrame with just "Year",  "Question" and "Prevalence" columns.
* Use pivot, twice:
  -  First, make the question text the column header, and the year the row index
  - Next, make the year the column header, and the question text the row index
* Use Markdown to explain data, code, and next analytic steps.
