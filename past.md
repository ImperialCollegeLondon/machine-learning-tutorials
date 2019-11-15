---
layout: default
---

These are the archives of past tutorials.

## Schedule 2018-2019

| Date      |  Venue  | Time | Title | Speaker
|----------:|:---------:|------|-------|-------|
| 13/03/19 |Huxley Building, LT 145 | 14:00 - 16:00 | [Neural Network Verification](http://mpawankumar.info/tutorials/vmcai2019/index.html)| [Dr. M Pawan Kumar](https://mpawankumar.info/)|
| 27/02/19 |Huxley Building, LT 145 | 14:00 - 16:00 | [Kernel methods for hypothesis testing and sample generation](https://imperiallondon-my.sharepoint.com/:b:/g/personal/vsharman_ic_ac_uk/Eah-FYTlYrJOm_xROMnBi2IBFsaMKY3QRGxMQEBRL6ScIg?e=15FSlX)| [Prof. Arthur Gretton](http://www.gatsby.ucl.ac.uk/~gretton/)|
| 28/11/18 |Huxley Building, LT 145 | 14:00 - 16:00 | [Approximate Kernel Methods, Embeddings, and Aggregates](http://www.stats.ox.ac.uk/~sejdinov/talks/pdf/2018-11-28_imperialtutorial.pdf)| [Dr. Dino Sejdinovic](http://www.stats.ox.ac.uk/~sejdinov/)|
| 07/11/18 |Huxley Building, LT 145 | 14:00 - 16:00 | [Bandit Algorithms and Reinforcement Learning](https://imperiallondon-my.sharepoint.com/:b:/g/personal/vsharman_ic_ac_uk/EXnK_RWB58tLi8VJgZvpkFMBZqLsUbqaVDxmSq9DxNplVw?e=wK9lAm)| [Dr. Tor Lattimore](https://tor-lattimore.com/)|

-----------

### Title : [Neural Network Verification](http://mpawankumar.info/tutorials/vmcai2019/index.html)

#### Speaker : [Dr. M Pawan Kumar](https://mpawankumar.info/)

Speaker's Bio : Pawan Kumar is an Associate Professor in the Department of Engineering Science at the University of Oxford, and a Tutorial Fellow at Lady Margaret Hall. Prior to joining Oxford (2012-2015), Pawan was a faculty member in the Center for Visual Computing at Ecole Centrale Paris. He spent three years (2009-2011) as a postdoc with Prof. Daphne Koller at the Computer Science Department of Stanford University. He was a Ph.D. student (2003-2007) at the Computer Vision Group in Oxford Brookes University and a postdoc (2008) at the Visual Geometry Group in the University of Oxford, where he was supervised by Prof. Philip Torr and Prof. Andrew Zisserman. As an undergraduate student (1999-2003) at the International Institute of Information Technology, Hyderabad, Pawan worked at the Center for Visual Information Technology, under the supervision of Prof. C.V. Jawahar and Prof. P.J. Narayanan. 

Abstract: In recent years, deep neural networks have been successfully employed to improve the performance of several tasks in computer vision, natural language processing and other related areas of machine learning. This has resulted in the launch of several ambitious projects where a human will be replaced by neural networks. Such projects include safety critical applications such as autonomous navigation and personalised medicine. Given the high risk of a wrong decision in such applications, a key step in the deployment of neural networks is their formal verification: proving that a neural network satisfies a desirable property, or generating a counter-example to show that it does not. This tutorial will summarise the progress made in neural network verification thus far. The contents of the tutorial are divided in three parts.

Part 1: Unsound methods, which can be used to show that some of the false properties are indeed false.

Part 2: Incomplete methods, which can be used to show that some of the true properties are indeed true.

Part 3: Complete methods, which combine unsound and incomplete methods to provide formal verification. 


-----------

### Title : Kernel methods for hypothesis testing and sample generation 

#### Speaker : [Prof. Arthur Gretton](http://www.gatsby.ucl.ac.uk/~gretton/)

Speaker's Bio : Arthur Gretton is a Professor with the Gatsby Computational Neuroscience Unit, CSML, UCL, which he joined in 2010. He received degrees in physics and systems engineering from the Australian National University, and a PhD with Microsoft Research and the Signal Processing and Communications Laboratory at the University of Cambridge. He worked from 2002-2012 at the MPI for Biological Cybernetics, and from 2009-2010 at the Machine Learning Department, Carnegie Mellon University. 

Abstract: In this tutorial, I will provide an introduction to distribution embeddings using kernels, with applications including hypothesis testing and sample generation through a Generative Adversarial Network (GAN). I'll begin with two constructions of divergences on probability distributions: as a difference in feature means, and using a class of well behaved witness functions that detects where the distributions are most different. I'll introduce the Maximum Mean Discrepancy, which can be viewed in terms of both interpretations. I'll discuss how to choose features to increase the statistical power of two-sample tests based on the MMD; I'll then describe how the MMD features can be weakened to make them more suitable for training GANs. Time permitting, I'll briefly cover additional applications, such as dependence detection and testing goodness-of-fit for statistical models.

-----------

### Title : Approximate Kernel Methods, Embeddings, and Aggregates

#### Speaker : [Dr. Dino Sejdinovic](http://www.stats.ox.ac.uk/~sejdinov/)

Speaker's Bio : Dino Sejdinovic is an Associate Professor at the Department of Statistics, University of Oxford, a Fellow of Mansfield College, Oxford, and a Turing Fellow of the Alan Turing Institute. He previously held postdoctoral positions at the Gatsby Computational Neuroscience Unit, University College London (2011-2014) and at the Institute for Statistical Science, University of Bristol (2009-2011). He received a PhD in Electrical and Electronic Engineering from the University of Bristol (2009) and a Diplom in Mathematics and Theoretical Computer Science from the University of Sarajevo (2006). 

Abstract: Kernel embeddings of distributions and the Maximum Mean Discrepancy (MMD), the resulting probability metric, are useful tools for fully nonparametric hypothesis testing, for the two-sample problem, (conditional) independence testing, and for multivariate interaction. Moreover, they also found applications in learning and predicting on distributional inputs corresponding to the situation where the access to outputs is at a much coarser (aggregate) level. I will give an overview of this framework and give some recent developments in the context of large-scale kernel approximations and weakly supervised learning on aggregates. 

-----------

### Title : Bandit Algorithms and Reinforcement Learning 

#### Speaker : [Dr. Tor Lattimore](https://tor-lattimore.com/)

Speaker's Bio : Tor Lattimore is a senior research scientist at DeepMind working on bandit algorithms, reinforcement learning and machine learning theory. He received his PhD from the Australian National University under the supervision of Marcus Hutter. Before joining DeepMind he was a postdoc at the university of Alberta and an assistant professor at Indiana University. Together with Csaba Szepesvari he recently wrote a book on bandit algorithms, which is freely availableat http://banditalgs.com.

Abstract: Decision making in the face of uncertainty is a significant challenge in machine learning. Which drugs should a patient receive? How should I allocate my study time between courses? Which version of a website will return the most revenue? What move should be considered next when playing chess/go? All of these questions can be expressed in the multi-armed bandit framework where a learning agent sequentially takes actions, observes rewards and aims to maximise the total reward over a period of time. The framework is now very popular, used in practice by big companies, and growing fast. The focus of the tutorial will be on understanding the statistical ideas, mathematics and implementation details of the core algorithmic concepts.
