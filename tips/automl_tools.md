# AutoML Tools

Automated Machine Learning (AutoML) is an emerging field in which the process of building machine learning models to model data is automated.

Here is a list of tools that I have found to be helpful to an AI/ML engineer

[All Top Python Libraries for Data Science Explained (with Code)](https://towardsdatascience.com/all-top-python-libraries-for-data-science-explained-with-code-40f64b363663)


## How to choose an ML framework?

[Keras vs PyTorch for Deep Learning](https://towardsdatascience.com/keras-vs-pytorch-for-deep-learning-a013cb63870d)


## Keras Tutorials

[Introduction to Keras for Engineers](https://keras.io/getting_started/intro_to_keras_for_engineers/)

[3 ways to create a Machine Learning model with Keras and TensorFlow 2.0 (Sequential, Functional, and Model Subclassing)](https://towardsdatascience.com/3-ways-to-create-a-machine-learning-model-with-keras-and-tensorflow-2-0-de09323af4d3)

[Introducing TensorFlow Datasets](https://medium.com/tensorflow/introducing-tensorflow-datasets-c7f01f7e19f3)

[Getting started with TensorFlow 2.0](https://medium.com/@himanshurawlani/getting-started-with-tensorflow-2-0-faf5428febae)

[Introducing TensorFlow Datasets](https://medium.com/tensorflow/introducing-tensorflow-datasets-c7f01f7e19f3)

[How to (quickly) Build a Tensorflow Training Pipeline](https://towardsdatascience.com/how-to-quickly-build-a-tensorflow-training-pipeline-15e9ae4d78a0?gi=f2df1cc3455f)



### [Orange](https://github.com/biolab/orange3)

[Orange Docs](https://orangedatamining.com/docs/)

Orange is a data mining and visualization toolbox for novice and expert alike

A great tool for exploratory data analysis (EDA) and to evaluate many models as you narrow the choices for particular dataset.

### [FLAML](https://github.com/microsoft/FLAML)

FLAML is a fast, lightweight Python library that finds accurate machine learning models automatically which frees users from selecting learners and hyperparameters for each learner.

The simple and lightweight design makes it easy to extend such as adding customized learners or metrics. 

FLAML is powered by a new, cost-effective hyperparameter optimization and learner selection method invented by Microsoft Research. 

FLAML leverages the structure of the search space to choose a search order optimized for both cost and error.


### [PyCaret](https://github.com/pycaret/pycaret)

PyCaret is an open-source, low-code machine learning library in Python that automates machine learning workflows. It is an end-to-end machine learning and model management tool that speeds up the experiment cycle exponentially and makes you more productive.

In comparison with the other open-source machine learning libraries, PyCaret is an alternate low-code library that can be used to replace hundreds of lines of code with few words only. This makes experiments exponentially fast and efficient. PyCaret is essentially a Python wrapper around several machine learning libraries and frameworks such as scikit-learn, XGBoost, LightGBM, CatBoost, spaCy, Optuna, Hyperopt, Ray, and many more.


### [dataprep](https://github.com/sfu-db/dataprep)

DataPrep lets you prepare your data using a single library with a few lines of code.

DataPrep.EDA is the fastest and the easiest EDA (Exploratory Data Analysis) tool in Python. It allows you to understand a Pandas/Dask DataFrame with a few lines of code in seconds.

**Create Profile Reports, Fast**

You can create a beautiful profile report from a Pandas/Dask DataFrame with the create_report function. DataPrep.EDA has the following advantages compared to other tools:

10X Faster: DataPrep.EDA can be 10X faster than Pandas-based profiling tools due to its highly optimized Dask-based computing module.
Interactive Visualization: DataPrep.EDA generates interactive visualizations in a report, which makes the report look more appealing to end users.
Big Data Support: DataPrep.EDA naturally supports big data stored in a Dask cluster by accepting a Dask dataframe as input.


### H2O

[h2oai/h2o-3](https://github.com/h2oai/h2o-3)

H2O is an Open Source, Distributed, Fast & Scalable Machine Learning Platform. 

[H2O Docs](https://docs.h2o.ai/)

[H2O Tutorials](https://github.com/h2oai/h2o-tutorials)

[H2O Deep Learning](https://github.com/h2oai/h2o-tutorials/tree/master/tutorials/deeplearning)

[Automated Machine Learning with H2O (towardsdatascience)](https://towardsdatascience.com/automated-machine-learning-with-h2o-258a2f3a203f)

H2O is an in-memory platform for distributed, scalable machine learning. 

H2O uses familiar interfaces auch as R, Python, Scala, Java, JSON and the Flow notebook/web interface and works seamlessly with big data technologies like Hadoop and Spark. 

H2O provides implementations of many popular algorithms such as Generalized Linear Models (GLM), Gradient Boosting Machines (including XGBoost), Random Forests, Deep Neural Networks, Stacked Ensembles, Naive Bayes, Generalized Additive Models (GAM), Cox Proportional Hazards, K-Means, PCA, Word2Vec, as well as a fully automatic machine learning algorithm (H2O AutoML).

H2O is extensible so that developers can add data transformations and custom algorithms of their choice and access them through all of those clients. 

H2O models can be downloaded and loaded into H2O memory for scoring or exported into POJO or MOJO format for extemely fast scoring in production.


### [auto-sklearn](https://github.com/automl/auto-sklearn)

auto-sklearn is an automated machine learning toolkit and a drop-in replacement for a scikit-learn estimator.


### [AutoGluon](https://github.com/awslabs/autogluon)

AutoGluon automates machine learning tasks enabling you to easily achieve strong predictive performance in your applications. With just a few lines of code, you can train and deploy high-accuracy machine learning and deep learning models on text, image, and tabular data.


### [AutoKeras](https://github.com/keras-team/autokeras)

AutoKeras is an AutoML system based on Keras developed by DATA Lab at Texas A&M University. 

The goal of AutoKeras is to make machine learning accessible to everyone.


### [Auto-ViML](https://github.com/AutoViML/Auto_ViML)

Auto_ViML was designed for building High Performance Interpretable Models with the fewest variables. The "V" in Auto_ViML stands for Variable because it tries multiple models with multiple features to find you the best performing model for your dataset. The "i" in Auto_ViML stands for "interpretable" since Auto_ViML selects the least number of features necessary to build a simpler, more interpretable model. In most cases, Auto_ViML builds models with 20-99% fewer features than a similar performing model with all included features (this is based on my trials. Your experience may vary).

Auto_ViML is every Data Scientist's model assistant that:

1. Helps you with data cleaning
2. Assists you with variable classification
3. Performs feature reduction automatically
4. Produces model performance results as graphs automatically
5. Handles text, date-time, structs (lists, dictionaries), numeric, boolean, factor and categorical variables all in one model using one straight process.
6. Allows you to use the featuretools library to do Feature Engineering.


### [AutoViz](https://github.com/AutoViML/AutoViz)

Automatically Visualize any dataset, any size with a single line of code.

AutoViz performs automatic visualization of any dataset with one line. Give any input file (CSV, txt or json) and AutoViz will visualize it.


### [spaCy](https://github.com/explosion/spaCy)

spaCy is a library for advanced Natural Language Processing in Python and Cython. It is built on the very latest research and was designed from day one to be used in real products.

spaCy comes with pretrained pipelines and currently supports tokenization and training for 60+ languages. 

spaCy features state-of-the-art speed and neural network models for tagging, parsing, named entity recognition, text classification and more, multi-task learning with pretrained transformers like BERT, as well as a production-ready training system and easy model packaging, deployment and workflow management. 


### [MediaPipe](https://github.com/google/mediapipe)

Live ML anywhere

MediaPipe offers cross-platform, customizable ML solutions for live and streaming media.

- Face Detectiom
- Face Mesh
- Pose
- Object Detection
- Box Tracking
- Objectron


### [OpenCV](https://docs.opencv.org/master/d9/df8/tutorial_root.html)

[Introduction to OpenCV](https://www.geeksforgeeks.org/introduction-to-opencv/)

[OpenCV Python Tutorial](https://www.geeksforgeeks.org/opencv-python-tutorial/)

OpenCV is a huge open-source library for computer vision, machine learning, and image processing. 

OpenCV supports a wide variety of programming languages like Python, C++, Java, etc. 

OpenCV can process images and videos to identify objects, faces, or eve handwriting.


## Time Series Libraries

### [statsmodels](https://github.com/statsmodels/statsmodels/)

statsmodels is a Python package that provides a complement to scipy for statistical computations including descriptive statistics and estimation and inference for statistical models.

### [stumpy](https://github.com/TDAmeritrade/stumpy)

STUMPY is a powerful and scalable library that efficiently computes something called the matrix profile which can be used for a variety of time series data mining tasks. 

### [Darts](https://github.com/unit8co/darts)

darts is a Python library for easy manipulation and forecasting of time series. It contains a variety of models, from classics such as ARIMA to deep neural networks. The models can all be used in the same way, using fit() and predict() functions, similar to scikit-learn. The library also makes it easy to backtest models, and combine the predictions of several models and external regressors. Darts supports both univariate and multivariate time series and models. The neural networks can be trained on multiple time series, and some of the models offer probabilistic forecasts.

### [AutoTS](https://github.com/winedarksea/AutoTS)

Forecasting Model Selection for Multiple Time Series

AutoML for forecasting with open-source time series implementations.

### [TsFresh](https://github.com/blue-yonder/tsfresh)

tsfresh is a python package that calculates a huge number of time series characteristics or features automatically. 

In addition, the package includes methods for assessing the explanatory power and significance of such traits in regression and classification tasks.




## ML Libraries and Frameworks

## [Kedro](https://github.com/quantumblacklabs/kedro)

[Kedro — A Python Framework for Reproducible Data Science Project](https://towardsdatascience.com/kedro-a-python-framework-for-reproducible-data-science-project-4d44977d4f04)

Kedro is an open-source Python framework for creating reproducible, maintainable, and modular data science code. 

Kedro borrows concepts from software engineering and applies them to machine-learning code such as modularity, separation of concerns, and versioning.


### [PyMC3](https://github.com/pymc-devs/pymc3)

PyMC3 is a Python package for Bayesian statistical modeling and Probabilistic Machine Learning focusing on advanced Markov chain Monte Carlo (MCMC) and variational inference (VI) algorithms. Its flexibility and extensibility make it applicable to a large suite of problems.

[A Gentle Introduction to Bayesian Belief Networks](https://machinelearningmastery.com/introduction-to-bayesian-belief-networks/)

[Building DAGs with Python](https://mungingdata.com/python/dag-directed-acyclic-graph-networkx/)

[bnlearn](https://github.com/erdogant/bnlearn)


### [SageMaker](https://aws.amazon.com/sagemaker/?nc2=h_a1)

SageMaker is a machine learning environment that simplifies the work of an ML developer by providing tools for extra fast model building and deployment.

In 2021, Amazon launched SageMaker Studio, the first integrated IDE for machine learning. It provides a web interface to monitor all possible aspects of the life cycle of an ML model, Jupyter on steroids. Apart from being closely integrated into the AWS cloud it also offers data labeling software and many other features.

### [MXNet](https://github.com/apache/incubator-mxnet)

MXNet is an open-source framework designed to train and deploy deep neural networks with a strong focus on scalability. 

In contrast to the torch and tflow￼ frameworks, MXNet is a child of the Apache foundation and probably the best true open-source framework. 

A rising star and already accessible in many languages, not just Python.

It is not as popular but still supported by all major clouds and can potentially speed up your computations.

### [ONNX](https://github.com/onnx/onnx)

ONNX is a format to represent machine learning models. The goal is that future developers are no longer forced to pick a model that has been trained in their particular framework.

ONNX achieves this goal by using a common set of operators (the mathematical operations) that happen between the different layers and a common file format. 

ONNX is backed by pretty most of the big AI players and is sure to have a huge impact on the future of ML development. Apart from Google all of the tech giants are partners in this project.


### [wandb](https://docs.wandb.ai/)

Weights and biases (W&B/wandb) lets you track, compare, visualize, and optimize machine learning experiments with just a few lines of code. wandb also lets you track your datasets. 

Using W&B's lightweight tools, you can quickly track experiments, version and iterate on datasets, evaluate model performance, reproduce models, visualize results and spot regressions, and share findings with colleagues. 

### [MLFlow](https://github.com/mlflow/mlflow)

[Tutorial](https://www.mlflow.org/docs/latest/tutorials-and-examples/tutorial.html)

Similar to W&B, MLFlow provides functionality for logging code, models, and datasets on which your model has been trained. 

MLflow is a platform to streamline machine learning development including tracking experiments, packaging code into reproducible runs, and deploying models. 

MLflow offers a set of lightweight APIs that can be used with any existing machine learning application or library (TensorFlow, PyTorch, XGBoost, etc.) wherever you currently run ML code (such as notebooks, standalone applications, or the cloud). 

### gRPC

The trend now is toward gRPC for microservices since it is more secure, faster, and more robust (especially with IoT).

[gRPC with REST and Open APIs](https://grpc.io/blog/coreos/)

- gRPC was recommended for developing microservices by my professor in Distributed Computing course.

- gRPC uses HTTP/2 which enables applications to present both a HTTP 1.1 REST/JSON API and an efficient gRPC interface on a single TCP port (available for Go). 

- gRPC provides developers with compatibility with the REST web ecosystem while advancing a new, high-efficiency RPC protocol. 

- With the recent release of Go 1.6, Go ships with a stable net/http2 package by default.

### [Screen](https://linuxize.com/post/how-to-use-linux-screen/)

Screen is a GNU linux utility that lets you launch and use multiple shell sessions from a single ssh session. The process started with screen can be detached from session and then reattached at a later time. So your experiments can be run in the background, without the need to worry about session closing, or terminal crashing.

### Lucidchart

Lucidchart is a diagraning too that also has shared space for collaboration and the ability to make notes next to diagrams. 

### Streamlit

Streamlit turns data scripts into shareable web apps in minutes. 

Streamlit is one of the fastest way to build and share data apps. 

All in Python. All for free. No front‑end experience required.



## Deep Learning Tools

### [Hydra](https://hydra.cc/docs/intro/) 

Hydra provides a configuration file for the entire experiment. 

Hydra is helpful when we want to share our code with someone else or run the experiments on a different machine. 

Hydra provides the flexibility to set the desired configurations like learning rate, model hidden layer sizes, epochs, data set name, etc. without having to make changes to the actual code.

### [Pipreqs](https://pypi.org/project/pipreqs/) 

Pipreqs is useful when we want to port our code to a different machine and install all the dependencies. 

Pipreqs helps to create a list of python dependencies along with the versions that the current working code is using and saves them in a file that can be easily installed anywhere.

### [Loguru](https://loguru.readthedocs.io/en/stable/api/logger.html)

Loguru provides the functionality of a logger to log configuration, experiment name, and other training-related data.

Loguru provides the functionality of a logger to log configuration, experiment name, and other training-related data. 

### [H5py](https://docs.h5py.org/en/stable/quick.html)

H5py can be used to store all the intermediate loss values in a dictionary mapped to appropriate key which can be loaded to be reused as a python code.

### Pickle 

Picklecan be used to save and load the python classes or PyTorch models for reuse.

### [Tqdm](https://tqdm.github.io/) 

Tqdm can be used with a loop (such as a loop over a torch `DataLoader` object) to provide a picture of time per gradient step or epoch which can help in setting logging frequency of different results, saving the model, or getting an idea of how to set the validation intervals.


## Feature Engineering Tools

There are many tools that will help you in automating the entire feature engineering process and producing a large pool of features in a short period of time for both classification and regression tasks.

### [Feature-engine](https://github.com/feature-engine/feature_engine)

Feature-engine is a Python library with multiple transformers to engineer and select features for use in machine learning models. Feature-engine's transformers follow scikit-learn's functionality with fit() and transform() methods to first learn the transforming parameters from data and then transform the data.

### [Featuretools](https://github.com/alteryx/featuretools)

Featuretools is a framework to perform automated feature engineering that excels at transforming temporal and relational datasets into feature matrices for machine learning. 

Featuretools integrates with the machine learning pipeline-building tools you already have. 

In a fraction of the time it would take to do it manually, you can load in pandas dataframes and automatically construct significant features.

### AutoFeat

AutoFeat helps to perform Linear Prediction Models with Automated Feature Engineering and Selection. 

AutoFeat allows you to select the units of the input variables in order to avoid the construction of physically nonsensical features.



## NLP Tools

### [clean-text](https://github.com/jfilter/clean-text)

User-generated content on the Web and in social media is often dirty. Preprocess your scraped data with clean-text to create a normalized text representation.



## References

[Colaboratory FAQ](https://research.google.com/colaboratory/faq.html#resource-limits)

[Tools for Efficient Deep Learning](https://towardsdatascience.com/tools-for-efficient-deep-learning-c9585122ded0)
