# Probabilities and Deep Learning
* ### [When Probabilities meet Neural Networks (PPT) Presentation at Sinovation DeeCamp & Peking University, July 2018](https://github.com/roboticcam/machine-learning-notes/blob/master/DeeCamp2018_Xu_final.pptx) ###

Topics include: Expectation-Maximization & Matrix Capsule Networks; Determinantal Point Process & Neural Networks compression; Kalman Filter & LSTM; Model estimation & Binary classifier

* ### [Noise Contrastive Estimation, Re-parameterization, Natural Gradients](https://github.com/roboticcam/machine-learning-notes/blob/master/selected_probability.pdf) ###
Detailed illustration of Noise Contrastive Estimation (detals & derivations), Probability Density Re-parameterization, Natural Gradients 

# Video Tutorial to these notes.

* I recorded about 20% of these notes in videos in 2015 in Mandarin (all my notes and writings are in English) You may find them on [Youtube](https://www.youtube.com/channel/UConITmGn5PFr0hxTI2tWD4Q) and [哔哩哔哩](https://space.bilibili.com/327617676) and [优酷](http://i.youku.com/i/UMzIzNDgxNTg5Ng)

* I always look for high quality PhD students in Machine Learning, both in terms of probabilistic model and Deep Learning models. Contact me on YiDa.Xu@uts.edu.au


# Data Science

* ### [30 minutes introduction to AI and Machine Learning](https://github.com/roboticcam/machine-learning-notes/blob/master/30_min_AI.pptx)
An extremely gentle 30 minutes introduction to AI and Machine Learning. Thanks to my PhD student Haodong Chang for assist editing

* ### [Regression methods](https://github.com/roboticcam/machine-learning-notes/blob/master/regression.pdf) ###
Classification: Logistic and Softmax; Regression: Linear, polynomial; Mix Effect model **[[costFunction.m]](https://github.com/roboticcam/matlab_demos/blob/master/costFunction.m)** and **[[soft_max.m]](https://github.com/roboticcam/matlab_demos/blob/master/soft_max.m)**

* ### [Recommendation system](https://github.com/roboticcam/machine-learning-notes/blob/master/recommendation.pdf) ###
collaborative filtering, Factorization Machines, Non-Negative Matrix factorisation, Multiplicative Update Rule

* ### [Dimension Reduction](https://github.com/roboticcam/machine-learning-notes/blob/master/dimension_reduction.pdf) ###
classic PCA and t-SNE

* ### [Introduction to Data Analytics](https://github.com/roboticcam/machine-learning-notes/blob/master/AI_and_machine_learning.pdf) and [associate Jupyter notebook](https://github.com/roboticcam/machine-learning-notes/blob/master/industry_master_class.ipynb) ###
Three perspectives into machine learning and Data Science. Supervised vs Unsupervised Learning, Classification accuracy

# Deep Learning (jupyter style notes coming in 2018)

* ### [Optimisation methods](https://github.com/roboticcam/machine-learning-notes/blob/master/optimization.pdf) ###
Optimisation methods in general. not limited to just Deep Learning

* ### [Neural Networks](https://github.com/roboticcam/machine-learning-notes/blob/master/neural_networks.pdf) ###
basic neural networks and multilayer perceptron 

* ### [Convolution Neural Networks: from basic to recent Research](https://github.com/roboticcam/machine-learning-notes/blob/master/cnn_beyond.pdf) ###
detailed explanation of CNN, various Loss function, Centre Loss, contrastive Loss, Residual Networks, YOLO, SSD

* ### [Word Representation and approximated Softmax](https://github.com/roboticcam/machine-learning-notes/blob/master/word_vector.pdf) ###
Word2Vec, skip-gram, GloVe, Noise Contrastive Estimation, Negative sampling, Gumbel-max trick

* ### [Deep Natural Language Processing](https://github.com/roboticcam/machine-learning-notes/blob/master/deep_nlp.pdf) ###
RNN, LSTM, Seq2Seq with Attenion, Beam search, Attention is all you need, Convolution Seq2Seq, Pointer Networks

* ### [Deep Reinforcement Learning](https://github.com/roboticcam/machine-learning-notes/blob/master/dqn.pdf) ###
basic knowledge in reinforcement learning, Markov Decision Process, Bellman Equation and move onto Deep Q-Learning (under construction)

* ### [Restricted Boltzmann Machine](https://github.com/roboticcam/machine-learning-notes/blob/master/rbm_gan.pdf) ###
basic knowledge in Restricted Boltzmann Machine (RBM)


# Probability and Statistics Background

* ### [Bayesian model](https://github.com/roboticcam/machine-learning-notes/blob/master/bayesian.pdf) ###
revision on Bayes model include Bayesian predictive model, conditional expectation

* ### [Probabilistic Estimation](https://github.com/roboticcam/machine-learning-notes/blob/master/probability.pdf) ###
some useful distributions, conjugacy, MLE, MAP, Exponential family and natural parameters

* ### [Statistics Properties](https://github.com/roboticcam/machine-learning-notes/blob/master/statistics.pdf) ###
useful statistical properties to help us prove things, include Chebyshev and Markov inequality


# Probabilistic Model

* ### [Expectation Maximisation](https://github.com/roboticcam/machine-learning-notes/blob/master/em.pdf) ###
Proof of convergence for E-M, examples of E-M through Gaussian Mixture Model, **[[gmm_demo.m]](https://github.com/roboticcam/matlab_demos/blob/master/gmm_demo.m)** and **[[kmeans_demo.m]](https://github.com/roboticcam/matlab_demos/blob/master/kmeans_demo.m)** and **[[优酷链接]](http://v.youku.com/v_show/id_XMTM1MjY1MDU5Mg)**

* ### [State Space Model (Dynamic model)](https://github.com/roboticcam/machine-learning-notes/blob/master/dynamic_model.pdf) ###
explain in detail of Kalman Filter and Hidden Markov Model, **[[kalman_demo.m]](https://github.com/roboticcam/matlab_demos/blob/master/kalman_demo.m)** and **[[HMM 优酷链接]](http://v.youku.com/v_show/id_XMTM1MzQ1NDk5Ng)** and **[[Kalman Filter 优酷链接]](http://v.youku.com/v_show/id_XMTM2ODU1MzMzMg)** 


# Inference

* ### [Variational Inference](https://github.com/roboticcam/machine-learning-notes/blob/master/variational.pdf) ###
explain Variational Bayes both the non-exponential and exponential family distribution plus stochastic variational inference. **[[vb_normal_gamma.m]](https://github.com/roboticcam/matlab_demos/blob/master/vb_normal_gamma.m)** and **[[优酷链接]](http://v.youku.com/v_show/id_XMTM1Njc5NzkxNg)**


* ### [Stochastic Matrices](https://github.com/roboticcam/machine-learning-notes/blob/master/stochastic_matrices.pdf) ###
stochastic matrix, Power Method Convergence Theorem, detailed balance and PageRank algorithm


* ### [Introduction to Monte Carlo](https://github.com/roboticcam/machine-learning-notes/blob/master/introduction_monte_carlo.pdf) ###
inverse CDF, rejection, adaptive rejection, importance sampling **[[adaptive_rejection_sampling.m]](https://github.com/roboticcam/matlab_demos/blob/master/adaptive_rejection_sampling.m)** and **[[hybrid_gmm.m]](https://github.com/roboticcam/matlab_demos/blob/master/hybrid_gmm.m)**


* ### [Markov Chain Monte Carlo](https://github.com/roboticcam/machine-learning-notes/blob/master/markov_chain_monte_carlo.pdf) ###
M-H, Gibbs, Slice Sampling, Elliptical Slice sampling, Swendesen-Wang, demonstrate collapsed Gibbs using LDA **[[lda_gibbs_example.m]](https://github.com/roboticcam/matlab_demos/blob/master/lda_gibbs_example.m)** and **[[test_autocorrelation.m]](https://github.com/roboticcam/matlab_demos/blob/master/test_autocorrelation.m)** and **[[gibbs.m]](https://github.com/roboticcam/matlab_demos/blob/master/gibbs.m)** and **[[优酷链接]](http://v.youku.com/v_show/id_XMTM1NjAyNDYyNA)**

* ### [Particle Filter (Sequential Monte-Carlo)](https://github.com/roboticcam/machine-learning-notes/blob/master/particle_filter.pdf) ###
Sequential Monte-Carlo, Condensational Filter algorithm, Auxiliary Particle Filter **[[优酷链接]](http://v.youku.com/v_show/id_XMTM3MTE1Mjk2OA)**


# Advanced Probabilistic Model

* ### [Bayesian Non Parametrics (BNP) and its inference basics](https://github.com/roboticcam/machine-learning-notes/blob/master/non_parametrics.pdf) ###
Dircihlet Process (DP), Chinese Restaurant Process insights, Slice sampling for DP **[[dirichlet_process.m]](https://github.com/roboticcam/matlab_demos/blob/master/dirichlet_process.m)** and **[[优酷链接]](http://v.youku.com/v_show/id_XMTM3NDY0MDkxNg)** and **[[Jupyter Notebook]](https://github.com/roboticcam/python_machine_learning/blob/master/chinese_restaurant_process.ipynb)**

* ### [Bayesian Non Parametrics (BNP) extensions](https://github.com/roboticcam/machine-learning-notes/blob/master/non_parametrics_extensions.pdf) ###
Hierarchical DP, HDP-HMM, Indian Buffet Process (IBP)

* ### [Determinantal Point Process](https://github.com/roboticcam/machine-learning-notes/blob/master/dpp.pdf) ###
explain the details of DPP’s marginal distribution, L-ensemble, its sampling strategy, our work in time-varying DPP
