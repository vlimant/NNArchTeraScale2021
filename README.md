# Hands-on on Neural Network Architecture at the Terascale School of Machine Learning 2021
https://indico.desy.de/event/28296/

## Architecture Search
### Starter Notebook
We compare two simple trained models and discuss the potential issues with that comparison.

Hands-on:

https://github.com/vlimant/NNArchTeraScale2021/blob/master/modelCompare.ipynb

### Model Training
As a practical guide to training models, we provide a couple of ingredients to be more confident that a model has converged.

Hands-on:

https://github.com/vlimant/NNArchTeraScale2021/blob/master/solutions/modelTrain.ipynb

### Model Optimization
Given a model structure, one is usually left with a hand-full of hyper-parameters to scan. We provide a practical guide to navigating these.

Hands-on:

https://github.com/vlimant/NNArchTeraScale2021/blob/master/solutions/hyperOpt.ipynb

### Cross-Validation
Given a training dataset, the evaluation of a trained model can be subject to fluctuation due to the choice of test dataset. We provide an example of performing cross-validation and reach a more accurate estimation of the model performance.

Hands-on:

https://github.com/vlimant/NNArchTeraScale2021/blob/master/solutions/dataFold.ipynb

### Data Efficiency
Given a model and a training dataset, one may wonder if the model could do better with more training samples. We explore the behavior of models on training dataset of variable size.

Hands-on:

https://github.com/vlimant/NNArchTeraScale2021/blob/master/solutions/dataEfficiency.ipynb

## Graph Neural Networks Examples
### Particle-Flow Reconstruction with GNN
Exercise notebook based on the model featured in "MLPF: Efficient machine-learned particle-flow reconstruction using graph neural networks" https://arxiv.org/abs/2101.08578.
We explore the formulation of the different part of the model designed for particle-flow reconstruction.

Original material:

https://github.com/jpata/particleflow

Hands-on:

https://github.com/vlimant/NNArchTeraScale2021/blob/master/graphs/mlParticleFlow.ipynb

### Set-2-Graph models for track clustering in jets
Exercise notebook based on the model featured in "Secondary Vertex Finding in Jets with Neural Networks" https://arxiv.org/abs/2008.02831

Original material:

https://github.com/hadarser/SetToGraphPaper

Hands-on:

https://github.com/vlimant/NNArchTeraScale2021/blob/master/graphs/set2graph.ipynb

### Interaction Network for jet tagging
Exercise notebook on the interaction network model used for jet tagging in "JEDI-net: a jet identification algorithm based on interaction networks" https://arxiv.org/abs/1908.05318

Original material:

https://github.com/jmduarte/JEDInet-code

https://github.com/jmduarte/capstone-particle-physics-domain

Hands-on:

https://github.com/vlimant/NNArchTeraScale2021/blob/master/graphs/jediNet.ipynb
