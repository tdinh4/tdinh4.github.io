---
layout: page
permalink: /projects/
---

iPython Tensorflow Notebook Tutorials
====================
![](/assets/tf.jpg) 

<a href="https://github.com/adeshpande3/TensorflowStuff/blob/master/ConvolutionalNeuralNet.ipynb" target="_blank">Convolutional Neural Network Tutorial</a> - This notebook shows you how to define a simple convolutional network using Tensorflow. We'll discuss how to load in datasets, how to create our network architecture using Tensorflow variables, as well as how to define loss functions and optimizers. 
<br><br><a href="https://github.com/adeshpande3/Generative-Adversarial-Networks" target="_blank">Generative Adversarial Network Tutorial</a> - This notebook shows you how to create a simple GAN. The basic idea is that you have 2 different networks, a generator network and a discriminator network. The discriminative model has the task of determining whether a given image looks natural (an image from the dataset) or looks like it has been artificially created. The task of the generator is to create natural looking images that are similar to the original data distribution. In this tutorial, we'll look at how to create both models, and the unique process of training them to reach a Nash equilibrium. 

Sports Data Analysis
====================
![](/assets/sports.jpg) 

<a href="https://github.com/adeshpande3/March-Madness-2017/blob/master/March%20Madness%202017.ipynb" target="_blank">March Madness 2017 Bracket Predictor Model</a> - *** STILL IN PROGRESS *** This iPython notebook looks at how we can use historical data on NCAA regular season games to develop a model that outputs win probability for 2 given teams facing each other. We can frame this as a supervised learning problem where we can use past game by game results as our labels. Each team is represented by a d-dimensional vector containing information for that team (PPG, Number of Wins, etc) during the given season. The element wise difference between the two teams is inputted into a neural network, where the output is the softmax-bounded probability of the likelihood that Team 1 will come out victorious in the matchup. 
<br><br><a href="https://github.com/adeshpande3/MLB_Win_Predictor/blob/master/BaseballWinPredictor.lua" target="_blank">MLB Win Predictor Linear Regression Model</a> - This project looks at how a team's baseball statistics (ERA, Batting Average, RBI, etc), over the course of a season, contribute to their total number of wins. This uses the Torch7 computing framework to develop a linear regression model that takes in a set of 16 features representing traditional baseball statistics and outputs the predicted number of wins for the given season. Given the season statistics for a team, this model can predict a team's win total within 3 games (1.85% error). 

React Web Apps
====================

WORK IN PROGRESS 

