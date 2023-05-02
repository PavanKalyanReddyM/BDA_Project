<h1> Deliverable 1</h1>
<h4>1) Team </h4>
 	<h4>a)  Members</h4>
		<li>Veda Samhitha Dyawanapally</li>
        	<li>Meghana Chikyala</li>
   		<li>Poornima Pulakandam</li>
        	<li>Amarnath Reddy Chinthapalli</li>
		<li>Pavan Kalyan Reddy Madatala</li>
  	<h4>b)  Communication plan to include project artifact repository</h4>
A communication plan was created to outline how project artifacts were stored and shared among team members. In this case, We have used Google Spaces as the primary platform for discussions, while Google Meet was used for virtual meetings. Additionally, a Git repository will be utilized to share project files and other relevant information. The frequency of group meetings will be based on the project deliverables.

<h4>GitHub Repository Link</h4> https://github.com/PavanKalyanReddyM/BDA_Project.git
			
<h4>2)  Selection of data:</h4>
	We have chosen this dataset from kaggle.
<h4>DataSet Link:</h4> 
<h4>Kickstarter Projects:</h4>
https://www.kaggle.com/datasets/ulrikthygepedersen/kickstarter-projects
<h4>DataSet Description:</h4> 
The data set contains details about Kickstarter projects and whether they were able to achieve their funding goals or not.
<h4>3) Business Problem or Opportunity</h4>
<h4>Kickstarter Projects:</h4>
The dataset we have chosen is from Kaggle where it gives the data related to the Startup Project. We can use this data to derive some descriptive visualizations like how many projects were successful, which country has invested more in these projects and whether the Number of Projects being successful are increasing year by year etc.
Also, we use Machine Learning techniques and statistical analysis to give accuracy of the state of the project whether it is going to be successful or not and for developing accurate predictive models.
<h4> Domain Knowledge</h4>
AWS S3, AWS Sage Maker for Analytics and ML Process.
AWS Quick Sight for Creation of Dashboard Visualizations.


<h4>4) Research Objectives and Question(s)</h4>
<h4>Kickstarter Projects:</h4>
<li>Which category of projects has the highest success rate?</li>
<li>What is the overall trend of crowdfunding projects over time, and how does this vary across different categories?</li>
<li>How many projects were successful and how many failed? What is the overall success rate of Kickstarter projects?</li>
<li>What is the Correlation between the Goal, Pledged and Backers attributes?</li>
<li>Are there any outliers in the dataset, in terms of extremely high or low amounts pledged, number of backers, or project goals?</li>
<li>How many projects were launched for each category with respective year?</li>
<li>What is the average funding goal and pledged amount for different categories and subcategories on Kickstarter?</li>
<li>Are there certain countries that tend to have more successful campaigns?</li>
<li>Can we predict the success rate of a project (i.e., the percentage of its funding goal that is met) based on its category, subcategory, country, launch date, and the number of backers?</li>
<li>Is there a relationship between the success rate of a project and the length of its crowdfunding campaign (i.e., the difference between its launch date and its deadline)?</li>


<h1> Deliverable 2</h1>
<h4> Data Understanding </h4>
<h4>a) Exploratory Data Analysis </h4>
Exploratory data analysis was performed using AWS SageMaker. 
The hyperlink to the corresponding file is provided below.

https://github.com/PavanKalyanReddyM/BDA_Project/blob/main/Delivarable2_BDA.ipynb

<h4> b) Dashboard </h4>
<p>Dashboard instances displaying visualizations like pie charts, bar charts, word clouds, line graphs, outliers, and correlation graphs were made using AWS QuickSight. Research objectives are evaluated using these visualizations. Additionally, other plots were also produced using an AWS Amazon SageMaker notebook.</p>

The PDF document contains several graphs generated using AWS QuickSight. 
Please find the link to access the PDF document below.

https://github.com/PavanKalyanReddyM/BDA_Project/blob/main/Dashboard_KickstarterProjects.pdf

<h4> Data Preparation </h4>
<p>The dataset was checked for any missing values and those were removed to ensure accurate analysis. To enhance the analysis, a new attribute called 'Duration_in_days' was created using the 'Launched' and 'Deadline' attributes. Additionally, null values were checked and examined for each column, as they can hinder the machine learning algorithm's ability to learn. Afterwards, each column's data was observed thoroughly, and statistical measures such as standard deviation, mean, maximum, and other distributions were analyzed to determine the evenness of the data distribution.</p>






