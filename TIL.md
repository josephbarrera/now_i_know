9/20 Mon - I learned SQL Where, Order and Limit functions 
9/21 Tues - Functions + group by = keys to the castle of data
9/22 Wed - Worked on the Join function exercises
9/23 Thur - Worked and learned to approach it line by line
9/24 Fri - Reviewing all the SQL terms and the query order
9/25 Sat - Tried out the Quiz and realized I need to study
9/26 Sun - Went over the Query order and reviwed the material
9/27 Mon - Learned about Subqueries and Temp Tables
9/28 Tues - Learned about Case Statements
9/29 Wed - Continued with Case Statements 
**Will use this code for timestamp data analysis alot:
SELECT emp_no, MAX(to_date) AS max_date
FROM dept_emp
GROUP BY emp_no;**
9/30 Thurs - Took SQL Quiz, created a HackerRank and SQLZoo Repo
10/1 Fri - Started Python Module
10/4 Mon - Functions we see called on objects with the dot syntax are a special function called a “method”. Methods are functions defined on objects (like lists or strings, for example)
- Worked on control_structures: Conditionals (if, else) Loops (for, while, break, continue)
10/5 Tues - Nature is much simpler than all our thoughts about it - Richard Feynman
-started Python functions (arguments, parameters, default values, keyword arguments, calling functions, function scope, lambda)
10/6 Wed - Continued Python functions exercises
10/7 Thur - Went over Python functions exercies, started Python imports of libraries and modules into Python, 
Good book - Ultra Learning (teaches how to learn faster)
10/8 Fri - Started Matplotlib, created graphs using Pyton
10/9 - 10/11 -Played 6 weddings and taught lessons
10/12 Tues - Numpy (IMPORTANT: learn to use vectorized operations and create arrays of booleans to filter results)
10/13 Wed - Numpy exercises and review of numpy
10/14 Thur - Started PANDAS
Good book read - The Signal and the Noise
10/15 Fri - Working with Dataframes module
10/16 Mon - Dataframes module
10/17 Tues - Advanced Dataframes module
10/18 Wed - Started Seaborn and exercises
10/19 Thurs - Continued Seaborn exercises and reviewed for Python assessment
10/20 Fri - Python Assessment, Started spreadsheets
10/25 Mon - Yes, the utility of the data can outweigh its inherent wow factor.  Primarily, people are going to be hiring you to do something with data that *they* want you to take value from, so you essentially have an audience that is already receptive to the material that you are working with.  It may feel dry, but it could be extremely pertinent and actionable in your field, and *that* is your fuel for the storytelling more than the data itself - Madeleine Cooper 
Storytelling module
10/26 Tues - Learned about a scrum/kanban board, started storytelling project
10/27 Wed - Started Tableau module
10/28 Thur - DOCUMENTATION (markdown everything!), make sure a task is done before moving onto another task (don't push a task to the end of the project), employers like to see that you are doing projects on the side
11/1 Mon - Presented Telco Project, started Stats module and Simulation exercises
11/2 Tue - Continued simulation exerices and reviewed, started Probability Distributions
11/3 Wed - Continued Probability Distribution exercises
11/4 Thur - Started Stats - Hypothesis Testing and T-Test
11/5 Fri - Started Correlation in Stats
11/8 Mon - *Document your null and alternative hypothesis
*Document your confidence interval, alpha as well
Started Chi2 (comparing proportions) - expected values need to be higher than 5, otherwise it is sparse
11/9 Tues - Stats Quiz, Classification (Data acquisition)
11/10 Wed - Data Prep
11/11 Thur - Veteran's Day
11/12 Fri - EDA (exploratory data analysis) * If there's a plan or even a chance you will build models with this data, be sure to split the dataset and only explore train. By exploring only train data, we keep from peeking at our out of sample data. If you are absolutely not going to model, it's OK to explore the entire dataset. Any exploration more in-depth than a histogram or .value_counts should only be done on train *
11/15 Mon - Continued EDA
- Adam suggested to not explore too long. Focus on Alt Hypothesis. 
- Pairplot and heatmaps are great for self exploration of data.
- Don't use pairplot and heatmaps for presentations
- Should do Exercise 3 bc it will lead into the Classification Project
- In Tidying, each observation forms a row
- Seaborn likes the melted "long" up and down format
11/16 Tues - Learned Splitting data and Evaluation data. Baseline prediction (Coffee) or in TelCo data (churn vs. no churn) 
11/17 Wed - Started Modeling (Decision Tree)
(Zynga, Farmville, In a work environment, set up expectations about "accuracy". 96% is highly accurate after after training and validating models