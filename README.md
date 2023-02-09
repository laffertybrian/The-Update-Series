# The-Update-Series
### Updating my first data science project.

As I continue to learn and grow in this field, I want to be able to try and practice the new ideas I come across. This repository will take these ideas and apply them to my first [project](https://github.com/laffertybrian/food-sales-predictions).

### #1 Update:
  
After reading [this](https://towardsdatascience.com/benchmarking-machine-learning-models-with-cross-validation-and-matplotlib-in-python-4957a41149e) article from Toward Data Science, I was inspired to create a Python class to compare and evaluate multiple models at once. I wanted to go a bit beyond what the author had provided and adapted the code to not only evaluate multiple models, but also allow for assessing multiple metrics. Since, not all problems are the same having the ability to choose what metric is evaluated could be helpful. Because there are multiple models I had the class return a Pandas DataFrame for easy viewing. I also added a min/max function to the class to easily show the models that preformed the best. 

#1 Update Conclusion: Adding this class would have helped me improve my first project. Using the class, with 7 models, I was able to get a R^2 score that was 3% better than my initial project R^2. I would have selected a different model to tune, and this could have directly improved the outcome of the project. Also, the ability to see the fit and score times provides another layer of information from which to make business decisions. The ability to quickly assess the dataset with multiple models would have started me on a different path.
