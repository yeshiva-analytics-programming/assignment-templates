*Aside for learners:*

-------

*It's a good idea to do as much of this assignment as you can before looking at the template -- that way you are building your own Python muscles, and only getting the smallest amount of help as possible.*

*Below, you'll find what an example README could look like.  It's just an idea, so feel free to make your own choices that are different than what's shown here.*

*You'll also see links to files within this folder -- things like pseudocode (optional for you to do), code, and data.  We suggest that if you're stuck in an assignment, you do the following:*

* *Re-read the assignment description in Canvas*
* *Try writing out some pseudocode (logical steps that are small and break down the task, but don't use actual code)*
* *Take a look at the corresponding README in this repository to see if that is enough to help you get un-stuck*
* *Look at the [pseudocode](#pseudocode), to see just the logic, without the code*
* *Only if absolutely necessary: look at the [code sample](Assignment_15.ipynb)*
* *Problems with GitHub rendering the code sample?  Use the [quick workaround described in this repo's README](../README.md#problems-in-github)
* *Make use of resources like Stack Overflow, to practice how to get help when you're not in a class situation*
* *Still stuck?  Ask for help in Canvas!*

---------

## Pseudocode

Here are the steps we're doing in this module, according to the description for the Module 14 Optional Muscle Builder.  We're going to do a logistic regression model, using a dichotomous categorical value for the outcome.

* Ingest some of your final project data into a pandas DataFrame
* Split your data into training data (what you use to train your model) and testing data (what you use to see if your model is any good).  We suggest a 70/30 split, but you're welcome to do a different split if you think it's a better choice.
* Use scikit learn to do some simple machine learning on your data.  We suggest a simple Decision Tree -- chose an outcome like "resolved in less than a week" vs. "resolved after a week or more" and use a tree algorithm to make predictions!
* Evaluate your model and describe its accuracy.
* Throughout this exercise, use Markdown to describe your decisions and code.
* Commit your code and any ancillary files (like a README) to a Module 15 folder in a public GitHub repository and give your instructor a link to the repo.
