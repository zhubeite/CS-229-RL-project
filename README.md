# CS 229 project

## Introduction

This is a joint-work by Caitlin Stanton (stanton1 'at' stanford.edu) and Beite Zhu (jupiterz 'at' stanford.edu) for the CS229 2018 Fall final project. In the current status, we are exploring options in reinforcement learning, in particular the agents for Lunar Lander from OpenAi Gym. Details for the setup are presented later in the README

## Motivation

Our initial goal is to understand common techniques used in reinforcement learning.  In particular, we first sought to understand the methods and code used in [a link](https://medium.com/@gabogarza/deep-reinforcement-learning-policy-gradients-8f6df70404e6?fbclid=IwAR1mO7reVWv9ldNfBCWyTqHGZjvtMIGtGjfi1oV8sRrSpfSi5lCZHePZ1Ts}{medium.com/@gabogarza/deep-reinforcement-learning-policy-gradients), which enacts a policy gradient method to train an agent to play the LunarLander arcade game.  We then hope to practice applying other techniques tobetter learn Lunar Lander (such as deep Q learning).  Finally, we hope to ap-ply these techniques that work to learn arcade games to other, less conventialapplications, such as predicting the stock market.

## Current Model

We have a base line policy gradient model that has the following structure:

![Alt text](image/layers.PNG?raw=true "layers")

Here's its result from episode 200, 500 and 1000.

![Alt text](image/episode 200.gif?raw=true "layers") 
![Alt text](image/episode 500.gif?raw=true "layers") 
![Alt text](image/episode 1000.gif?raw=true "layers")

