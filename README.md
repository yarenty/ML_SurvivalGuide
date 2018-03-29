Machine Learning Survival Guide
-------------------------------

(C)2018 by [YarentY](http://www.yarenty.com)


> With programming skils and math knowledge of calculus, probability, algebra, optimization
> within 6 month one could get good backgroung in Machine Learning.  
> -- <cite>from Yoshua Bengio interview</cite>


# About
This is quick crash course into Machine Learning and Artificial Intelligence.
It is based on 2 main books:
 - Ian Goodfellow, Youshua Bengio, Aaron Courville: "Deep Learning" - 2016
 - Trevor Hastie, Robert Tibshirani, Jerome Friedman: "The Elements of Statistical Learning: Data Mining, Inference, and Prediction", 2017
 - and [deeplearning.ai](http://www.deeplearning.ai) course. 



> You need to have a full understanding of the whole stack.   
> And that's where I learned the most myself as well when I was learning this stuff is just implementing it myself from scratch was the most important. 
> It was the piece that I felt gave me the best kind of bang for the buck in terms of understanding.   
> And so that's something that I keep advising people is that you not work with flow or something else.   
> You can work with it once you have written at something yourself on the lowest detail, you understand everything under you,
> and now you are comfortable to. Now, it's possible to use some these frameworks that abstract some of it away from you, 
>  but you know what's under the hood.  
> \[...\] that's what I would advise a lot of people.  
> -- <cite>Andrej Karpathy, advice from interview with Andrew Ng</cite>

# Contents  
- lessons about minimum level of math needed to introduce you into the field of ML
- lessons about different ML algorithms and reasoning behind
- higher ML: RNN/CNN/CapsuleNet
- intro to popular libraries / technologies:
    - tensorflow
    - h2o
    - prophet
    - caffe
    - mxnet
    - spark
    - scikit-learn
- intro into popular solutions:
    - MS Azure - Machine Learning Studio
    - Google Cloud Platform
    - AI Alpha Zero 
- challenges - several challenges from different domains with weekly goals, 
where anyone could start testing learned tools/methodologies on real world scenarios



# Structure
- [Lessons](LESSONS). Syllabus:
    - Done:
        - [Getting Started](LESSONS/00_GettingStarted) - Env. installation, first steps in python, tensorflow/h2o - hello world
    - WIP:
        - [Basic Math](LESSONS/01_BasicMath) - Intro to calculus, vectors, matrix multiplications,
        - [Regression](LESSONS/02_Regression) - Predicting House Prices
    - Soon:
        - [Classification](LESSONS/03_Classification) - Sentiment analysis
        - [Feature engineering](LESSONS/04_FeatureEngineering)
        - [Anomaly Detection](LESSONS/05_Anomaly)
        - [Hyperparameters](LESSON/06_Hyperparameters)
        - [Deep NN](LESSONS/07_DeepNN)
        - [CNN](LESSONS/08_CNN)
        - [RNN](LESSONS/09_RNN)
        - [AutoML](LESSONS/10_AutoML)
- [Challenges](CHALLENGES) - different challenges with weekly goals
- [Resources](RESOURCES) - additional resources - books, whitepapers, things to read
- [Changelog.md](CHANGELOG.md) - updates on every new release


*NOTE: Each lesson has it's own challenges, i.e: first lesson challenge is to figure out installation of environment.*



# Important
This project contains large training files - to support them you must install Git Large File Storage extension!
1. Visit: [https://git-lfs.github.com/](https://git-lfs.github.com/) and install package.
2. Run it
3. Run `git lfs install` 
4. (Optional) if you still don't have big data files downloaded run `git lfs pull`
 



# License
[Apache License Version 2.0](LICENSE)

# Author
Jaroslaw Nowosad - [yarenty](http://www.yarenty.com)


> The secret to creativity is knowing how to hide your sources. 
> -- <cite>[Albert Einstein][1]</cite>

[1]:http://www.quotedb.com/quotes/2112