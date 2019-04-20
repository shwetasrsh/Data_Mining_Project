# Data_Mining_Project


QUORA INSINCERE QUESTIONS CLASSIFICATION



Table of Contents

  1. Introduction
  
  2. Model Development



INTRODUCTION

An existential problem for any major website today is how to handle toxic and divisive content. Quora wants to tackle this problem head-on to keep their platform a place where users can feel safe sharing their knowledge with the world. On Quora, people can ask questions and connect with others who contribute unique insights and quality answers. A key challenge is to weed out insincere questions - those founded upon false premises, or that intend to make a statement rather than look for helpful answers.
The objective is to predict whether a question asked on Quora is sincere or not.

An insincere question is defined as a question intended to make a statement rather than look for helpful answers. Some characteristics that can signify that a question is insincere:

- has a non-neutral tone
- is disparaging or inflammatory
- isn't grounded in reality
- uses sexual content



MODEL DEVELOPMENT


![alt text](https://github.com/shwetasrsh/Data_Mining_Project/blob/master/model2model.PNG)



Basic Workflow is shown as follows - 


![alt text](https://github.com/shwetasrsh/Data_Mining_Project/blob/master/img.PNG) 



In this neural network model - 

1st layer: Embedding Layer(without pretrained)

2nd layer: Global Average Pooling Layer

3rd layer: Output Dense Layer(using Sigmoid Function)






