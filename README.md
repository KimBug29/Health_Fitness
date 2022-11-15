# Health_Fitness

## Created by Kim Wolf

![Health & Fitness](/images/health-fitness-image.jpg)

#### According according to the World Health Organization (WHO), health is "the level of functional or metabolic efficiency of a living organism". While fitness is referred to "a state of health and well-being of the body".

#### Health and Fitness Relationship is a data analysis project with a focus on comparing and contrasting fitness activity to select health indicators. Activity measurement originated from fitness trackers, a sports logging app and manual data entry from participants.


## General Info - Project Description
***
 * The data analysis project was written in VS Code with Jupyter Notebook and Seaborn for data visualization.  
 * Use of pandas, seaborn, and matplotlib to perform various analysis of two (or more) data sets. Data visualization uses Seaborn charts.
 * While constructing this project I faced a steep learning curve with the various technologies, specifically use of kernals when running the code in conda.


 ## Project Features

 Health and Fitness Relationship project includes the following features.

 * Feature 1 - Load data. Read two JSON data files
 * Feature 2 - Clean data while combining. Clean data and perform a pandas merge with two data sets, then calculate some new values based on the new data set
 * Feature 3 - Visualize data using Seaborn plots/charts.
 * Feature 4 - Best practices. Utilize a virtual environment, instructions included in this README
 * Feature 5 - Interpretation of data. Use of markdown cells in Jupyter Notebook, including clear code comments, and well written README.md 


## Technologies Used   
***
A list of technologies used within the project:
* [VS Code](https://code.visualstudio.com/download): Version 1.73
* [Juypter Notebook in Anaconda3](https://www.anaconda.com/): Python 3.9.7   
* Need to enter more info here.....

## Installation  
***
To install, run and view the project, perform the following steps:
```
Clone my repo from GitHub.

git clone https://github.com/KimBug29/Health_Fitness.git

Next, down the data set from Kaggle at https://www.kaggle.com/datasets/vlbthambawita/pmdata-a-sports-logging-dataset and save the file folder titled 'osfstorage-archive'

Conda was used to create this project, and I created a conda virtual environment. 

Ensure you have installed Anaconda. (link to install https://docs.anaconda.com/anaconda/install/) If you use windows, in ‘Start’ you need to type and start the ‘Anaconda prompt’. If you are on Mac or Linux, you can do all of these in Terminal.

To create a conda virtual environment:
1. Create an environment 
    conda create --name NEWENV (replace NEWENV with the name of your choice)

2. You will be asked if you'd like to proceed y/n. Select  y to proceed.

3. Use conda activate NEWENV to activate your new virtual environment. (Again, please replace NEWENV with your chosen name). My virtual environment name is hfenv

4. To run the project insure you have installed the packages listed in the environment.yml file. These packages are under dependencies. Use conda install.

For example: conda install python
Repeat until all packages are installed.

5. Open the Jupyter Notebook: fitness.ipynb

    Make sure that the virtual environment you created is selected.

6. Run the notebook.

## Credits

Data file folder titled 'osfstorage-archive' was obtained through Kaggle at https://www.kaggle.com/datasets/vlbthambawita/pmdata-a-sports-logging-dataset 