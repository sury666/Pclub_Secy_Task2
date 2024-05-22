# Pclub_Secy_Task2
Task 2 - Machine Learning of PClub Secretary Recruitment Test

## Approach I took to find the dataset
I searched on kaggle, github and other sources to find the data on **Tidal Volume** but couln't find one exactly as required. After hours of searching I came across one on github which was somewhat related to Tidal Volume, Lung Capacity. So, I used this dataset as lung capacity and tidal volume are similar terms.
The github repo I found - [Github](https://github.com/dferriola/LungCap-Linear/blob/master/README.md)
The dataset given here - [Dataset](https://drive.google.com/file/d/0BxQfpNgXuWoITmVwQzJ2VF9qVlU/view?usp=sharing&resourcekey=0-laj6fcrhqu9xwgjl7WJTmA)

## My appproach
So, firstly, I searched google on how to predict some things based on same other factors using ML. I learned about supervised ML and regression models. After plotting the data, it turned out to be linearly related, so I used linear regression to build my ML model. I analysed my data and found that it was already clean(didn't contain any null values).
In the starting I didn't know that linear regression can be used only on numeric values, so I got unexpected errors. After thorough reading on the internet, I got to know about feature encoding, so I used it.
To improve accuracy, I removed outliers and (scaled the data in the starting which decreased the aaccuracy so scraped it). 

## Steps to run my code and to test my model against a test dataset
My github repo contains this README file, the dataset I used and the only jupyter notebook containing all the code.
To run my code, you simply have to run all codeblocks inside the jupyter notebook named 'Code_Playground.ipynb'.
To test my model against a test dataset, simply enter the dataset inside the last codeblock as I've also written inside in the notebook.

## Screenshots of my model in action
![image](https://github.com/sury666/Pclub_Secy_Task2/assets/154620691/fbdbe94f-969f-41a3-a743-2a1061aeb54f)
![image](https://github.com/sury666/Pclub_Secy_Task2/assets/154620691/fab20941-6a8c-4f72-b3fc-de3e5c785ffd)
![image](https://github.com/sury666/Pclub_Secy_Task2/assets/154620691/c3948f97-3329-4a41-8eb8-b476acbb24e9)
![image](https://github.com/sury666/Pclub_Secy_Task2/assets/154620691/3e087a48-c99c-4ae8-9e7e-52a8727b92a0)
![image](https://github.com/sury666/Pclub_Secy_Task2/assets/154620691/817d3662-d454-4244-b2de-2c629cf7d6d7)
