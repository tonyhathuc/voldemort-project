# voldemort-project
Mid - bootcamp project for Ironhack


Skip to content
Search or jump to…

Pull requests
Issues
Marketplace
Explore
 
@tonyhathuc 
Tognolia
/
Voldemort-Project
1
0
0
Code
Issues
Pull requests
Actions
Projects
Wiki
Security
Insights
Voldemort-Project
/
README.md
in
main
 

Spaces

2

Soft wrap
1
# Voldemort-Project
2
## Team : Tony - Jerrit - Andrea
3
### *April 2021*
4
​
5
Project exploring data cleaning, Visualisation and Analysis of Credit Card for marketing strategy planning.
6
​
7
## Content
8
​
9
- [Project Outline](#project-outline)
10
- [The Data](#the-data)
11
- [The Database](#the-database)
12
- [Visualisation](#visualisation)
13
- [Statistical Analysis](#statistical-analysis)
14
- [Delivering Insight](#delivering-insight)
15
- [Next Steps](#next-steps)
16
​
17
## Project Outline
18
​
19
This repository contains the group project by the Lily Potter team for the Ironhack Mid-Bootcamp Project. Our objective was to understand the features and other characteristics of the bank's customers comparing those who accept a credit card offer and those who do not.
20
​
21
## The Data 
22
​
23
The dataset was checked for duplicates.
24
The identifier field (Customer Number) was dropped.
25
The data columns were checked for null values. Null values were present in the numerical features were dropped since represent less than one percent of the total.
26
The data type of each column was checked. 
27
The unique values and distribution of each categorical feature were checked.
28
The distributions of each numerical variable were checked. The data fields Credit Cards Held, Homes Owned, Household Size, Bank Accounts Open were of numeric data type but are in fact categoricals so they will be treated as categories in our analysis.
29
Numericals variables were checked for correlation un´sing heatmap and some were dropped due to high redundancies.
30
Data columns were renamed and stylized as snake_case.
31
Checking the target variable unique values we have seen that the data were strongly unbalanced. We will deal with this during the several iterations later.
32
​
33
​
34
​
35
## The Database
36
​
37
The marketingcreditcard.csv file has been imported in to SQL workebench in order to answer to some questions related to the groupwork.
38
​
39
### [SQL](https://github.com/Tognolia/Voldemort-Project/tree/main/sql)
40
.sql query file with query results in file annotations. 
41
​
42
## Visualisation
43
​
No file chosen
Attach files by dragging & dropping, selecting or pasting them.
@tonyhathuc
Commit changes
Commit summary
Create README.md
Optional extended description
Add an optional extended description…
 Commit directly to the main branch.
 Create a new branch for this commit and start a pull request. Learn more about pull requests.
 
© 2021 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
