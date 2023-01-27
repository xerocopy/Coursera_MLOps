# Coursera_MLOps

#### This is a notepad along with my study. I think it will be handy when I need to look back sometime later and probably useful for other peer learners to find things.


### Course 1 Introduction to Machine Learning in Production
This is a compilation of resources including URLs and papers appearing in lecture videos.

Overall resources:

Konstantinos, Katsiapis, Karmarkar, A., Altay, A., Zaks, A., Polyzotis, N., … Li, Z. (2020). Towards ML Engineering: A brief history of TensorFlow Extended (TFX). http://arxiv.org/abs/2010.02013 

Paleyes, A., Urma, R.-G., & Lawrence, N. D. (2020). Challenges in deploying machine learning: A survey of case studies. http://arxiv.org/abs/2011.09926

Week 1: Overview of the ML Lifecycle and Deployment
Concept and Data Drift

Monitoring ML Models

A Chat with Andrew on MLOps: From Model-centric to Data-centric AI

Konstantinos, Katsiapis, Karmarkar, A., Altay, A., Zaks, A., Polyzotis, N., … Li, Z. (2020). Towards ML Engineering: A brief history of TensorFlow Extended (TFX). http://arxiv.org/abs/2010.02013 

Paleyes, A., Urma, R.-G., & Lawrence, N. D. (2020). Challenges in deploying machine learning: A survey of case studies. http://arxiv.org/abs/2011.09926

Sculley, D., Holt, G., Golovin, D., Davydov, E., & Phillips, T. (n.d.). Hidden technical debt in machine learning systems. Retrieved April 28, 2021, from Nips.cc 

https://papers.nips.cc/paper/2015/file/86df7dcfd896fcaf2674f757a2463eba-Paper.pdf

Week 2: Select and Train Model
Establishing a baseline

Error analysis

Experiment tracking

Brundage, M., Avin, S., Wang, J., Belfield, H., Krueger, G., Hadfield, G., … Anderljung, M. (n.d.). Toward trustworthy AI development: Mechanisms for supporting verifiable claims∗. Retrieved May 7, 2021 http://arxiv.org/abs/2004.07213v2

Nakkiran, P., Kaplun, G., Bansal, Y., Yang, T., Barak, B., & Sutskever, I. (2019). Deep double descent: Where bigger models and more data hurt. Retrieved from http://arxiv.org/abs/1912.02292

Week 3: Data Definition and Baseline
Label ambiguity

https://arxiv.org/pdf/1706.06969.pdf

Data pipelines

Data lineage

MLops

Geirhos, R., Janssen, D. H. J., Schutt, H. H., Rauber, J., Bethge, M., & Wichmann, F. A. (n.d.). Comparing deep neural networks against humans: object recognition when the signal gets weaker∗. Retrieved May 7, 2021, from Arxiv.org website:


### Course 2 Machine Learning Data Lifecycle in Production

Data Journey and Data Storage Resources:
Data Versioning:

https://dvc.org/

https://git-lfs.github.com/

ML Metadata:

https://www.tensorflow.org/tfx/guide/mlmd#data_model

https://www.tensorflow.org/tfx/guide/understanding_custom_components

Chicago taxi trips data set: 

https://data.cityofchicago.org/Transportation/Taxi-Trips/wrvz-psew/data

https://archive.ics.uci.edu/ml/datasets/covertype

Feast:

https://cloud.google.com/blog/products/ai-machine-learning/introducing-feast-an-open-source-feature-store-for-machine-learning

https://github.com/feast-dev/feast

https://www.gojek.io/blog/feast-bridging-ml-models-and-data


### Course 4 Machine Learning Engineering for Production

More materials and lab data are available at my other forked repository from Coursera (https://github.com/xerocopy/machine-learning-engineering-for-production-public.git)

Links on model servers:

1. tensorflow serving: https://www.tensorflow.org/tfx/serving/architecture

2. torchserve: https://github.com/pytorch/serve

3. kubeFlow serving: https://www.kubeflow.org/docs/external-add-ons/serving/

4. NVIDIA Triton: https://developer.nvidia.com/nvidia-triton-inference-server

#### scaling with boy bands
In the next few minutes you’ll learn about horizontal and vertical scaling. Before going into that, here’s a fun case study on managing scale. 

In this extreme case a famous boy band called ‘One Direction’ hosted a 10-hour live stream on YouTube, where they instructed fans to go visit a web site with a quiz on it every 10 minutes. This led to a really interesting pattern in scalability where the application would have zero usage for the vast majority of the time, but then, every 10 minutes may have hundreds of thousands of people hitting it. 

It’s a complex problem to solve when it comes to scaling. It could be very expensive to operate. Using smart scaling strategies, Sony Music and Google solved this problem very inexpensively. Laurence isn’t allowed to share how much it cost for the cloud services, but, when he and several of the other engineers went out for celebration drinks after the success of the project, the bar bill was more expensive than the cloud bill. (And they didn’t drink a lot!) 

Check out the talk about how scaling worked for this system here: https://www.youtube.com/watch?v=aIxNm5Eed_8

Learn about the event and the app here: https://www.computerweekly.com/news/2240228060/Sony-Music-Google-cloud-One-Directions-1D-Day-event-platform-services

#### Experiment Tracking
Learn more about experiment tracking by checking this two resources out:

[Machine Learning Experiment Tracking](https://towardsdatascience.com/machine-learning-experiment-tracking-93b796e501b0)

[Machine Learning Experiment Management: How to Organize Your Model Development Process](https://neptune.ai/blog/experiment-management)