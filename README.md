# ML-ClassifiersComparision-BankMarketing
This ML project compares 4 Classifiers: KNN, SVM, Logistic Regression, and Decision Trees against Bank Marketing dataset


## Dataset
The dataset is from the <a href="https://archive.ics.uci.edu/ml/datasets/bank+marketing">UCI Machine Learning repository</a>. The data is from a Portuguese banking institution and is a collection of the results of multiple marketing campaigns. 

## Project Structure
<ul>
    <li><code>data/Data Source.url</code>: contains the url to the datasource. As I have reached the maximum space limit on github, I can't upload the actual data file here.</li>
    <li><code>data/bank-names.txt</code>: Contains the details about the dataset.</li>
    <li><code>images/</code>: contains the graphs used for reporting purposes in the notebook</li>
    <li><code>ML - Comparing Classifiers - Bank Marketing Data.ipynb</code>: this notebook covers all the CRISM-DM steps used in this project: Business Understanding, Data Understanding, Data Preparation, Modeling, Evaluation, and Deployment</li>
    <li><code>README.md</code>: provides an overview of the project</li>
</ul>

## Requirements
The following packages are required to run this project:

<ul>
    <li>numpy</li>
    <li>pandas</li>
    <li>scikit-learn</li>
    <li>matplotlib</li>
    <li>jupyter</li>
    <li>Python 3.9 or above</li>
</ul>

## Results
The below bar graphs compare the performance of the different classifiers with regard to fit times and precision scores respectively: 
<br />
 ![Fit Times comparision](/Images/FitTimes.png "Fit Times comparision.")
 <br />
 ![Precision score comparision](/Images/Precision.png "Precision score comparision.")
 <br />

As the selection criteria for the model will not only depend on the training time and precision score, but also on feature coefficients which can be turned iinto actionble customer-targeting guidelines to the campaining team, I choose the the <b><u>SVM model with the Linear Kernel</u></b> for the task.<br /><br />
Based on the chosen model's feature coefficients, my recommendation to the campaining team would be to: 
<ul>
<li>Focus on customer who accepted the campaing in previous campaigns, and</li>
<li>Avoid customers who either turned down the previous campaign or didnt record any results </li>
</ul>

## Contributors
Ashwin Kambli (@ashwin-kambli)

## License
This project is licensed under the MIT License - see the <a href="LICENSE" target="_new">LICENSE</a> file for details.