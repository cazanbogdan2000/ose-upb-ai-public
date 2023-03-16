# Orange Services [Data & AI]

> **Note**: This course should be mostly hands-on, with live coding sessions in each course and a 4 weeks homework which should be uploaded at the end of the course in order to differentiate between students. Each course will have a small introduction (slides) and then we jump right into the coding part where I can share with them best practices, tricks, models and everything else which is necessary for someone who will possibly join Orange Services in the Data and AI team.
> 

> Note: The application part of the course will be coded in Python using for some parts the PyTorch framework.
> 

## Structure

1. Intro to AI applications in telecom industry
    1. Presenting a short intro of use-cases from telecom world where we can use AI/ML for achieving better results. Mainly a theoretical course where I should evaluate the level of Mathematics / Computer science general knowledge of the students and I should decide on how to proceed in the next lectures. 
    2. Topics which could be discussed in this course: 
        1. Predictive networks - How ML models can help us to reduce the latency in the mobile world
        2. Marketing helpers (Recommender systems)
        3. TBD
2. Clustering
    1. Focus of the core of the problem and its application for Orange Services. On brief: Large volumes of data cannot bring insights without a basic clustering over them.
    2. Application: 
        1. K-Means from scratch (not the whole code base - part of it should be completed as an assignment)
        2. Data gathering from a public API / platform
            - How to get data from kaggle with command line tools
3. Regression 
    1. Spotlight: Orange services is using large amount of temporal data, from network activity time series to user activity time series. This type of data requires some level of knowledge, which means that we need to be able to make accurate predictions on this data.
    2. The main point for the application part is to code a linear regression from scratch
        1. Live coding a linear regression (Not the whole codebase - part of it should be completed as an assignment)
        2. Find a dataset with network activity data which can be used in this example
4. Classification
    1. Theory regarding the applications of classification in user behavior 
    2. Coding a Support Vector Machine from scratch (finish this one)
    3. Test on some fake user data / anonymized data maybe
    4. Discuss results  
5. Anomaly detection
    1. Introduction to **predictive networks** and how the world of telecom is actually working. Discuss the theory behind each mobile data transfer and how it is done. 
    2. Second part: Introducing the idea of Neural Networks (universal approximators). 
        1. Short live coding session using a simple dataset
        2. Short discussion on models which can help us on this topic
        3. Presenting the Auto Encoder / Decoder
6. Generative models
    1. Data is not always available and moreover, when it is, is hard to gather and process. This course will make the point on synthetic data and how we can generate them in a simple use-case, where we are not allowed, for example, by the GDPR to gather data from users. 
    2. Short into with the history of the generative models (Gaussian Mixture Models, Variational Auto Encoders, Generative Adversarial Networks, Diffusion models)
    3. Live coding a GAN using the Fashion MNIST dataset (~1h to code and test)
7. MLOps - hands on full course
    1. We have a model, how we can actually use it in production. Introducing DevOps, CI/CD and data gathering techniques for machine learning engineers. Because our work is evolving around Google Cloud Platform, in this course I will show off the main parts of Google Cloud Platform and how we can put a model in production for a simple use case. 
        1. Intro to GCP
        2. We will use a model from previous weeks and we will make it into production 
8. Internal project presentation - invited speaker
    1. TBD
    

## Assignment

The course will have a 4 week assignment which will consist of 

1. Finishing the coding part from the course / testing it / improving the performance of the models and finally upload it to a GitHub project 
    1. K-Means 
    2. Linear Regression
    3. Difficulty: 5/10
2. Detect simple anomalies using self organizing maps (SOM) on Orange services data 
    1. Possibly a Kaggle competition ( I am not sure in this moment )
    2. The homework will include a skeleton
    3. It will test how they can adapt the knowledge from the course to a real word scenario
    4. Difficulty: 8/10
