# Assignment: Collaborative Machine Learning Project

## Objective
In this assignment, you will work with a colleague(s) to build a simple baseline Machine Learning model. One student will focus on feature engineering, while the other will develop the model. You will work on separate Git branches and then merge your work.

## Steps
- One student creates a new repository for your work and adds the colleague.
- Choose a dataset to work on on Kaggle.com. Can be a Classification or Regression problem. Try to work with a dataset that has under 100mb.
- Add the file to repo.
- Create a branch with your name.
- Your partner should do the same.
- Pull your branch to your computer using VSCode / Git Desktop and switch to it.

# Feature Engineering (Student 1)

- Create a new Python file: feature_engineering.py.
- Write functions to clean the dataset and create relevant features.
- Push your changes to your branch.

# Model Training (Student 2)

- Create a new Python file: train_model.py.
- Import the functions from feature_engineering.py. If your colleague hasn't pushed yet, use the original dataset until feature data is ready.
-  Train a simple baseline model (e.g., Logistic Regression, Decision Tree, or another simple model).
- Push your changes to your branch.

# Combining Work

- One student needs to combine the work on the main branch. The other needs to do the Pull Requests from the branches you've created.
- Merge both individual branches into this branch.
- Ensure that the code works together without errors.
- Push the merged branch to the repo.
- Do a pull request to the main branch.
- In the PR description, briefly explain your roles and what was done. Make one of the students as the reviewer.

## Guidelines
- Most of your code should be in .py files instead of a Jupyter Notebook.
- Use a notebook only for testing and visualization if necessary.
- Use functions and modular code to keep the project clean.
- Communicate with your partner to avoid merge conflicts.

💡 Bonus Challenge: If you finish early, try improving your model or adding evaluation metrics!
