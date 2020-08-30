# Case Study: Absenteeism-at-Work


The purpose of the business exercise will be to explore whether a person presenting certain characteristics is expected to be away from work at some point in time or not. In other words we want to know for how many working hours an employee could be away from work based on information such as how far they live from their workplace, how many children and pets they have, Do they have higher education and so on.

> Data: As a data source for our analysis, we will use Secondary data which is based on the dataset of an already existing study about the prediction of absenteeism at work. This means that the business exercise we will go through will be realistic and obtained skills have 100 percent application in the business world.

> Reasearch Question: We would like to know whether or not an employee can be expected to be missing for a specific number of hours in a given work day.

Having such information in advance can improve our decision making how by reorganizing the work process in a way that will allow us to avoid a lack of productivity and increase the quality of work generated in our firm.

Definition of absenteeism: The absence from work during normal working hours resulting in temporary incapacity to execute regular working activity.


### Data Preprocessing:

First, we will preprocess the data. We will start working on the ‘Absenteeism_data.csv’ file and take it to a usable state in a machine learning algorithm.

### Machine Learning:

Based on Preprocessed data we will develop a model that will predict the probability of an individual being excessively absent from work. For our case study, this will be a logistic regression model. Numerous machine learning tools and techniques will help us at this stage. At the end, we will store our work as a Python module that we will call ‘absenteeism_module’ and will thus preserve it in a form suitable for further analysis.

 
This exercise is designed first of all to practice Data Preprocessing and Logistic Regression. 

Below you can find an information about the dataset.

* ID: Individual Identification
* Reason for Absence: We have overall 28 Reasons for Absence in our list which are presented in a column categorized as numbers. Certain reasons formulate a grouls which you can see below.

Group 1 (1 to 14) Certain Infectious and Parasitic diseases 
Group 2 (15, 16, 17) Diseases of the nervous system
Group 3 (18, 19, 20, 21) Pregnancy and Childbirth
Group 4 (22 to 28) Patient follow-up
* Date: Date of Absence
* Transportation Expense: Costs related to business travel such as fuel, parking	
* Distance to Work: Measured in kilometers
* Age: Years of age
* Daily Work Load Average: Measured in minutes
* Body Mass Index
* Education: A categorical variable, representing different levels of education
* Children: Number of children in the family
* Pets: Number of pets in the family	
* Absenteeism Time in Hours
