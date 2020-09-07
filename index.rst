
.. _index:

****************************************
Analytics ZOO
****************************************

.. _dsg-what-is-analytics-aoo?:

What is Analytics Zoo?
======================

Analytics Zoo seamless scales TensorFlow, Keras and PyTorch to distributed big data (using Spark, Flink & Ray).


* **End-to-end pipeline for applying AI models (TensorFlow, PyTorch, OpenVINO, etc.) to distributed big data** 
    * Write [TensorFlow](ProgrammingGuide/TFPark/tensorflow.md) or [PyTorch](ProgrammingGuide/pytorch.md) inline with Spark code for distributed training and inference.
    * Native deep learning (TensorFlow/Keras/PyTorch/BigDL) support in [Spark ML](ProgrammingGuide/nnframes.md) Pipelines.
    * Directly run [Ray](ProgrammingGuide/rayonspark.md) programs on big data cluster through _RayOnSpark_. 
    * Plain Java/Python APIs for (TensorFlow/PyTorch/BigDL/OpenVINO) [Model Inference](ProgrammingGuide/inference.md). 

* **High-level ML workflow for automating machine learning tasks**
  - [Cluster Serving](ClusterServingGuide/ProgrammingGuide.md) for automatically distributed (TensorFlow/PyTorch/Caffe/OpenVINO) model inference . 
  - Scalable [AutoML](ProgrammingGuide/AutoML/overview.md) for time series prediction.

  - **Built-in models** for [Recommendation](APIGuide/Models/recommendation.md), [Time Series](APIGuide/Models/anomaly-detection.md), [Computer Vision](APIGuide/Models/object-detection.md) and [NLP](APIGuide/Models/text-matching.md) applications.



.. _dsg-why-use-analytics-aoo?:

Why use Analytics Zoo?
======================

.. _dsg-how to-use-analytics-aoo?:

How to use Analytics Zoo?
=========================