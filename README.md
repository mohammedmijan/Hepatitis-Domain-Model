 # Hepatitis Domain Machine Learning Model with Exploratory Data Analysis and Statistical Analysis
It can predict the patients going to be live or die with hepatitis disease symptoms. 

## The information for the dataset is given below:
  ### Find out
  1. Living conditions for hepatitis 
  2. The hampers for human body by hepatitis
  ### Insights
- The Protine column has 43.22% data missing. So, we convert it 0 value
- The data contains the patients who are mean 41 year old with standerd deviation 12.56. So, many patients are found around 30 to 50 years. 7 years old patient also have in dataset.
- The maximum number of age is in between 30 to 50 years old
- Male data was taken more than wemen
- Most of them are taken antivirals and having the symptoms
- All of the enzymes and hormones are in normal limitations on the living patients except the prothrombin timing
- The KDE is also pointing out the exact quantity of the enzymes and hormones on living patients
- It is also observered the maximum numbers of age along with sex comparison
- The dataset is catgorical and plotting discrete points. So, the data are running a non-linear plotting.
- The dataset is hardly appropable for analysis. So, the model will not build a proper model. Because, the numerical columns are not properly identified. The reason is that the data are discrete or continous. So, Classification or Regression cannot give a proper prediction. We needs to use clustering.(From statistical analysis)
### Model Details:
##### The information about the model:
1. Model Name :Perceptron(penalty='elasticnet')
2. Precision :0.85
3. Recall :0.9444444444444444
4. Score :0.8333333333333334
5. F1 Score :0.8947368421052632
### Limitations
##### - 1. The dataset is only for the patients of hepatitis, So, the model is working on patients
##### - 2. The dataset is not as much as big which can create an appropriate model
