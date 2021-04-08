---
title: "Notes from Genova Deep Learning Summer School 2018"
last_modified_at: 2016-03-09T16:20:02-05:00
categories:
  - Blog
tags:
  - deep learning
  - machine learning
  - italy
  - summer school
---

The following are my notes from the [Deep Learning Summer School 2018](http://irdta.eu/deeplearn2018/) in Genova, Italy, 2018. 

## Zaki: Introductory Tutorials on Regression and Deep Learning

Frameworks: `Kera 10`, `PyTorch`, `TensorFlow`
**Part 1: Regression:** 
* Goal: Fit the data
* Prediction accuracy evaluation metrics: `OLS` (Ordinary Least Square), `SSE` (Sum of Squared Errors) 
* Simplest way: Linear Regression
* A bias is added into the linear formulation of the predicted value: \\( \hat{y}_i = b + w_1 \cdot x_1 + \cdots w_d \cdot x_d \\)		
* Example: Bivariate
* Note: Regression expressed by the projections of one vector on the span (surface) formed by other vectors
* Extention: Multiple regression
* Error function: Show how well trained a network is
* Gradients: Parallel derivatives 
* Regularization: \\(L_1, L_2\\)
**Part 2: Logistic Regression**
* `Sigmoid`, `tanh` function acting like `ReLU` (activation function)
* `Cross-entropy`: \\( Likelihood = \mathbb{P} (Data \| Parameters) = \mathbb{P} (D \| w) \\) 
* `Stochastic Gradient Descent` (SGD): Find the smallest by going downward
	* Compute for one single point
	* Initial guess of weights: \\(w^0 = (0,0, \cdots, 0). \\)
	* Compute `SGD` at this point and then update the weights for all points (back-propagation)
**Part 3: From Perception to Multilayer Perceptions (`MLP`) to CNN**
* Any neuron is connected to others with weights

## Gschwind (Huawei): Deploy DL Applications at Enterprise-Scale
**Rule-based reasoning**
* Limit: Data classification for rich, but fuzzy data \\( \rightarrow \\) Not enough resources (human, time, etc.)
to write all rules for complex objects with many possible variations 
* Rules: Often complex, non-intuitive
**Developer-centric AI ecosystems:**
* PowerAI: IBM
* Deep Learning containers: NVIDIA
* Cloud AutoML: Google
* Azure DL virual machine: Microsoft
**Performance evaluation and measurement:**
* Comparation of execution time
* Drawback: Optimization that improves 1 metric often degrade others
	* Image/Time
	* Time/Epoch
	* Epoch to convergence
* \\( \uparrow \\) parallelism: OK
* \\( \uparrow \\) batch size: OK. Nevertheless: \\( \uparrow \\) convergence but \\( \downarrow \\) gain
* Lower precision: Trading off FP precision and throughput  

## Xing: NN Programming
**Symbolic programming vs. Imperative programming**
* Symbolic: `Caffe`, `PyTorch`
* Imperative: `TensorFlow`, `theano`, `Caffe2`
**Building an NN:**
* In general: One needs those following information in order to build an NN:
	* I/O dataflow?
	* Number of layers [full-connected (`fc`), convolution (`conv`), rectifier (`ReLU`)]
	* Objective function, loss function
	* Connect operations
* Static Declaration (`SD`)
* `SD` for *Dynamic* NN (Dataflow graph): (1) Static Unroll; (2) Bucketing; and (3) Dynamic Unroll (in `TensorFlow`)
	(1) Static Unroll: Scan all data and make them have the same length
	(2) Bucketing: Scan all data and then put into different buckets, one bucket is one NN
	(3) Dynamic Unroll: Control flow operations
* Dynamic Declaration (`DD`): Declare and construct each Dataflow graph *for each* input sample

## Li Errran Li: Deep Reinforcement Learning

**Reinforcement learning**
* MDP planning: 
	* Planning: Assumed a full knowledge of MDP. Leads us to Dynamic Programming
		* Policy interation
		* Value iteration
* Model-free prediction and control: 
	* Prediction: Given \\(M\\) and \\(\pi\\), find \\(S, Q\\). Estimate the `v-function` of an unknown MDP
	* Optimal control: Given \\(M\\), find \\(\pi^{\star}\\). Optimize `v-function` of an unknown MDP`
		* Monte-Carlo 
		* Temporal-Difference (TD)
* MDP applications: 
	* Optimal control primarily: Continuous MDPs
	* Partially observable problems: Can be converted to MDPs
	* Bandits: One-state MDP

**Deep Q-Learning:** 
* `Q-Net`: Mnih et al. Nevertheless Q-net in this paper is not up-to-date
* Improvements to Deep Q-Network:
	* Double Q-Network
	* Prioritised replay: Weighting experience according to surprise, i.e., storing experience in priority 
	queue according to DQN error
	* Duelling networl: Split Q-Net into 2 channels:
		* `V(s,v`: Action-independent value function
		* `A(s,a,w)`: Action-independent advantage function
* Frameworks: `rllab`, `OpenAIGym`
* Games: universe.openai.com, deepmindlab
