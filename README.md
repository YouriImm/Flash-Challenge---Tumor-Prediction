## About

Included in this repository is a *flash challenge* that I carried out in June 2018. This was a quick and short challenge to implement machine learning algorithms on a (mostly) clean dataset. Using a clean dataset was intentional, as this challenge was intended to be brief, with full focus on machine learning. The main goal was to implement a machine learning pipeline in libraries other than sklearn and evaluate their results. 
Keras was used to train a neural network, and PySpark was used to create a machine learning pipeline with a Random Forest Classifier. While there are differences, both performed well.

- [Keras](https://keras.io "Keras") was used to build a small neural network on the data. The neural network ended up performing extremely well, even on unseen data. Full code, evaluation metrics and visualizations can be found here. 
- [PySpark](http://spark.apache.org/docs/2.1.0/api/python/pyspark.html "Pyspark") was used to train a Random Forest Classifier using cross validation. I am well aware of the fact that Spark is not necessary for this dataset. However, implementing a machine learning pipeline in Spark does mean that the pipeline would still work if this dataset were much, much bigger. Added to that, note that this flash challenge exists purely for practice purposes. The Spark implementation performed very well, though not quite as well as the neural network did. That said, evaluation metrics still looked excellent. The PySpark code can be found here. 

The data used for this challenge is a well known dataset containing tumor observations. The goal is to predict malignant tumors. You can find the dataset in the data folder of this repository. 

This small challenge was carried out purely for the sake of practice, and had no other purpose. 
___

This project was carried out during [Anchormen's *High Potential Program*](https://anchormen.nl/services/high-potential-program/ "Anchormen's HPP website"), a data science education program taught at [ITvitae Learning](https://itvitae.nl/ict-opleidingsprogrammas#opleiding-4 "Dutch link").