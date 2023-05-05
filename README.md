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
<li>Can we predict the success rate of a project (i.e., the percentage of its funding goal that is met) based on its category, subcategory, country, launch date, and the number of backers?</li>
<li>How important are Categories in predicting the success of Kickstarter Projects?</li>
<li>How important are Sub Categories in predicting the success of Kickstarter Projects?</li>

<h1> Deliverable 2</h1>
<h4> Data Understanding </h4>
<h4>a) Exploratory Data Analysis </h4>
Exploratory data analysis was performed using AWS SageMaker. EDA helps to uncover insights and patterns within the data, validate assumptions, and determine the best approach to analyze the data.
The hyperlink to the corresponding file is provided below.

https://github.com/PavanKalyanReddyM/BDA_Project/blob/main/Delivarable2_BDA.ipynb

<h4> b) Dashboard </h4>
<p>Dashboard instances displaying visualizations like pie charts, bar charts, word clouds, line graphs, outliers, and correlation graphs were made using AWS QuickSight. Research objectives are evaluated using these visualizations. Additionally, other plots were also produced using an AWS Amazon SageMaker notebook.</p>

The PDF document contains several graphs generated using AWS QuickSight. 
Please find the link to access the PDF document below.

https://github.com/PavanKalyanReddyM/BDA_Project/blob/main/Dashboard_KickstarterProjects.pdf

<h4> Data Preparation </h4>
<p>The dataset was checked for any missing values and those were removed to ensure accurate analysis. To enhance the analysis, a new attribute called 'Duration_in_days' was created using the 'Launched' and 'Deadline' attributes. Additionally, null values were checked and examined for each column, as they can hinder the machine learning algorithm's ability to learn. Afterwards, each column's data was observed thoroughly, and statistical measures such as standard deviation, mean, maximum, and other distributions were analyzed to determine the evenness of the data distribution.</p>
<h1> Deliverable 3</h1>
<h4>Analytics, Machine Learning:</h4>
We have used Amazon SageMaker, Athena, and Glue, which are great tools for recognizing and understanding the structure of the data. Athena allows us to query the data in S3 using SQL, while Glue automatically crawls and catalogs the data and generates ETL code to transform it into a format that is suitable for analysis. By using these tools, we have gathered a better understanding of our data and ensured that we are using the best ML tools for our specific dataset.

Additionally, Amazon machine learning technologies like SageMaker, Athena, and Glue can help extract insights from the data and build accurate machine learning models that can drive better business decisions.
![WhatsApp Image 2023-05-04 at 10 15 20 PM](https://user-images.githubusercontent.com/123277087/236364973-05fc7130-d9f8-46d3-b4c1-efd3cf5a9d87.jpeg)
![WhatsApp Image 2023-05-04 at 10 16 50 PM](https://user-images.githubusercontent.com/123277087/236365102-9753b698-605b-43c5-982a-b0be02a4dca4.jpeg)
![WhatsApp Image 2023-05-04 at 10 17 10 PM](https://user-images.githubusercontent.com/123277087/236365128-3dfa10a6-dd84-4c45-8da6-363f6a380965.jpeg)
<h4>Evaluation and Optimization:</h4>
AWS offers a variety of machine learning models and analytic tools, and we have used logistic regression and random forest models. 
The likelihood that a dependent variable that is binary will take a specific value is predicted by a logistic regression model of the relationship between a binary dependent parameter and any number of independent variables. 
Regression as well as classification are handled by an ensemble learning method known as random forest.It functions by building multiple decision trees on various subsets of the data that are randomly chosen, followed by combining the predictions from each tree to create a final prediction.
<h4>Results</h4>
The accuracy of a machine learning model on the dataset can be a useful metric for evaluating the performance of the model. For our Kickstarter dataset, accuracy can tell you how well the model is able to predict the outcome of a crowdfunding campaign (i.e., whether it will be "successful," "failed," "canceled," or "suspended") based on the input features.

The notebook containing the code for building the models, evaluating their accuracy, and computing other relevant metrics can be accessed via the link provided below.
<h5>Link</h5>
https://github.com/PavanKalyanReddyM/BDA_Project/blob/main/Deliverable_3.ipynb
<h5>1. How important are categories in predicting the success of Kickstarter campaigns?</h5>
<b>Feature Importance:</b>
![WhatsApp Image 2023-05-04 at 10 19 01 PM](https://user-images.githubusercontent.com/123277087/236365499-fbd8d4b6-9ebb-43d9-bade-a429e03fda0f.jpeg)


	








