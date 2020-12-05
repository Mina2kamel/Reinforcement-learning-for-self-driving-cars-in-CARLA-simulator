# Steering Model for Autonomous Driving System using Deep Reinforcement Learning

An important part of the Autonomous Driving System (ADS) is the steering system which supposed to emulate the behavior of human drivers as a self-driving car controller. This eliminates the need for human engineers to anticipate what is important in an image and to foresee all the necessary rules for safe driving. The most mature machine learning framework that can be put forward to do such task is Deep Reinforcement Learning (DRL) due to its ability to work and interact with virtual simulation environment. In this thesis work, we try to train our car in Carla simulator using DRL algorithms, our code is implemented in python with PyCharm editor and we used anaconda3 as a command prompt. First, we used DQN(Deep-Q-Learning) algorithm in order to train our model to see if our agent can take continuous actions. We trained using two models, the first is Xception model which is using Xception that is a good model for training self-driving cars. It is a model in Keras with71 hidden layers. And the other model is a 64x4 convolutional neural network (CNN) that is much simpler and has less parameters to learn compared to the first model.

# requirements:
Install carla 9.5\
tensorflow-gpu==1.15.0\
keras==2.2.3
