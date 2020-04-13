---
layout: post
title: 'Deep Learning by Andrew Ng, Part 1'
published: true
---
This will be my first attempt at the Deep Learning specialization taught by Andrew Ng.
The specialization is divided to 5 courses - 
1. Neural Networks and Deep Learning - Building and training a new neural network, while the object is learning how to recognise cats(why though?)
2. Practical aspects of deep learning - improving Deep Neural Networks using Hyperparameter tuning, Regulariztion and Optimization
3. Structuring machine learning projects - best practices for dividing our data, even when datasets come from different disributions, and when to use end to end Deep Learning.
4. Convilutional Neural Networks (CNN) - implied to images
5. Natural Language processing -  building sequence models such as Recurrent Neural Neturks (RNN), LSTM. 
Used for things that come in sequences such as natural languages(speech recognision), music generation.

What is a Neural Network?
Deep learning is esentially training a large number Neural Networks. But what is a neural network?
The simplest form of a Neural network includes just 2 variables, is this example the size of the house and its price. We are trying to predict the price of the house as a function the size of the house

price y    Linear function with a max of 0, because a price of a house cant go below 0.
            it is called RELU function and very popular in machine learning.
            x/   
            /x                   This neural network looks like this
         x /                     size  ---> () ---> price 
    _____ /                         x      nueron/     y
         size of house x                  node 
         
         
The neuron's job is to input the size, compute the linear function (while taking a max of 0), and return the price

When we add more variables to the network, it might look like this - 

size
              () 
#bedrooms\
         v
         ()
          ^    
zip_code\/
         v
         ()
         ^   
wealth  /




         
         
         