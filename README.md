# Deep Temporal Similarity

Deep Learning methods have dramatically improved the state-of-the-art across multiple fields, such as speech recognition, object detection, among others. Nevertheless, its application on signal processing, where data is frequently unlabelled, has received relatively little attention. In this field, nowadays, a set of sub-optimal techniques are often used. They usually require an expert to manually extract features to analyse, which is a knowledge and labour intensive process. Thus, a self-learning technique could improve current methods. Moreover, certain machines in a factory are particularly complex, such as an oil-hydraulic press. Here, its sensors can only identify few failures by setting up some thresholds, but they commonly cannot detect wear on its internal components. So, a self-learning technique would be required to detect anomalies related to deterioration. The concept is to determine the condition of a machine and to predict breakdowns by analysing patterns in the measurements from their sensors. This document proposes a self-learning methodology that uses a deep learning model to predict failures in such a machine. The core idea is to train an algorithm that can identify by itself the relevant features to extract on a work cycle, and to relate them to a part which will breakdown. The conducted evaluation focuses on an example case where a hydraulic accumulator fails. As result, it was possible to forecast its breakdown two weeks in advance. Finally, the proposed method provides explanations at every step, after acknowledging their importance in industrial applications. Also, some considerations and limitations of this technique are stated to support guiding the expectation of some stakeholders in a factory, i.e. a (Global) Process Owner.  

#### Keywords
Signal Processing, Deep Learning, Machine Learning, Predictive Maintenance, Anomaly Detection


## Getting Started
This repository serves to share the algorithm published in my Master Thesis.
[Master Thesis full document](http://www.diva-portal.org/smash/record.jsf?pid=diva2%3A1523089&dswid=-6680) <br/>

Nevertheless, the source data used is not available, but you may try it on any other continuous measurement, in which a repetitive pattern its found.

**Prerequisites**
* Install all the libraries listed in `requirements.txt`
* Change the data directories to use your own data (i.e. data_dir1, data_dir2, etc.)

I strongly recommend you to use a GPU to train your models for analysing high frequency data.
<br/>
<br/>
Enjoy! :) 
