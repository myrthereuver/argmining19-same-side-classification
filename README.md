###### Prerequisite: Please download [Git lfs](https://git-lfs.github.com/) 
 
# [Same Side Classification](https://sameside.webis.de) 

Identifying (classifying) the stance of an argument towards a particular topic is a fundamental task in computational argumentation. The stance of an argument as considered here is a two-valued function: it can either be ''pro'' a topic (= yes, I agree), or ''con'' a topic (= no, I do not agree).

With the new task » same side (stance) classification« we address a simpler variant of this problem: Given two arguments regarding a certain topic, the task is to decide whether or not the two arguments have the same stance. 
  
## Task: Same Side Classification

Given two arguments on the same topic, decide whether they have the same or opposite stance towards the topic. 


## Settings
We have two experimental settings:
 - Within: Train on a set of topics and evaluate on the same set of topics.
 - Cross: Train on one topic and evaluate on another topic.
We choose the 2 topics with highest number of arguments: *abortion* and *gay marriage*.


## Data
### Data source:
idebate.org, debatepedia.org, debatewise.org, debate.org

The data folder contains the training and testing data, for *cross* and *within* topics. You can split the *training* data as you like in order to train your model. After that, the model will be evaluated using the test data.


For more details, visit https://sameside.webis.de

