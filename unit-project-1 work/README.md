# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project #1: Research Design Write-Up
DS | Unit Project 1

### PROMPT

"A problem well-stated is half-solved" -- Charles Kettering

Welcome to Data Science! In this first project you will create a framework to scope out data science projects. This framework will provide you with a guide to develop a well-articulated problem statement and analysis plan that will be robust and reproducible.

**Goal:** Create a structured Jupyter notebook using markup language to describe the dataset you are using and the exploratory analysis you plan to pursue.

Note: You'll be working with two scenarios in this project and one dataset.

---

### DELIVERABLES

#### Completed Jupyter Notebook

- **Requirements:**
    - Identify features of the dataset, including identifying the outcome variable and covariates/predictors.
    - Create a data dictionary that lists feature names and data types (gives an at-a-glance understanding of what the data includes)
    - Write a high quality problem statement 
    - State any risks and assumptions of your data
    - Outline the exploratory analysis methods you need to use to understand the relationships and trends in your data

- **Bonus:**
    - Practice writing an alternative problem statement for your dataset
    - Articulate the risks and assumptions of this alternative model

- **Submission:**
    - TBD by Instructor 

---

### TIMELINE

| Deadline | Deliverable| Description |
|:-:|---|---|
| Class 4 | Project 1  | Research Design Write-Up in Jupyter Notebook   |

---

### EVALUATION

Your project will be assessed using the following standards:

1. Identify the Problem

#### Rubric: [Click here for the complete rubric](./project1-rubric.md). 

Requirements for these standards will be assessed using the scale below:

|Score | Expectations|
|----- | ------------|
|**0** | _Incomplete._|
|**1** | _Does not meet expectations._|
|**2** | _Meets expectations, good job!_|
|**3** | _Exceeds expectations, you wonderful creature, you!_|

While your total score is a helpful gauge of whether you've met overall project goals, __specific scores are more important__ since they'll show you where to focus your efforts in the future!

---

### RESOURCES

#### Dataset  
We'll be using the same Admissions.csv dataset to explore logistic regression in Python. We will be following the same basic modeling as explained in [yhat's blog](http://blog.yhat.com/posts/logistic-regression-and-python.html), so you can get an overview of the simple way they load the data, explore the data, fit a logistic model and evaluate the model. 

The problem/goal for this dataset is to identify factors that may influence admission into graduate school. You will see that the data contains four variables/features: admit, gre, gpa, rank.

- 'admit' is a binary variable. It indicates whether or not a candidate was admitted admit =1) our not (admit= 0)
- 'gre' is GRE score
- 'gpa' stands for Grade Point Average
- 'rank' is the rank of an applicant's undergraduate alma mater, with 1 being the highest and 4 as the lowest

Dataset: [Admissions.csv](./datasets/admissions.csv)

#### Starter code
For this project, you will be using a Jupyter notebook. Notebooks are a handy way to communicate your research with your team and share your analysis. Using markup syntax will allow you create more visually appealing notebooks.

* Open the [starter code instructions](./code/project1-starter.ipynb) in iPython notebook.

#### Sample Deliverables 
Check out the example notebook in our starter code, which includes a data dictionary and answers to the same questions you will need to answer on your own using the Admissions.csv dataset. Wonder how to format your notebook the same way? Simply double-click on any section in the example notebook to view the markdown language.

![Example Notebook](./code/project1-example.ipynb)

#### Suggestions for Getting Started 

- Get used to the Jupyter Notebook layout. Play around with keyboard shortcuts.
- Try out basic markdown for commonly used formats; look up commands for headers, bold, italic, tables.
- **Read docs for Jupyter Notebooks.** Most of the time, there is a tutorial that you can follow, but not always, and learning to read documentation is crucial to your success as a data scientist!

### Additional Links

- [Markdown Cheat Sheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

---
