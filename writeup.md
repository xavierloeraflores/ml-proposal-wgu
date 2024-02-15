# C951 Task 3 Writeup
Xavier Loera Flores
ID:011037676
xloeraf@wgu.edu
C951 Introduction to Artificial Intelligence

# Machine Learning Project Proposal

## Project Overview
The following project proposal will demonstrate the need for a machine learning solution that implements image recognition to address an organizational need. The proposal will include a project overview, project design, machine learning solution design, and a description of the data sets that will be used to train the machine learning model.

### Organizational Need

A social media company needs a machine learning solution to automatically detect what type of content is in an image to flag the post as explicit or not explicit for moderation and content filtering purposes. The platform needs to be able to automatically detect the content of images as the user uploads the images to the platform. 

### Context and Background
The company has seen a significant increase in the number of images with explicit content being uploaded to their platform. While the platform allows users to manually mark their posts as NSFW or explicit, many users are not doing so, and the company receives numerous complaints from users who do not wish to see explicit content. This will allow the moderation team to focus on images with explicit content and remove them from the platform. It would also allow the company to blur or hide explicit images from users who do not wish to see them.

### Outside Works
#### Work 1

#### Work 2

#### Work 3


### Machine Learning Solution

### Benefits of Proposed Machine Learning Solution


## Machine Learning Project Design

### Scope

### Goals, Objectives Deliverables

### Standard Methodology

### Project Timeline

### Resources and Costs

### Success Criteria


## Machine Learning Solution Design

### Proposed Project Hypothesis

### Machine Learning Algorithms
#### Algorithm Advantage

#### Algorithm Limitation

### Tools and Environments

### Performance Measuring Process

## Description of Data Sets

### Data Sources
Data will be sourced from all the public images uploaded to the company's social media platform by users. The company terms of service allow for the use of images uploaded to the platform for improving features on the platform. These images can be found on the company's database and can be accessed through the company's API or either through a direct connection to the database.

### Data Collection Method
Once we have access to the collection of image data via either the company's API or direct connection to the database, we will collect the images to store them for use in training the machine learning model. For the most part, the data collected will already be categorized as explicit or not explicit since the company's moderation team had already flagged the images when the throughput of images was lower. The company only recently faced the issue of an increase in un-flagged explicit images so most of the images on the platform are already categorized.  

#### Method Advantage
By utilizing the database of images from the company's platform, we ensure that the data that will train the machine learning model is representative of the data that the model will be used on. The model will be trained to accept user generated content by being trained on user generated content. This will allow the model to tackle edge cases that can be found in user generated content since the model will be trained on years worth of data from the company's platform.

#### Method Limitation
The limitation with this method is that the model will be trained on data that has already been flagged by the company as explicit. User generated content can be unpredictable and new types of explicit content can be uploaded that the platform will not recognize such as AI generated images, deep fakes, and hand drawn explicit images. The model will be able to detect previous trends in explicit content but may not be able to detect new types or even subtle instances of explicit content. 

### Data Preparation

#### Data Set Formatting

#### Missing Data

#### Dirty Data

#### Data Anomaly Mitigation

### Behaviors for Handling & Communicating Data


