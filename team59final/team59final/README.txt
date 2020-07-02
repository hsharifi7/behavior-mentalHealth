DESCRIPTION:========================================================================
The folder CODE contains all the data analysis we done for the project.
It contains two folders:
	1- ProjectBRFSS ---> contains the code for visualization
	2- DataAnalysis	---> contains the code for data analysis, ML, and DL

INSTALLATION: ======================================================================

In order to run the code for =**visualization**=:
	1- run a webserver pointing to the directory ProjectBRFSS
	2- Alternatively, you can open the directory in visual code and run the live server on "index.html"
	The visualization is online : https://github.gatech.edu/pages/kmarikrishnan3/ProjectBRFSS/ed.html

In order to run the =**data analysis code**=, there are two pre-requisits.
	1- installing Anaconda, Jupyter, scikit-lear, and Keras
	2- downloading SQLite database 

***Installing Anaconda, scikit-lear, and Keras***
Installing Anaconda would install Jupyter notebook too.
To install Anaconda Distribution for Python 3.6 download the installation package from: 
https://www.anaconda.com/distribution/

After you install anaconda, you run the command 
	$> anaconda-navigator

This command will run a GUI that shows list of applications it contains. One of the Jupyter.
From this GUI you can run Jupyter.

By installing Anaconda, you can use conda package manager to install scikit-learn and Keras.
	$> conda install scikit-learn
	$> conda install -c conda-forge keras

***downloading SQLite database***
The database is onlin in a google drive space. 
https://drive.google.com/open?id=1_Qo9t5JRVX-0sCE7F0HoW5Gdf2Dp3vZO
Please unzip the file and place it under the folder "CODE".

EXECUTION :=====================================================================
For the interactive visualization:
	1- run a webserver pointing to the directory ProjectBRFSS
	2- Alternatively, you can open the directory in visual code and run the live server on "index.html"
	The visualization is online : https://github.gatech.edu/pages/kmarikrishnan3/ProjectBRFSS/ed.html

From this part you can easily run the code from any of the Jupyter notebooks.
List of Jupyter notebooks for analysis of six factors on mental health:

	1- alcohol-smoke.ipynb --> alcohol and smoking ~ mental health
	2- physical-activity.ipynb --> physical activity ~ mental health
	3- veggies-fruits.ipynb --> veggies and fruits ~ mental health
	4- education.ipynb --> education ~ mental health
	5- internet.ipynb --> internet ~ mental health
	6- consolidate --> consolidate all data into one CSV
	7- advanced-model --> consolidate all data into CSV with no Fruit, veg, internt factors

List of Jupyter notebooks for Machine and Deep Learning analysis.
In order for the ML/DL analysis to work, you need to run the Jupyter codes above to 
generate the data for analysis.

	1- RandomForest-Analysis (Accuracy 68%)
	2- NaiveBayes-Analysis (Accuracy 68%)
	3- LinearDiscriminant-Analysis (Accuracy 69%)
	4- KNN-Analysis (Accuracy 63%)
	5- eightClassifier-Analysis (Accuracy 35% to 68%)
	6- DeepLearning-Analysis (Accuracy 68%)

List of Jupyter notebooks for adanced analysis to increased the accuracy
	1- advanced-model (Accuracy 72%)
	2- education-advanced --> this is the initial advanced analytics that led to increase in accuracy.






