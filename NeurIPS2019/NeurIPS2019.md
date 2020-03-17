[NeurIPSLogo]: images/header-neurips2019.png
[MultipleFutures]: images/MultipleFuturesPrediction.png
[LookAhead]: images/WorldModelsWithoutLookahead.png
[Disney]: images/disney.jpg
[HALGAN]: images/HALGAN.png

# NeurIPS 2019 Report
![banner][NeurIPSLogo]

# Best Papers
## Outstanding Paper Award
Distribution-Independent PAC Learning of Halfspaces with Massart Noise  
Ilias Diakonikolas (1), Themis Gouleakis (2), Christos Tzamos (1)
1. University of Wisconsin-Madison
2. Max Planck Institute for Informatics  

[Presentation](https://slideslive.com/38923833/distributionindependent-pac-learning-of-halfspaces-with-massart-noise)  
[Paper](https://arxiv.org/pdf/1906.10075.pdf)

A "Halfspace" (also known as a Linear Threshold Function) is defined as a boolean function where its respective two classes are separated by a linear hyperplane. Furthermore, Massart noise is a form of malicious signal in the sample targets where the probability of "flipping" the sample's target is driven by a maliciously chosen probablistic parameter which makes the misclassification probability reflect an "at most" threshold.

This paper solves a formerly open problem of **_algorithmically_**, in polynomial time, which minimizes the probablity of misclassifying a sample from some distribution due to the presense of Massart noise and yields a hypothesis that bounds error to be less than the upper-bound of the Massart noise rate plus an epsilon.

## Outstanding New Directions Paper Award
Uniform Convergence may be Unable to Explain Generalization in Deep Learning  
Vaishnavh Nagarajan (1), J. Zico Kolter (1,2) 
1. CMU
2. Bosch AI  

[Presentation](https://slideslive.com/38922600/uniform-convergence-may-be-unable-to-explain-generalization-in-deep-learning)  
[Paper](https://arxiv.org/pdf/1902.04742.pdf)

This award represents a work which effectively provides a new direction for researchers to focus on. In their paper, Nagarajan and Kolter explore Uniform Convergence bounds and show that they may not universally explain generalization in deep learning. 

In their study they show that bounds actually increase with dataset size instead of decreasing. Current bound-based metrics on generalization in deep learning show a data-set size dependency and produce enough uncertainty wrt whether a model is generalizing or simply memorizing the data. They explain that research is needed into bounds which reflect the actual generalization error of the model. They then provide a formal proof showing that uniform convergence failes to explain generalization in stochastic gradient descent trained neural networks. 

# Sunday December 8: Expo
I found the NeurIPS Expo to be extremely well attended by many of the top firms in Machine Learning and AI research, such as DeepMind, OpenAI, Google AI, Amazon, Facebook AI, Apple, Microsoft, etc. 


The expo seemed to be very recruiting oriented wrt graduate students and postdocs. However, most booths were also presenting any accepted work they had at the conference.

![MultipleFutures][MultipleFutures]  
![World Models Without Lookahead][LookAhead]  

 Impressed with Disney Research  

![Disney][Disney]  

# Monday December 9

## Morning Session

Deep Learning with Bayesian Principals - [Emtiyaz Khan](https://twitter.com/emtiyazkhan?lang=en)  
[Presentation](https://slideslive.com/38923183/deep-learning-with-bayesian-principles)

Efficient Learning of Deep Neural Networks: From Algorithms to Hardware Architectures - [Vivienne Sze](https://twitter.com/eems_mit?lang=en)  
[Presentation](https://slideslive.com/38922815/efficient-processing-of-deep-neural-network-from-algorithms-to-hardware-architectures)
## Afternoon Sesssion

Reinforcement Learning: Past, Present, and Future Perspectives - [Katja Hofmann](https://twitter.com/katjahofmann)  
[Presentation](https://slideslive.com/38922817/reinforcement-learning-past-present-and-future-perspectives)

## Invited Talks

How to Know - [Celeste Kidd](https://twitter.com/celestekidd?lang=en)  
[Presentation](https://slideslive.com/38922819/how-to-know)

# Tuesday December 10

## Posters
Addressing Sample Complexity in Visual Tasks Using HER and Hallucinatory GANs  
[Paper](https://arxiv.org/abs/1901.11529)  

[![HALGAN]](https://drive.google.com/file/d/1Vf89lDBaV1tG1ZAymSb_tNAXW_34mUak/view)

# Wednesday December 11

## Invited Talks

From System 1 Deep Learning to System 2 Deep Learning - Yoshua Bengio  
[Presentation](https://slideslive.com/38922304/from-system-1-deep-learning-to-system-2-deep-learning)

# Friday December 13

## Workshops  

## [Meta-Learning](https://slideslive.com/neurips/west-ballroom-b-metalearning)  

Meta-Learning as Hierarchical Modelling - [Erin Grant](https://twitter.com/ermgrant?lang=en)    
[Presentation](https://slideslive.com/38923086/metalearning-as-hierarchical-modelling)

## [Biological and Artificial Reinforcement Learning](https://slideslive.com/neurips/west-ballroom-c-biological-and-artificial-reinforcement-learning)  
Toward a General AI-Agent Architecture - Richard Sutton  
[Presentation](https://slideslive.com/38924024/toward-a-general-aiagent-architecture)

# Saturday December 14

## Workshops

## [Deep Reinforcement Learning](https://slideslive.com/neurips/west-exhibition-hall-c-deep-reinforcement-learning)

Adversarial Policies: Attacking Deep Reinforcement Learning - [Adam Gleave](https://twitter.com/argleave)  
[Presentation](https://slideslive.com/38922702/contributed-talk-adversarial-policies-attacking-deep-reinforcement-learning)

Assessing the Robustness Deep Reinforcement Learning - [Michael Littman](https://twitter.com/mlittmancs?lang=en)  
[Presentation](https://slideslive.com/38922709/assessing-the-robustness-of-deep-rl-algorithms)

Bayes-Adaptive Deep Reinforcement Learning via Meta-Learning - [Shimon Whiteson](https://twitter.com/shimon8282?lang=en)  
[Presentation](https://slideslive.com/38922727/bayesadaptive-deep-reinforcement-learning-via-metalearning)

