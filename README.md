# Deployment screenshot:
<img src="/src/build.png" alt="Alt text" title="Optional title">
<img src="/src/success_deployment.png" alt="Alt text" title="Optional title">
<img src="/src/cloud_formation.png" alt="Alt text" title="Optional title">
<img src="/src/check_logs.png" alt="Alt text" title="Optional title">
# teslabot questions and responses:
# What is the definition of a serverless application?
Severles is a cloud-native developoment model that allows developers to build and run applications without having to manage servers.

# What is the definition of model serving and what are the two types?
It is to host machine learning models on the cloud or on premises to make their functions available via API. So the applications can incorpate AI into the system.
The two types are batch and online. 

1. Batch means that you feed the model , typically as a scheduled job, with a large amount of data and write the output to a table. This type is tipycally running on local machines.
2. Online deployment means that you deploy the model with an endpoint so applications can send a request to the model and get a fast response at low latency. This type is mostly running on cloud.

# What are 3 advantages of deploying using Model Serving methods Vs. deploying on GitHub Pages or HuggingFace for free?
1. Less server down-time.
2. Third-parties provision necessary resources.
3. Easier teamwork.

# What Is Machine Learning Inference? How Does Machine Learning Inference Work? Please walk us through an example?
Machine learning inference is the process of running data points into a machine learning model to calculate an output such as a single numerical score. This process is also referred to as “operationalizing a machine learning model” or “putting a machine learning model into production.”
ads. recommendation. It is based on your browse history, the company can recommend you contents. This recommendation system is based upon the machine learning calculation results. It will recommend based upon high probability of your preference.