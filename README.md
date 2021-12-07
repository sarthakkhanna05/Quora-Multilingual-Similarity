# Natural-Language-Processing
Devised a program for an ongoing kaggle competition to find relationships between two sentences- similar, contradictory or neutral. Constructed by applying a fine-tuned multilingual XLM-RoBERTa model and various Tensorflow modules. The challenge is that the sentences are in 15 different languages. 92% accuracy achieved.

# Steps to implement the code

* Import the 'xlm_roberta' notebook in kaggle notebooks.
* load the data using an ongoing competition contradictory my dear watson. 
* Run the Notebook 
* Make pre-processing and model optimization changes according to your intuition.
* make oredictions on the test data 

# Data Visualization

![image](https://user-images.githubusercontent.com/78380617/144985727-4410ed88-910e-4634-b836-2b0ac58f1566.png)

The data consists of sentences in 15 different languages. We need to classify the hypothesis and premise for each one of them. 

# Encoding

We Encode every word/token in each sentence using pre-trained tokens from transformer's AutoTokenizer. 

![image](https://user-images.githubusercontent.com/78380617/144986072-28048964-9656-46f3-92b7-3e87ccce242f.png)

# Confusion Matrix

![image](https://user-images.githubusercontent.com/78380617/144986431-9eaab63e-76eb-4908-a4c5-4e3b4809e1f7.png)


