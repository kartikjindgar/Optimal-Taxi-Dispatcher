# Optimal-Taxi-Dispatcher
*Using Reinforcement Learning to optimize Taxi Dispatch system in New York City.*

Meeting demand efficiently lies at the crux of most ride-sharing businesses. 
It is essential to dispatch cabs with the not only the goal to satisfy customer demand, but also minimize travel costs and customer waiting times. 
This kind of problem is difficult to solve using general supervised learning methods because we need to be able to capture changing cab distributions with each action taken, in order to learn the best overall dispatch strategy.  

> Goal:  Train an RL agent to optimally dispatch cabs in Manhattan, based on live demand. 

This project was undertaken as part of Reinforcement Learning course at Center for Data Science, New York University.  

Repository Structure :
- Data Folder: contains the unprocessed yellow taxi trip data(.parquet) and different processed matrices(move_cost, wait_cost, taxi_zone_lookup) used while training the RL agent
- Outputs Folder: contains the output graphs showing trends of accumulated rewards and % insatiated demand
- PolicyGradient.ipynb Notebook contains the training and evaluation code for the RL agent
- data_prep.ipynb Notebook contains code to generate different matrices from the nyc yellow taxi data required for training the RL agent 
