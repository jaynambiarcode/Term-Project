# Term-Project
About
The project is based on a tool where the approval of loan is mesured. The loan approval process will have a certain criteria that it is based on 
Overhere I have various categories assigned like
1. Age
2. Job
3. Martial status
4.Education
5. Default- If the person owes any credit to any financial insitution
6. Housing- A housing loan or a existing mortagage
7. Loan- Any existing personal loan


For most of the approval the prospects previous application is checked through
It could be for any of the loans the applicant has filed for. This can be derived from the database.
The loan issuer holds multiple campaigns so as to attract the applicants, this can range from nil to low application fee. 0% APR etc
We would have to take few of these parameters into consideration also. 
In regards to that, we would check few parameters like


8. Contact- last communicated with the issuer 
9. Month: last contacted month of year (categorical: 'Jan', 'Feb', 'Mar', ..., 'Nov', 'Dec')
10 Day of the week: last contact day of the week (categorical: 'Mon','Tue','Wed','Thu','Fri')
11 Duration: last contact duration, in seconds (numeric). Important note: this attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.

##other attributes:
12 - Campaign: Number of contacts performed during this campaign and for this client (numeric, includes last contact)

13 - Pdays: number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)

14 - Previous: number of contacts performed before this campaign for the client (numeric)

15 - poutcome: outcome from the  previous marketing campaign (categorical: 'failure','nonexistent','success')

##social and economic context attributes

16 - emp.var.rate: employment variation rate - quarterly indicator (numeric)
The Organisation for Economic Co-operation and Development defines the employment rate as the employment-to-population ratio. 
This is a statistical ratio that measures the proportion of the country's working age population (statistics are often given for ages 15 to 64) that is employed.

17 - cons.price.idx: consumer price index - monthly indicator (numeric)
A consumer price index measures changes in the price level of a weighted average market basket of consumer goods and services purchased by households. 

18 - cons.conf.idx: consumer confidence index - monthly indicator (numeric)
It is an economic indicator published by The Conference Board to measure consumer confidence,
which is defined as the degree of optimism on the state of the U.S. economy that consumers are expressing through their activities of savings and spending. 

19 - euribor3m: euribor 3 month rate - daily indicator (numeric)
Euribor is short for Euro Interbank Offered Rate. The Euribor rates are based on the average interest rates at which a large panel of European banks borrow 
funds from one another. There are different maturities, ranging from one week to one year.

20 - nr.employed: Number of employees - quarterly indicator (numeric)

Output variable (desired target):
21 - y - has the client subscribed for a term deposit? (binary: 'yes','no')

The data sheet is obtained from various websites of financial insitutions. 

Installation.
1. pip install numpy
2. pip install pd
3. pip install matplotlib
4. pip install seaborn



The following data analysis is done on a Juptyer notebook
While the coding was performed on Google Colab a similar platform like Juptyer
This file is a .ipynb file.
The cosing can be opened on Google Colab by having it stored on ones Google drive account unlike a system space.
Ones it is opened on Colab the directories are set, the file paths are assignned.
The file paths are assigned to location as desired.

Using 
The project involves using of matplt for graphical data representation.
Wherein I have used heatmaps, bar graphs to represent the data. 

In the project I have used various package-management system also called "pip". 
These package manager allow us to perform certain operation which standard libraries in Python cannot execute.
Many of these packages simplify Python development by providing friendly interfaces to functionality that already exists in the standard library. 
For example, one can write a script that retrieves the contents of a web page using only the standard libraries included with Python.

The usage of following pip have been described below
numpy- for adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays. 

matplotlib- This library is used yo construct various graphs, I have used the heat map to depict the eligibilty criteria, 
These kind of graphical representation helps in indentifying certain data analysis in pictorial format which helps in knowing the core region to be undermined and some to
be ceeded. 

seaborn- The usage of seaborn links in with the matlab plot where a data generated in the form graphs and maps give a visualization to the project.\

sklearn- It is a robust library for machine learning in Python. It provides a selection of efficient tools for machine learning and statistical modeling including classification, regression, clustering and dimensionality reduction via a consistence interface in Python. This library, which is largely written in Python.
We use this in conjunction with numpy and matplotlib












































