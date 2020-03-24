## Project Info 
In this project, we analyzed the trends after CPDB (Citizens Police Database) went public and compared it with the trends before the release of CPDB. The main project highlights are as follows: 
### Relational Analytics, Data Cleaning and Integration  
**Tools used:** PostgreSQL, Trifacta, Pandas<br>
We used SQL to analyze the segregation of complaints by officer rank, incidents carried out by off-duty cops and their segregation by area, impact of investigator's race on the outcome of investigation, normalized settlement amount per officer rank and average duration of cases per officer rank. 
### Visualizations  
**Tools used:** Tableau, D3.js <br> 
We used Tableau and D3.js to analyze decrease in allegation count and whether or not this trend changes based on race. We also created a heatmap which shows incidents by area and how the number of incidents change in different areas over the years. 
### Graph Analytics 
**Tools used:** Spark, NetworkX, Graph Frames <br>
We created a co-accusal network of officers where the nodes are officers and edges are cases. Then, we used page ranking algorithm to identify nodes of importance. 
### Machine Learning and NLP 
**Tools used:** Sklearn, NLTK, Pandas, Numpy <br>
In this section we validated our hypothesis that the trend has changed after release of CPDB by training ML models on data before release of CPDB and testing it on data after release of CPDB. We also created a N-gram model to find related important keywords in different allegation categories and then also assigned a severity score to each document.  

## Dataset used 
The Citizen's police dataset can be found [here](http://invisible.institute/police-data). 

## Usage 
Each checkpoint folder contains a README document which explains about the analysis performed and instructions to reproduce the analysis. A summary of all the checkpoints can be found in the report attached with this repository. 
