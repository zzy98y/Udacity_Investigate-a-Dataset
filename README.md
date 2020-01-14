# Udacity_Investigate-a-Dataset
## Udacity Data Analyst Nano Degree Project #2 Investigate a Dataset 
### This project presented a thorogh process of Data Analysis. Content and Analysis wise may not be perfect, but process wise is complete and thorogh. 
## **Warning: This is a passed project, copy this project may result in plagerism and program cancellation from Udacity.**
# Setup 
If you **don't** have Pandas, Numpy, Matplotlib and Jupyter Notebook installed: 
In either Command Prompt(Windows)/Terminal(Mac): \
`pip install pandas` \
`pip install numpy` \
`pip install matplotlib`\
`pip install jupyterbook` 

# tmdb-movies.csv 
In my code, I directly used the file name when I read the csv file. To be able to do that, you need to first upload the actual file into your jupyter notebook. 


# Issue
In the dataset, there is this column called genre. There are movies with multiple genre seperated by '|'. I wasn't to be able to seperate them individually because every movie has different number of mix genre. So I just automatically assume the first genre is the primary genre of the movie. 

