# CS583: Deep Learning


1. **Machine learning basics.**
This part briefly introduces the fundamental ML problems-- regression, classification, dimensionality reduction, and clustering-- and the traditional ML models and numerical algorithms for solving the problems.

    * ML basics. 
    [[slides-1](https://github.com/wangshusen/DeepLearning/blob/master/Slides/1_ML_Basics.pdf)]
    [[slides-2](https://github.com/wangshusen/DeepLearning/blob/master/Slides/1_Models.pdf)]

    
    * Regression. 
    [[slides-1](https://github.com/wangshusen/DeepLearning/blob/master/Slides/2_Regression_1.pdf)] 
    [[slides-2](https://github.com/wangshusen/DeepLearning/blob/master/Slides/2_Regression_2.pdf)]
    
    
    * Classification. 
    
        - Logistic regression: 
        [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/3_Classification_1.pdf)] 
        [[lecture note](https://github.com/wangshusen/DeepLearning/blob/master/LectureNotes/Logistic/paper/logistic.pdf)]
    
        - SVM: [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/3_Classification_2.pdf)] 
    
        - Softmax classifier: [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/3_Classification_3.pdf)] 
    
        - KNN classifier: [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/3_Classification_4.pdf)]
    
    * Regularizations. 
    [[slides-1](https://github.com/wangshusen/DeepLearning/blob/master/Slides/3_Optimization.pdf)]
    [[slides-2](https://github.com/wangshusen/DeepLearning/blob/master/Slides/3_Regularizations.pdf)]
    
    * Clustering. 
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/4_Clustering.pdf)] 
    
    * Dimensionality reduction. 
    [[slides-1](https://github.com/wangshusen/DeepLearning/blob/master/Slides/5_DR_1.pdf)] 
    [[slides-2](https://github.com/wangshusen/DeepLearning/blob/master/Slides/5_DR_2.pdf)] 
    [[lecture note](https://github.com/wangshusen/DeepLearning/blob/master/LectureNotes/SVD/svd.pdf)]
    
    * Scientific computing libraries.
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/5_DR_3.pdf)]
    
    
2. **Neural network basics.**
This part covers the multilayer perceptron, backpropagation, and deep learning libraries, with focus on Keras.

    * Multilayer perceptron and backpropagation. 
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/6_NeuralNet_1.pdf)]
    [[lecture note](https://github.com/wangshusen/DeepLearning/blob/master/LectureNotes/BP/bp.pdf)]
    
    * Keras. 
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/6_NeuralNet_2.pdf)]
    
    * Further reading:
    
        - [[activation functions](https://adl1995.github.io/an-overview-of-activation-functions-used-in-neural-networks.html)]
        
        - [[parameter initialization](https://towardsdatascience.com/weight-initialization-in-neural-networks-a-journey-from-the-basics-to-kaiming-954fb9b47c79)]
    
        - [[optimization algorithms](http://ruder.io/optimizing-gradient-descent/)]
    
    
3. **Convolutional neural networks (CNNs).**
This part is focused on CNNs and its application to computer vision problems.

    * CNN basics.
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/7_CNN_1.pdf)]
    
    * Tricks for improving test accuracy.
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/7_CNN_2.pdf)]
    
    * Feature scaling and batch normalization.
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/7_CNN_3.pdf)]
    
    * Advanced topics on CNNs. 
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/7_CNN_4.pdf)]
    
    * Popular CNN architectures.
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/7_CNN_5.pdf)]
    
    * Face recognition.
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/7_CNN_6.pdf)]
    
    * Further reading: 
    
        - [style transfer (Section 8.1, Chollet's book)]
        
        - [visualize CNN (Section 5.4, Chollet's book)]



4. **Recurrent neural networks (RNNs).**
This part introduces RNNs and its applications in natural language processing (NLP).

    * Categorical feature processing.
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/9_RNN_0.pdf)] 

    * Text processing.
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/9_RNN_1.pdf)] 
       
    * RNN basics.
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/9_RNN_2.pdf)]
       
    * LSTM.
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/9_RNN_3.pdf)]
    [[reference](http://colah.github.io/posts/2015-08-Understanding-LSTMs/)]
       
    * Making RNNs more effective.
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/9_RNN_4.pdf)]
   
    * Text generation.
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/9_RNN_5.pdf)]
    
    * Machine translation. 
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/9_RNN_6.pdf)]
    
    * Image caption generation. 
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/9_RNN_7.pdf)]
    [[reference](https://machinelearningmastery.com/develop-a-deep-learning-caption-generation-model-in-python/)]
    
    * Attention. 
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/9_RNN_8.pdf)]
    [[reference-1](https://distill.pub/2016/augmented-rnns/)]
    [[reference-2](https://lilianweng.github.io/lil-log/2018/06/24/attention-attention.html)]
    
    
5. **Language Models beyond RNNs.**

    * Transformer model: beyond RNNs. 
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/9_RNN_9.pdf)]
    [[reference](https://arxiv.org/pdf/1706.03762.pdf)]
    
    * Pre-train Transformer using BERT. [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/9_RNN_10.pdf)]
    [[reference](https://arxiv.org/pdf/1810.04805.pdf)]


6. **Autoencoders.**
This part introduces autoencoders for dimensionality reduction and image generation.

    * Autoencoder for dimensionality reduction.
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/8_AE_1.pdf)]
    
    * Variational Autoencoders (VAEs) for image generation. 
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/8_AE_2.pdf)]

    
7. **Generative Adversarial Networks (GANs).** 

    * DC-GAN [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/12_GAN.pdf)]



8. **Recommender system.** 
This part is focused on the collaborative filtering approach to recommendation based on the user-item rating data.
This part covers matrix completion methods and neural network approaches. 

    * Collaborative filtering. 
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/10_Recommender.pdf)]

    
9. **Deep Reinforcement Learning.** 

    * Reinforcement learning [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/13_RL_1.pdf)] [[lecture note](https://github.com/wangshusen/DeepLearning/blob/master/LectureNotes/DRL/DRL.pdf)] [[Video (in Chinese)](https://youtu.be/vmkRMvhCW5c)]

    * Value-based learning [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/13_RL_2.pdf)] [[Video (in Chinese)](https://youtu.be/jflq6vNcZyA)]

    * Policy-based learning [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/13_RL_3.pdf)] [[Video (in Chinese)](https://youtu.be/qI0vyfR2_Rc)]

    * Actor-critic methods [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/13_RL_4.pdf)] [[Video (in Chinese)](https://youtu.be/xjd7Jq9wPQY)]

    * AlphaGo [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/13_RL_5.pdf)] [[Video (in Chinese)](https://youtu.be/zHojAp5vkRE)]


10. **Parallel Computing.** 

	* Basics and MapReduce. 
	[[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/14_Parallel_1.pdf)] 
	[[lecture note](https://github.com/wangshusen/DeepLearning/blob/master/LectureNotes/Parallel/Parallel.pdf)] 
	[[Video (in Chinese)](https://youtu.be/gVcnOe6_c6Q)]
	
	* Parameter Server and Decentralized Network. 
	[[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/14_Parallel_2.pdf)] 
	[[Video (in Chinese)](https://youtu.be/Aga2Lxp3G7M)]
	
	* TensorFlow's Mirrored Strategy and Ring All-Reduce. 
	[[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/14_Parallel_3.pdf)] 
	[[Video (in Chinese)](https://youtu.be/rj-hjS5L8Bw)]

	
	
	* Federated Learning. 
	[[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/14_Parallel_4.pdf)] 
	[[Video (in Chinese)](https://youtu.be/STxtRucv_zo)]


11. **Adversarial Robustness.**
This part introduces how to attack neural networks using adversarial examples and how to defend from the attack.

	* Data evasion attack and defense.
    [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/11_Evasion.pdf)]
    [[lecture note](https://github.com/wangshusen/DeepLearning/blob/master/LectureNotes/Adversarial/DataAttacks.pdf)]

	* Data poisoning attack.
	 [[slides](https://github.com/wangshusen/DeepLearning/blob/master/Slides/11_Poisoning.pdf)]
	[[Video (in Chinese)](https://youtu.be/_K0nZcqdu5w)]
	 
        
    * Further reading:
    [[Adversarial Robustness - Theory and Practice](https://adversarial-ml-tutorial.org/)]
    



