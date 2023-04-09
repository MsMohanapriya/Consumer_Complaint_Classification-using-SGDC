# Consumer_Complaint_Classification-using-SGDC

Consumer Complaint Classification means classifying the nature of the complaint reported by the consumer.
It is helpful for consumer care departments as they receive thousands of complaints daily, so classifying them helps identify complaints that need to be solved first to reduce the loss of the consumer.


The problem of consumer complaint classification is based on Natural Language Processing and Multiclass Classification.
To solve this problem, we needed a dataset containing complaints reported by consumers.

I found an ideal dataset for this task that contains data about:

The nature of the complaint reported by the consumer
The Issue mentioned by the consumer
The complete description of the complaint of the consumer

To classify the complaints:
Here we are importing python libraries for various activities
1.pandas for data manipulation
2.numpy for handling numeric data as arrays
3. sklearn for clustering, classification, stastical modeling 
4.nltk(Natural Language Toolkit) for text analysis

The product column in the dataset contains the labels. Here the labels represent the nature of the complaints reported by the consumers. Let’s have a look at all the labels and their frequency

Preprocess the data and perform transistions before training the model

spliting the data into two sets training and test set

Now train the Machine Learning model using the Stochastic Gradient Descent classification algorithm.
