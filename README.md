# machine_learning

We have used Google's AutoML Vision to create a machine learning model that determines whether a given image can be classified as Cardboard, Glass, Metal, Paper or Plastic. The model was trained using an open source database created and classified by Gary Thung and Mindy Yang. 

The model reached a precision of 90.76%. Upon inspection of the confusion matrix we confirmed our suspicions that glass would often be confused for plastic and vice versa. This prompted us to refine our UI in order to add another layer of reliability to our app. 

We used Google's Cloud Vision API to get the labels associated with any image in order to determine object type

