---
title:  "Learning and Optimization"
layout: multitrack
organizer_url: 
categories:
- dali2016
organizers:
- given: Stefanie
  family: Jegelka
  url: "http://people.csail.mit.edu/stefje/"
  institute: Massachusetts Institute of Technology
- given: Guillaume
  family: Obozinski
  url: "http://imagine.enpc.fr/~obozinsg/"
  institute: Ecole des Ponts - ParisTech
show_abstracts: true
room: "Sala Ginestra"
talks:
- title: "Primal-Dual Rates and Certificates"
  author: 
  - given: Martin 
    family: Jaggi
  start: "09:30"
  end: "10:05"
  abstract: "We propose an algorithm-independent framework to equip existing optimization methods with primal-dual certificates. Such certificates and corresponding rate of convergence guarantees are important for practitioners to diagnose progress, in particular in machine learning applications. We obtain new primal-dual convergence rates e.g. for the Lasso as well as many L1, Elastic-Net and group-lasso-regularized problems. The theory applies to any norm-regularized generalized linear model. Our approach provides efficiently computable duality gaps which are globally defined, without modifying the original problems in the region of interest."
- title: "Generalization properties of multiple passes stochastic gradient method"
  author: 
  - given: Silvia 
    family: Villa
  start: "10:05"
  end: "10:40"
  abstract: "The stochastic gradient method has become an algorithm of choice in machine learning, because of  its simplicity and small computational cost, especially when dealing with big data sets. Despite   its widespread use, the  generalization properties of the variants of stochastic gradient method used in practice are relatively little understood.  Most previous works consider generalization properties of SGM with only one pass over the data, while in practice  multiple passes are usually considered. The effect of multiple passes has  been studied extensively for the optimization  of an empirical objective, but the role for generalization is less clear. In this talk, we start filling this gap studying the generalization properties of multiple passes stochastic gradient method for least square regression in an abstract non parametric setting. We show that,  if all other parameters are fixed a priori, the number of passes over the data indeed acts as a regularization parameter. The obtained bounds are sharp  and matches those obtained with other regularized techniques such as ridge regression."
- title: "Minimizing the Maximal Loss: Why and How ?"
  author: 
  - given: Shai 
    family: Shalev-Shwartz
  start: "10:40"
  end: "11:15"
  abstract: "We argue that in some situations, minimizing the maximal loss over the training set is essential for achieving good performance on unseen examples. We present a stochastic algorithm for solving the resulted optimization problem."
- title: ""
  start: "Coffee Break"
- title: "Variational Inference in Probabilistic Submodular Models"
  author: 
  - given: Andreas 
    family: Krause
  start: "11:45"
  end: "12:20"
  abstract: "As a discrete analogue of convexity, submodularity has profound implications for optimization. In recent years, submodular optimization has found many new applications, such as in machine learning and related fields. In this talk, I will present our recent work on quantifying uncertainty in submodular optimization. In particular, we carry out the first systematic investigation of inference and learning in probabilistic submodular models (PSMs). These are probabilistic models defined through submodular functions -- log-sub/supermodular distributions -- generalizing regular binary Markov Random Fields and Determinantal Point Processes. They express natural notions such as attractiveness and repulsion and allow to capture long-range, high-order dependencies among the variables.  I will present our recently discovered variational approach towards inference in general PSMs based on sub- and supergradients. We obtain both lower and upper bounds on the log-partition function, which enables computing probability intervals for marginals,
conditionals and marginal likelihoods. We also obtain fully factorized approximate posteriors, at essentially the same computational cost as ordinary submodular optimization. Our framework results in convex problems for optimizing over differentials of submodular functions, which we show how to optimally solve. Our approximation is exact at the mode (for log-supermodular distributions), and we provide bounds on the approximation quality of the log-partition function with respect to the curvature of the function. We further establish natural relations between our variational approach and the classical mean-field method from statistical physics. Exploiting additive structure in the objective leads to highly scalable, parallelizable message passing algorithms. We empirically demonstrate the accuracy of our inference scheme on several PSMs arising in computer vision and network analysis."
- title: "On the Global Linear Convergence of Frank-Wolfe Optimization Variants"
  author: 
  - given: Simon 
    family: Lacoste-Julien
  start: "12:20"
  end: "12:55"
  abstract: "The Frank-Wolfe (FW) optimization algorithm has lately re-gained popularity thanks in particular to its ability to nicely handle the structured constraints appearing in machine learning applications. However, its convergence rate is known to be slow (sublinear) when the solution lies at the boundary. In this talk, I will present some less well-known variants of the FW algorithm for which we proved their global linear convergence rate recently for the first time, highlighting at the same time an interesting geometric notion of 'condition number' for the constraint set appearing in the constant."
- title: ""
  start: "Lunch and Afternoon Activities"
- title: "Submodular Functions: from Discrete to Continous Domains"
  author: 
  - given: Francis 
    family: Bach
  start: "18:00"
  end: "18:35"
  abstract: "Submodular set-functions have many applications in combinatorial optimization, as they can be minimized and approximately maximized in polynomial time. A key element in many of the algorithms and analyses is the possibility of extending the submodular set-function to a convex function, which opens up tools from convex optimization. Submodularity goes beyond set-functions and has naturally been considered for problems with multiple labels or for functions defined on continuous domains, where it corresponds essentially to cross second-derivatives being nonpositive. In this paper, we show that most results relating submodularity and convexity for set-functions can be extended to all submodular functions. In particular, (a) we naturally define a continuous extension in a set of probability measures, (b) show that the extension is convex if and only if the original function is submodular, (c) prove that the problem of minimizing a submodular function is equivalent to a typically non-smooth convex optimization problem, and (d) propose another convex optimization problem with better computational properties (e.g., a smooth dual problem). Most of these extensions from the set-function situation are obtained by drawing links with the theory of multi-marginal optimal transport, which provides also a new interpretation of existing results for set-functions. We then provide practical algorithms to minimize generic submodular functions on discrete domains, with associated convergence rates. (available at https://hal.archives-ouvertes.fr/hal-01222319v2/document)"
- title: "MetaGrad: Faster Convergence Without Curvature in Online Convex Optimization"
  author: 
  - given: Wouter M. 
    family: Koolen
  start: "18:35"
  end: "19:10"
  abstract: "Online convex optimization is a machine learning paradigm that is popular in learning from large data sets. We develop a new style of algorithms for online convex optimization that adapt to the complexity of the functions encountered by learning the learning rate. As a result, we get refined guarantees that express that we improve the sqrt(T) worst-case regret bound whenever the sought optimum is stable. It is well-known that reduced regret is possible with functions that exhibit curvature. Yet our stability is a much weaker requirement; it includes many cases without any curvature. For example any single fixed function, or functions generated by stochastic sources that satisfy a natural condition. Our new algorithms enjoy the efficiency of online gradient descent and AdaGrad. We expect the new adaptivity to be especially useful in practice."
- title: "Less is more: optimal learning with stochastic projection regularization"
  author: 
  - given: Lorenzo 
    family: Rosasco
  start: "19:10"
  end: "19:45"
  abstract: "In this talk, we will discuss the generalization properies of commonly used techniques to scale up kernel methods and Gaussian processes. In particular, we will focus on data dependent and independent sub-sampling methods, namely Nystrom and random features, and study their generalization properties within a statistical learning theory framework. On the one hand we show that these methods can achieve optimal learning errors while being computational efficient. On the other hand, we show that subsampling can be seen as a form of stochastic projection regularization, rather than only a way to speed up computations."
- title: ""
  start: "Dinner"
speakers:
- Francis Bach
- Martin Jaggi
- Wouter M. Koolen
- Andreas Krause
- Simon Lacoste-Julien
- Lorenzo Rosasco
- Shai Shalev-Shwartz
- Silvia Villa
---
