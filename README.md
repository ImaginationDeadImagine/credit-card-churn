# Credit Card Churn (C3): in search of explanatory variables

**C3** is a data analysis project inspired by the intuition of a bank manager that attrition rates (hereinafter referred to as 'churn') are increasing amongst the bank's customers.  The aim of the project is to investigate with exploratory data analysis whether there are explanatory variables within the dataset that might predict churn for cohorts of customers. 

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

## Dataset Content

* The dataset comprises 10,127 customer records in a .csv file of 1.476 MB.
The fields within an individual record included:

| Variable |
|-----------|
| CLIENTNUM |
| Attrition_Flag |
| Customer_Age |
| Gender |
| Dependent_count |
| Education_Level |
| Marital_Status |
| Income_Category |
| Card_Category |
| Months_on_book |
| Total_Relationship_Count |
| Months_Inactive_12_mon |
| Contacts_Count_12_mon |
| Credit_Limit |
| Total_Revolving_Bal |
| Avg_Open_To_Buy |
| Total_Amt_Chng_Q4_Q1 |
| Total_Trans_Amt |
| Total_Trans_Ct |
| Total_Ct_Chng_Q4_Q1 |
| Avg_Utilization_Ratio |
| Naive_Bayes_Classifier_Attrition_Flag_Card_Category_Contacts_Count_12_mon_Dependent_count_Education_Level_Months_Inactive_12_mon_1 |
| Naive_Bayes_Classifier_Attrition_Flag_Card_Category_Contacts_Count_12_mon_Dependent_count_Education_Level_Months_Inactive_12_mon_2 |

## Business Requirements

* The bank would like to identify predictive variables within its dataset to help identify customers likely to churn so that efforts might be directed towards retaining them as customers.

## Hypothesis and how to validate?

* The null hypothesis is that there are no variables within the bank's dataset that can predict churn.
* The alternative hypothesis claims that there are individual variables which are predictive of churn.
* The initial phase of the project will consist of exploratory data analysis with the aim of identifying predictive variables. 

## Project Plan

* The provided dataset was cleaned prior to analysis.  The cleaning steps were carried out in the attached Jupyter Notebook, C3_Notebook.ipynb.
* The steps were carried out using pandas and the data processed was contained in the BankChurners_clean.csv file.
* The data was managed throughout the collection, processing, analysis and interpretation steps by interacting with the stored data via Jupyter Notebooks.
* I chose the research methodology that I used, exploration of the data, because it was within the limitations of my current skills.

## The rationale to map the business requirements to the Data Visualisations

* There was a single business requirement: identify variables in the dataset that might be used to predict credit card churn.
* The methodology, albeit limited, was to compare churned and non-churned customer data, particularly to see if there were substantial differences in boxplot medians.
* Future analysis might consider tests of statistical significance for identified variables, rather than relying on subjective assessments as used in the present study.

## Analysis techniques used

* Data cleaning was largely unnecessary as the original dataset was already clean.  However, two columns (the Naive Bayes columns) were dropped from the dataset as they appeared to be derived columns and not part of the original data.  A limitation of the original dataset is that it does not appear to have been designed with the present study in mind, although it has produced results that can inform further analysis.
* The data analysis techniques, such as the ETL, were structured based on techniques presented by Code Institute.  This was also the case for the visualisations.
* I did not feel limited by the data for the study.  I believe the project results answered the remit.  Further work can now be done to extend the analysis, such as modelling relationships between combinations of identified variables.
* The generative AI tool that I used throughout the project was Perpelexity.  It got me through a rough patch when I couldn't understand why modules such as seaborn and matplotlib, that appeared to have been successfully imported, were not found by my code.  Perplexity led me to the source of the problem: I had not activated my virtual environment.  With that out of the way, I relied on Perplexity to hold my hand through a rushed analysis, especially in plotting multiple plots at once, rather than tediously plotting each variable by hand, for which I had no time.

## Ethical considerations (optional)

* Were there any data privacy, bias or fairness issues with the data?
* It could have been stated that there were no data privacy issues with the data, either in the jurisdictions where it was collected, or stored.
* How did you overcome any legal or societal issues?
* I took it on trust that for this project, Code Institute would not have given a project with such issues.

## Unfixed Bugs

* There appear to be several unfixed bugs in my cranium, which I continue to work on.
* There were definite gaps in my practical knowledge, particularly when it came to activating my virtual environment.  I failed to do that and was led on a merry dance of errors before turning to Perplexity which helped resolve the situation.


## Development Roadmap

* The challenges I faced were largely of my own making.  As noted above I had to rely on Perplexity to dig myself out of a hole wherein I had neglected to activate my virtual environment, and was left wondering why requirements had installed but modules were not found inside VS Code.
* What new skills or tools do you plan to learn next based on your project experience?  Stress management - this experience has been highly stressful and I felt like giving up entirely.  I was helped by a colleague who got me through the worst of that.

## Main Data Analysis Libraries

* Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.

## Credits

### Content 

I could not have done this project, certainly in the time available, without the assistance of the generative AI, Perplexity.

## Acknowledgements

* I have received support and encouragement (even if they didn't know it!) from my data coaches, Emma and Marko, and tutors, Kevin and Rory.  I am also grateful for the work of past tutors in providing foundational material.
* My colleagues, including the curmudgeon Phil and especially Hema, who got me back on the horse, deserve special mention for helping me to retain my sanity (although some might disagree.)