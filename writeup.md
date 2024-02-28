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
The following works were used to help guide the proposal and provide context to the project.

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
A rough estimate of the project timeline is as follows:

Timeline Overview:
|Sprint| Dates | Task |
|------|-------|------|
| 0    | 1-2 weeks | Project Planning |
| 1    | 1-2 weeks | Data Collection |
| 2    | 1-2 weeks | Data Preparation |
| 3    | 1-2 weeks | Model Training |
| 4    | 1-2 weeks | Integration & Testing |
| 5    | 1-2 weeks | Evaluation |
| 6    | 1-2 weeks | Model Deployment |

### Resources and Costs

Using estimates from [Microsoft Azure Visions Pricing](https://azure.microsoft.com/en-us/pricing/details/cognitive-services/computer-vision/) as well as the daily estimates for the number of images uploaded to [Instagram](https://bernardmarr.com/how-much-data-do-we-create-every-day-the-mind-blowing-stats-everyone-should-read/), we can estimate the cost of the machine learning solution.

Assuming:

- 100,000,000 Daily Uploaded Images
- $0.40 Per 1000 Images @ at least 1,000,000 transactions per day

| Resource                        | Cost                 |
| ------------------------------- | -------------------- |
| Engineering Labor               | $100K-150K           |
| Database Storage                | $10,000              |
| Data Processing                 | $10,000              |
| Machine Learning Model Training | $10,000              |
| Upfront Cost Total              | ~$130K-180K          |
| Machine Learning Cloud Server   | ~$35K-45K daily      |
| Maintenance Engineering Labor   | $10K-15K monthly     |
| On-Going Total                  | ~$1M - 1.35M monthly |

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

The data will need to be prepared for the training of the machine learning model through cleaning, formatting, and anomaly mitigation. The data will be cleaned to removed any irrelevant, spam, duplicate, or mis-categorized images. All the images will be formatted to the standard canvas and file size that images are stored and views on the platform. Using these goals in mind, checks and validation will be ran on the data to mitigate data anomalies and ensure that the data is consistent and ready for training.

### Behaviors for Handling & Communicating Data

It is important that when handling the data that we are transparent with the company and the users about the use of their data. This needs to be done with respect for the users because some users may not want their images to be used for training machine learning models. Once the model is implemented, the images should be user anonymized and the model should not store any images that are being processed in the future. This is because the model will be used on images that are uploaded to the platform which some users may eventually want to delete. We may eventually revisit and retrain the model with new data later on to improve the model's accuracy and performance.

## References

(1) .

(2) .

(3) .

(4) Microsoft. "Microsoft Azure Pricing" Azure.Microsoft.com https://azure.microsoft.com/en-us/pricing/details/cognitive-services/computer-vision/ Accessed Feb 16,2024.

(5) Bernard Marr & Co. "How Much Data Do We Create Every Day? The Mind-Blowing Stats Everyone Should Read" BernardMarr.com https://bernardmarr.com/how-much-data-do-we-create-every-day-the-mind-blowing-stats-everyone-should-read/ Accessed Feb 16,2024.
