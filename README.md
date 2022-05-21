# IronHack_final_project - Resumatchmaker

Hi there, welcome to my final project in IronHack Data Analysis Bootcamp. For this final project, I am going to build a model to help you identify the highly matched job with your resume in the database. The idea is that you input your resume to the model, and the model will retrun you the highest matches in the dataset. 

Please see the link for the project development details: https://trello.com/invite/b/OeTURFDE/898b5c5dea203c320ab8d9fa6aa787f0/resumatchmaker

In this project, I used a dataset that I found on Kaggle: U.S. Technology Jobs on Dice.com (https://www.kaggle.com/datasets/PromptCloudHQ/us-technology-jobs-on-dicecom) to build my model. The dataset has 22,000 instance, which is big enough to train and pivot my model. 

- In the Cleaning Data notebook, I have done 4 rounds cleaning because the nature of the dataset. Limitation: Although the dataset that I have chosen is big enough, I am not confident that the cleaning would work for every dataset. 

- In the EDA notebook, you will be able to see how the dataset looks like: how big is the dataset, which are the most used words, how many unique words, and the comparision of removing the stop words. 

- In the Further Cleaning & Model Building notebook, I did a final deep cleaning by stemming the text, and then I used different method to tokenize the text and compare their result. 

- In the Finding_job noteboook, you are able to run the model in once.
