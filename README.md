# Machine-Learning-s21-Project
Repository of all project documentation and Code

Remember to commit and push any time you finish a chunk of work. 

Tasks:

Part A:  Create a notebook called initial_exploration

Python: Pull in a data set and look at it.
Markdown:  Did you discover interesting relations?
Markdown:  What feature/s would you like to be able to predict?
Python: Clean the data
Python: Create training/test sets


Part B: Create a notebook called linear_regression

Python: Initial data prep section.  Read, clean and create sets.
Markdown: Pick an initial set of features for X and the target feature y.  Explain why you made this choice.
Python: Do a linear regression on X and y.  Compute metrics.
Markdown: Comment on the results.
Python: See if you can do better.
Python: Do a final evaluation with the test set.
Markdown: Look at the parameters you found and discuss what you have learned.


Part C: Update the README to give an overview of the state of your project.  Comment on each of the notebooks and any important results.




Updates:

   Part A, interesting correlations are that there are no correlations. I might need to reevaluate my project.
   
   I would like to predict the profit based on company and budget 
   
   Given the example of Disney's "John Carter" being the biggest bust (-200mil) and Disney's (Disney owned companies) Starwars, Avatar, Titanic, and Avengers (4/5 of the most profitable movies at 400-700mil profit each), there is a clear discrepency in company and profit.
   
   As for most other factors things such as Disney's Pirates of the Carribean (2 instances) being some of the highest budget movies despite the profit range of 9mil to -9mil, it is a little hard to find correlations and that's within a single company. The 9mil-->-9mil profit range is with the same company, same star actor, same writer, and a 80% similar budget. The budget and company have almost nothing to do with the success of a movie
   
   
   Part B, The linear regression confirmed what I already knew, there is no correlation, my intended topic is a complete bust, not as much as John Carter though lmao. I need to find a new dataset and restart the project. The bias of my regression is 5.6million, with the coefficient being 0.145. neither in which are acceptable
    
    
   Part C:
       My project is dead in the dirt and I need to restart. My issue is that other datasets that are good are too large, I will see what sklearn can do even if it is going to be difficult can't exactly restart :(
       
       
Part D:  Create a notebook called classification

Python: Initial data prep section.  Read, clean and create sets.

Markdown: Pick an initial set of features for X and the target feature y.  Explain why you made these choices.  (Note, A target that is continuous can be made discrete by creating buckets that hold a range of values. For example: If you have a feature time_of_day that ranges from 0 to 23:59, you can create 24 buckets for each of the hour intervals, 0 to 0:59, 1 to 1:59, etc.)

Python: Do a decision tree on  X and y.  Compute metrics.

Markdown: Comment on the results.

Python: See if you can do better using SVM or some other multi-classifier.

Python: Do a final evaluation with the test set.

Markdown: Look at the parameters you found and discuss what you have learned.

Part E: Update the README to give an overview of the state of your project.  Comment on each of the notebooks and any important results.