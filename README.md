# Facial Expression Recogonition with TensorFlow Convolutional Neural Networks

**TensorFlow** is an open-source library developed by Google <https://www.tensorflow.org/>

This project is for one of my acdemic courses. The detailed Python scripts and sample results are showed in **`CNN_Facial_Expression_Recogonition.ipynb`**. This project used TensorFlow library to train Convolutional Neural Networks (use Softmax regression as classifier). The data is from one of Kaggle challenges [here](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data). There are seven facial expression in this dataset, and specific information is showed in Jupyter Notebook.


**The CNN model structure is showed below:**

![CNN model](https://github.com/Hanzhuo/Facial-Expression-Recognition-with-TensorFlow-Convolutional-Neural-Networks/blob/master/ImageDocument/cnn_flow.png)

**Results:**
The optimal number of iteration steps of training this CNN model is around 3000. Training 3000 iteration steps' model needs around 6 hours (8GB Intel i5-4210U 1.70GHz * 4 CPU only). Using this notebook scripts can get different accuracy each time. The result in the notebook just show one of these different resutls. The accuracy of the best model that I trained can reach around 68%. 

![The highest accuracy](https://github.com/Hanzhuo/Facial-Expression-Recognition-with-TensorFlow-Convolutional-Neural-Networks/blob/master/ImageDocument/accuracy_68%25.png)
