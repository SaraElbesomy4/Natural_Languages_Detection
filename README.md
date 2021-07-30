# Natural_Languages_Detection
This is the main project of the NLP Course in Zewail City (CIE 553)

This project objective is Building a machine learning model to successfully identify the most popular languages. Many models have been tried and the results have been compared to find the best model.

### Dataset:
I used a subset from WiLi-2018 Wikipedia dataset. The original dataset contains 235000 paragraphs of 235 languages. Each language in this dataset contains 1000 paragraphs.
Not all of the 235 languages are commonly used so, the subset I used just contains 22 languages so, it include 22000 paragraphs. 1000 paragraphs for every language. A sample from the datset is shown in the following figure. You can find the dataset [here](https://www.kaggle.com/zarajamshaid/language-identification-datasst)

<p align="center">
  <img src="https://github.com/SaraElbesomy4/Natural_Languages_Detection/blob/main/Images/Sample%20from%20the%20dataset.PNG" width="500" height="179" alt="Sample from the dataset" />
</p>

### Models:
In this project I tried 3 different ML models: Logistic regression, Support vector machine and Multi-layer perceptron neural network.I tried all of them with 2 different features extractores: Bag of words and TF-IDF. Therefore, I have 6 models to compare and find the best one.

### Results:
As shown in the following table, I got high acccuracies over all the models.

<p align="center">
  <img src="https://github.com/SaraElbesomy4/Natural_Languages_Detection/blob/main/Images/Results.PNG"  width="500" height="112" alt="Results" />
</p>
