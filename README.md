# Extreme-Learning-Machine Algorithm Vs Convolution Neural Networks Vs Feed Forward Neural Networks.

This project was done as part of the course Introduction to Intelligent Systems at IU Bloomington.

# Abstract

In December 2005, Guang-BinHuang, Qin-Yu Zhu and Chee-Kheong Siew proposed Extreme Learning Machine (ELM) algorithm as a faster alternative to the traditional iterative machine learning models [1]. In the past few decades, the Machine Learning community has proliferated, and every few months, there is a new machine learning model or a new machine learning technique introduced. Since the introduction of ELM, many modifications have been made to the algorithm to keep it up to date with the new emerging machine learning models and techniques. In 2012, Guang-Bin Huang, Hongming Zhou, Xiaojian Ding, and Rui Zhang proposed ELM for Regression and Multiclass classification [2]. The authors of the paper took a note from the success of Support Vector Machines and their variations in solving classification problems and combined SVM with the Extreme Learning Machine algorithm. This project 1)Implements the ELM algorithm for Regression and Multiclass classification over the Fashion-MNIST dataset and 2)Compares the accuracy and time performance of the algorithm to the performance of conventional neural network architectures such as Convolutional Neural Networks and Deep Neural Networks. The results of the project highlight both the benefits and limitations of the Extreme Learning Machine Algorithm.

# Conclusions
Extreme Learning Machine algorithms are high-speed and can give a pretty good accuracy within a fraction of the time taken by conventional neural networks. ELMs can be very useful for applications where both time and accuracy are of concern. However, since there are fewer hyperparameters to tune, ELM gives us less control over optimizing the algorithm and reaching the desired accuracy. ELMs perform better on CPU.
Other neural network architectures, such as DNN (Fully connected) and CNN converge very slowly compared to ELM. However, these neural networks have many hyperparameters that can be tuned to increase accuracy performance. They perform better on GPU.
Some hybrid algorithms of ELM and multi-layer neural networks have been proposed where the number of layers in ELM is increased. These algorithms might give a better accuracy performance within a similar timeframe and are worth exploring.

# References:
1. Guang-Bin Huang, Qin-Yu Zhu, and Chee Siew. Extreme learning machine: Theory and applications. Neurocomputing, 70:489–501, 12 2006.
2. Guang-Bin Huang, Hongming Zhou, Xiaojian Ding, and Rui Zhang. Extreme learn- ing machine for regression and multiclass classification. ieee trans. syst. man cybern. 42(2), 513-529. IEEE transactions on systems, man, and cybernetics. Part B, Cyber- netics : a publication of the IEEE Systems, Man, and Cybernetics Society, 42:513–29, 10 2011.
