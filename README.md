# Final Project Applied Machine Learning 2021 Ben Gurion University

Students:
Guy Zamostiano, Maayan Shtengel

This project's topic is evaluation of perforamce of the method introduced in the paper:

“Regularization Learning Networks: Deep Learning for Tabular Datasets” 
by: 	
Ira Shavitt  Weizmann Institute of Science
Eran Segal Weizman Institute of Science

arXiv:1805.06440v3 [stat.ML] 23 Oct 2018
https://arxiv.org/abs/1805.06440

based on the papar's code: https://github.com/irashavitt/regularization_learning_networks


How to run the code:
The code is a Jupter Notebook that can be run.

The hyperparameters of the RLN network are:
	  
   Theta -
	 the normalization factor of the regularization coefficients. 
	 By the paper and its implementation we saw that a good range for theta is [-12,-8]
   
   (Log) Learning rate - 
   the learning rate of the regularization coefficients.
   From the paper and its implementation(Keras_implementation.py) the best learning rates
   are quite large and between 10^4-10^6. 

The hyperparameter of the L1 regularization network is:
    l1 -the regularization factor that is also called ‘l1’


PLEASE PAY ATTENTION:
In the running there will be a request to give a code for accessing the google drive (by a link) where the results will be uploaded.
This is done in the first block of code in the notebook:
"auth.authenticate_user()"
(Everyone should have access to the drive)
If you will not enter the code, the running will not continue. 


Link:
https://colab.research.google.com/drive/1OibJbQMKMFTVbGCyKV8AI0nKrypZ3rqU?usp=sharing
