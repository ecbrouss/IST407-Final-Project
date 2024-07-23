## Mason, Lauren, Daniella, Devyn, Erin

## Motor Vehicle Collisions - Crashes
https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95

## Machine Learning-Assisted Motor Vehicle Crash Analysis: Creating a Safer City

## What are you trying to do? Articulate your objectives using absolutely no jargon.
We’re aiming to improve the safety of drivers and pedestrians in NYC by utilizing machine learning techniques to discover crash trends/patterns and identify high risk zones. We specifically want to develop predictive models that will utilize the dataset’s key features to predict events such as injury severity/death toll for a crash and to predict areas and times of especially high risk.

## How is it done today, and what are the limits of current practice?
Currently, analysis is done manually, using standard statistical analysis without the assistance of ML techniques. This limits the ability to consume large amounts of data and relies too heavily on human expertise as opposed to letting the computer do the processing. Doing it this way can result in missing complex patterns that may not be obvious due to the sheer size of the dataset.

## What is new in your approach and why do you think it will be successful?
Our approach aims to integrate machine learning techniques to create predictive models in real time using the NYC dataset. This will enable us to quickly identify high risk zones and how they change over time as new data is entered into the dataset. We believe it will be successful because of the nature of machine learning, which functions better with datasets that contain a lot of data. Being updated consistently while containing over 2 million crash reports indicates that using predictive models will have an immediate impact.

## Who cares? If you are successful, what difference will it make?
If we are able to be successful, there will be a profound impact for both stakeholders and those residing in NYC. Law enforcement will be able to reduce response time when they’re aware of areas at a higher risk for an incident, leading to a stronger understanding of the high risk areas and reducing time needed to recover from the incident. Outside of stakeholders, the citizens of New York City benefit the most, directly benefiting from an increase of overall road safety and a reduction in injuries/deaths resulting from crashes in NYC. The differences include an overall improvement to citizen safety, increased optimization in city resources, and a reduction in both the number and severity of accidents. 

## What are the risks?
Model Bias--our predictive model could rely too heavily on historic data as opposed to more recent data, resulting in allocation in the wrong areas. There could also be an overreliance on the ML, which would ignore the human expertise of those who live in the city and understand high risk areas. There could also be a data quality issue, where bad data is inputted into the model.
## How will you acquire data? Ideally, you will have already identified a data source and will have verified that it has sufficiently "interesting" data. Data can be interesting for a variety of reasons, including:
#### There's a lot of it (>50000 rows)
#### There are many features (>10 columns)
#### The features covers a variety of different kinds of variables
#### The data addresses an inherently interesting topic.

Our data comes from the NYC OpenData website, found on data.cityofnewyork.us at this link: https://data.cityofnewyork.us/Public-Safety/Motor-Vehicle-Collisions-Crashes/h9gi-nx95
Our dataset contains 2,000,000+ rows with a significant (28) number of columns, which contain both categorical and numeric variables.

## 3. Include a weekly project timeline. What do you expect to have done at the end of each week? 

Week 9: Shared understanding of dataset, variables, and overall direction.
Week 10: 
Week 11: Re-draft Proposal, Work on Project 2
Week 12: Project Checkpoint 2 deliverable. 
Week 13: BREAK
Week 14: (presentation, 12/6)
Week 15: (presentation, 12/11)
Project Report Due: 12/18

## 4. How will you coordinate your work? Have a plan that everyone will contribute do. Avoid plans where individuals work serially, one after the other, as this will inevitably lead to cascading failures. Also include information about how you will coordinate - will there be a weekly check-in? Or will you communicate on an ad-hoc basis?

Collaborate ideas and work progress through a shared google doc. Most likely ad-hoc basis. We will communicate through a groupchat where we will check in with each other every couple of days to make sure we are all staying up to task. Work will be delegated based on personal skills and schedules. 

# Group Project Checkpoint 2 Rubric

For the second checkpoint, you will have identified your data and developed a descriptive analysis. This will be contained in a markdown file called 'checkpoint2_data_analysis.ipynb' that includes:


1.	Distributions (where appropriate)
2.	Analysis of missing data and outliers
3.	Plans for cleaning, including imputation, scaling, encoding, and other feature transformations
4.	Any data enrichment you have done or plan to do (e.g., bringing in new datasets)
5.	Initial analysis of feature importance (if classification)
6.	Observations about correlation in the data or other notable statistical features

In addition, your second checkpoint should now specify your refined focus, incorporating feedback and new understandings gleaned from the data. This part of the submission will be presented in a markdown file called 'checkpoint2_narrative.md.' Explain how you have incorporated feedback from me ( and / or peers). Additionally, you should now have a revised project plan, and an analysis of how your activities have conformed to your previous plan.

This checkpoint is worth 7 points on your final grade, two of which come from teammates evaluations. The remaining five points are apportioned as follows:

2 points - quality and clarity of data analysis. Did you address the above points? Is your submitted notebook well organized and complete?
2 points - Insights and clarity of plan moving forward. Do I understand what you are doing? Have you addressed points of feedback? Does your proposed plan take into account the reality of your data?
1 point - Do you have a concrete plan moving forward? Is it realistic? Does it specify who is doing what?
