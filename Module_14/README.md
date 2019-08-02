*Aside for learners:*

-------

*It's a good idea to do as much of this assignment as you can before looking at the template -- that way you are building your own Python muscles, and only getting the smallest amount of help as possible.*

*Below, you'll find what an example README could look like.  It's just an idea, so feel free to make your own choices that are different than what's shown here.*

*You'll also see links to files within this folder -- things like pseudocode (optional for you to do), code, and data.  We suggest that if you're stuck in an assignment, you do the following:*

* *Re-read the assignment description in Canvas*
* *Try writing out some pseudocode (logical steps that are small and break down the task, but don't use actual code)*
* *Take a look at the corresponding README in this repository to see if that is enough to help you get un-stuck*
* *Look at the [pseudocode](#pseudocode), to see just the logic, without the code*
* *Only if absolutely necessary: look at the [code sample](Assignment_14.ipynb)*
* *Problems with GitHub rendering the code sample?  Use the [quick workaround described in this repo's README](../README.md#problems-in-github)
* *Make use of resources like Stack Overflow, to practice how to get help when you're not in a class situation*
* *Still stuck?  Ask for help in Canvas!*

---------

## Pseudocode

Here are the steps we're doing in this module, according to the description for the Module 14 Optional Muscle Builder.  We're going to do a logistic regression model, using a dichotomous categorical value for the outcome.

* Ingest some of your data (or all of it!) into a pandas dataframe.
* You do not have to worry about making a split between training and test data for this assignment.
* Select (or create) an "outcome" or "dependent" variable that falls into one of the following categories:
  - It has a dichotomous categorical value ("Yes", "No" / "Pass" , "Fail, etc.)
  - It is a continuous numerical value
* For dichotomous categorical values, create a logistic model using scikit learn.  It can be very simple, with just one or two "independent" or "explanatory" variables.  Your model does not have to perform well!
* For a continuous numerical outcome, create a linear model using scikit learn.  Again, it can be very simple, with just one or two  "independent" or "explanatory" variables.  Your model does not have to perform well!
* With your model, try predicting the outcome variable using the same data you used to fit the model.  
* Describe the accuracy of your model.
