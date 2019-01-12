# Facial Expression Detection using Convolutional Neural Networks
Facial Expression Detection using Convolutional Neural Networks. Project for Machine Learning (CIS519) at the University of Pennsylvania.

For this project, we used a basic Convolutional Neural Network to detect facial expressions. There are two experiments outlined in this project: (1) Training and testing on separate subsamples (train on female faces, detect on male), and (2) train on peak expression and test on mid-level expression. We used two networks, one modeled off of AlexNet and another smaller network, which we have affectionately called MiniNet. These networks were implemented in PyTorch. 

The facial expression database used was the Cohn-Kanade Database of faces, linked here: http://www.consortium.ri.cmu.edu/ckagree/
