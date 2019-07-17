you can before looking at the template -- that way you are building your own Python muscles, and only getting the smallest amount of help as possible.*

*Below, you'll find what an example README could look like.  It's just an idea, so feel free to make your own choices that are different than what's shown here.*

*You'll also see links to files within this folder -- things like pseudocode (optional for you to do), code, and data.  We suggest that if you're stuck in an assignment, you do the following:*

* *Re-read the assignment description in Canvas*
* *Try writing out some pseudocode (logical steps that are small and break down the task, but don't use actual code)*
* *Take a look at the corresponding README in this repository to see if that is enough to help you get un-stuck*
* *Look at the [pseudocode](#pseudocode), to see just the logic, without the code*
* *Only if absolutely necessary: look at the [code sample](Assignment_10.ipynb)*
* *Problems with GitHub rendering the code sample?  Use the [quick workaround described in this repo's README](../README.md#problems-in-github)
* *Make use of resources like Stack Overflow, to practice how to get help when you're not in a class situation*
* *Still stuck?  Ask for help in Canvas!*

---------

## Pseudocode

Here are the steps we're doing in this module, according to the description for the Module 10 Muscle Builder:

* Ingest some rows of your final project data into a pandas DataFrame.  You can use the Socrata API to just select a limited number of rows (maybe half a million?)
* Choose a variable in your data that has a reasonable (say, 2-10) number of values.  Maybe it's sex, or year, or borough.  You can also create a variable using binning, if you need to (using quartiles or something similar).
* Use that variable to conduct some aggregation.  You could compute the mean or median of a continuous variable, for example (What's the mean age?  The median fine or penalty?), or the frequency of a categorical variable (What percent are cat owners?  What are the top three favorite fruits?)
* Explain your findings -- what do the values that come out of your aggregation actually mean?
* Use markdown to show your thinking as you go along -- even a short assignment like this one deserves a literate statistical programming approach!
