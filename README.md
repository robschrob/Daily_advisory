# The Daily Advisor

Final project for the Building AI course

## Summary

The tool shall support every person in defining a healthy daily routine by giving individual advice for the day at hand.
The routine includes areas of: 1) nutrition and food, 2) sports and exercises, 3) other


## Background

Which problems does your idea solve? How common or frequent is this problem? What is your personal motivation? Why is this topic important or interesting?

# Finding and holding owes balance in life
# Feeling generally better and less exhausted, depressed, ...
# Understanding ones limits and what to look out for in life better


## How is it used?

Describe the process of using the solution. In what kind situations is the solution needed (environment, time, etc.)? Who are the users, what kinds of needs should be taken into account?

Based on general, individual personal needs and interests ("base day routine" and "personal ups, downs, handicaps") a model shall be defined (especially the weights). Including personal mood, health etc. in the morning, the tool then gives specific advice for the day to come.
E.g. when one wakes up, the person feeds how he slept, what he did last night, what and how much he plans to do in the day.
The solution then gives advice what to consider. E.g. drinking lots of water the whole day, doing a bit less sport than planned etc.

It is important to understand and consider specific differences between the days. E.g. is it a work day or holiday.
This defines which base routine and parameters (or models) shall be used to derive the advice.


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?

There will likely be multiple models which need to be trained, depending on the general type of users (e.g. a very elderly person).
These models will incorporate general knowledge (e.g. on nutrition) and data which needs to be sampled by (alpha) users of the solution.
As well the solution shall continuously learn by incorporating feedback by the users at its application.
Most likely will be a deep learning / RNN model with reinforcement learning be applied.


## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

It can only give advice, it does not relieve from ones personal responsibility.
E.g. when the solution would recommend to do more sports, it cannot take over responsibility when the user gets an injury.


## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 

Creating a demonstrator on some certain key elements of the solution would be a first step.
For this the project needs an experience data scientist to collect, structure and evaluate required data. And to evaluate potential models.


## Acknowledgments

n/a

Building AI course project
