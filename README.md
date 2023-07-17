# TextClassification
Comparing Deep learning model with Pytorch – transformation, logistic regression with CV hyper-parameter optimization, and Graph based methods on Emotions DataSet
# Text Classification Using Machine Learning Methods

 

## About Corpus 

For this project, algorithms are applied to Emotion Dataset. The corpus is gathered from English tweets. Tweets are mostly in Spoken Language. So, there will be some phrases like 10/10, OOOMG, and WHAT A WONDERFUL DAY that do not have a meaning in a dictionary or mean something different from the definition in the dictionary. For example, in the first case, 10/10 means perfect but semantically it is a mathematical operation. Therefore, the model needs features more than semantic meaning to predict an emotion for unseen tweets. The paper is using a graph-based algorithm and extracts the word embeddings for model training. Also, there are lots of results published by different papers with high accuracies and they all used deep learning. Hence, we decided to use a non-graph-based algorithm beside a deep algorithm and test the papers' hypothesis. 

## Results 

In this project logistic regression with CV hyper-parameter optimization as the simple machine learning model  is implemented. Also, a deep learning model with Pytorch – transformation was added for comparison purposes. 

### First Method

![Screenshot from 2023-06-18 15-03-50](https://github.com/maryamteimouri/TextClassification/assets/57563772/1d605b3b-4473-4e86-b5a5-83069cecb1bd)

The accuracy of this method is 68%. 

### Second Method 
![Screenshot from 2023-06-18 15-02-06](https://github.com/maryamteimouri/TextClassification/assets/57563772/8ce74cfd-7849-4805-b99e-7ea96506a22d)

The accuracy of this method is 92%. 

## How results are related to the state of art 

The first method is using the semantic features only. The accuracy is low, and the model is not very efficient. The paper uses a graph-based embedding, and the best accuracy is 81%. The deep learning model's feature extraction method is not clear, but the accuracy is the highest, 92%. This proves that the model needs more features than the simple semantic ones but extracting graphs might not be enough too. The deep learning model extracted the best features based on the results. 

References 

https://paperswithcode.com/sota/text-classification-on-emotion 

https://huggingface.co/docs/transformers/tasks/sequence_classification 

