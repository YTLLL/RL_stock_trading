
# Reinforcement Learning projects

To see the full code and experiment results and images please download the file: "Final_Stock_Trading_Algo.ipynb"

## Abstract 

Our primary goal is to demystify the complexities of applying deep reinforcement learning to stock market trading. We provide detailed documentation of our methodology, including the preprocessing of data, the tuning of algoritm parameters, and interpretation of results. This will empower both researchers and professionals understand how to build models for their specific requirements and drive innovation in financial technology.

## Introduction

The stock market is characterized by its high-dimensional, continuous, and dynamic nature, with data features such as Open, High, Low, Close, and Volume that evolve over time and exhibit complex non-linear interdependencies. Traditional Q-Learning struggles to handle such complexity due to its reliance on a discrete Q-table, which becomes impractically large and lacks the capacity for generalization and function approximation needed for effective decision-making in such environments. In contrast, Deep Q-Networks (DQN) leverage neural networks to approximate the Q-value function, enabling them to manage high-dimensional continuous state spaces and generalize across a wide range of market conditions. DQNs also incorporate experience replay and target networks, which enhance learning stability and efficiency, making them well-suited to adapt to the dynamic and noisy financial markets. Therefore, DQNs offer a powerful and scalable solution for developing robust trading strategies in the complex and volatile landscape of stock trading.

However, while standard DQNs provide significant improvements over traditional Q-learning, they are still susceptible to issues like overestimation of Q-values and lack of stability in volatile markets. In this context, we further discovered deep reinforcement learning techniques such as Double DQN and Dueling DQN approach to stock market prediction. These methods not only enhance the accuracy of predictions but also adapt dynamically to changing market conditions, offering significant advantages over traditional models. By enabling algorithms to learn and adapt their strategies based on dynamic market conditions, rathern than relying solely on historical data, DRL has the potential to uncover the hidden patterns and correlations in financial time series data that are often overlooked by traditional methods.

Our project aim to implement four distinct types of reinforcement learning algorithms to day trade the stock within dynamic market. We aim to explore and evaluate the performance of our models on various stock datasets including SPY and NVDA, providing a comprehensive analysis of each method's strengths and weaknesses. Through this project, we seek to provide a valuable insight into effective utilization of DRL into financial trading environment.


## Project requirements 
 
Your project should demonstrate an understanding of concepts, methods and models in the area of Reinforcement Learning and how to use/apply them using software frameworks in Python. This should involve using knowledge acquired in the course and building on this knowledge through an independent study to go more deeply into a specific subject. Your project may cover different aspects of _reinforcement learning_ methods, demonstrating an understanding of their suitability for a given class of problems, how to implement and validate them using synthetic and/or real datasets. The project can also comprise case studies involving specialised and/or complex scenarios in which you can experiment with different actions, states, rewards and policies. You may consider establishing some theoretical properties regarding RL methods or proposing your own methods. Development of the new theories and methodologies are **not** necessary, but you will get a high mark if these developments contain enough novelty.
 
Your **report would typically be in the form of a Jupyter notebook**, containing code, **along with a Markdown text** explaining different parts. You may want to provide a tutorial-like exposition for certain subjects covered in your project. For example, this may include instructions for loading specific libraries and/or packages you have used, preprocessing tasks you have applied to your datasets and specific requirements for running your models. **Your report and any other project related material should be submitted in the GitHub classroom repo** that will be assigned to your project.
 
It is expected from **your report to be** presented up to a high professional standard. This means that it has to be **structured well**, neat and polished. 
Your report should have a title, abstract, main content body, conclusion, and a list of references. 
In the abstract, please make sure to briefly describe what is the problem addressed by your project, why is the problem a problem, 
what is your solution and why you have chosen given solution. The abstract should be short, a paragraph of 5-10 sentences. 

You may use **visualizations** in your report, for example using Matplotlib, Tensorboard and other Python libraries. 

Your **report may describe a working prototype application**. In this case, your report should contain a clear and full description of the steps that one needs to follow in order to run your application. 

Your **report should cite any references that you use** (including the reference for the code). You may also discuss and cite any previously proposed alternative solutions to your problem. The conclusion section should briefly summarise the results of your project, highlight your main findings, and briefly discuss any interesting avenues for future research.

You are allowed to discuss your project topic with Chengchun. The list of candidate projects is given below to give you some idea about potential project topics. **You may (but you are not expected) to take one of the project topics listed below**. 

## Candidate project topics

Here you'll find references to various resources such as research papers and blogs that may inspire your choice of the course project. You may also check references provided in the lecture materials.

You're welcome to propose a topic that is not included in the list below.

#### Causal Reinforcement Learning
* Li et al., [Causal Reinforcement Learning: An Instrumental Variable Approach](https://arxiv.org/abs/2103.04021)
* Shi et al., [A Minimax Learning Approach to Off-Policy Evaluation in Confounded Partially Observable Markov Decision Processes](https://arxiv.org/abs/2111.06784)
* Tennenholtz et al., [Off-Policy Evaluation in Partially Observable Environments](https://arxiv.org/pdf/1909.03739.pdf)
* Xu et al., [An Instrumental Variable Approach to
Confounded Off-Policy Evaluation](https://arxiv.org/pdf/2212.14468.pdf)
* Zhang et al., [Markov Decision Processes with Unobserved
Confounders: A Causal Approach](https://www.cs.purdue.edu/homes/eb/mdp-causal.pdf)

#### Games
* Atari [zoo](https://eng.uber.com/atari-zoo-deep-reinforcement-learning/)
* [Model based reinforcement learning for Atari](https://arxiv.org/pdf/1903.00374.pdf) 

#### Optimization

* Zhu et al, [Causal Discovery with Reinforcement Learning](https://arxiv.org/pdf/1906.04477.pdf)
* [TraceIn](https://ai.googleblog.com/2021/02/tracin-simple-method-to-estimate.html#:~:text=TracIn%20is%20a%20simple%2C%20easy,github%20linked%20in%20the%20paper.) A Simple Method to Estimate the Training Data Influence 
* Microsoft [MARO (Multi-Agent Resource Optimization)](https://github.com/microsoft/maro) 
* Kool et al, [Attention, Learn to Solve Routing Problems!](https://openreview.net/forum?id=ByxBFsRqYm) 
* Mao et al, [Resource management with deep reinforcement learning](https://people.csail.mit.edu/alizadeh/papers/deeprm-hotnets16.pdf), Hotnets 2016
* Mirhoseini et al, [Device placement optimization with reinforcement learning](https://arxiv.org/abs/1706.04972), ICML 2017
* Mirhoseini et al, [A hierarhical model for device placement](https://openreview.net/pdf?id=Hkc-TeZ0W), ICLR 2018
* Bello et al, [Neural combinatorial optimization with reinforcement learning](https://arxiv.org/pdf/1611.09940.pdf), ICLR 2017

#### Medical application

* Gao et al., [Offline Learning of Closed-Loop Deep Brain Stimulation
Controllers for Parkinson Disease Treatment](https://arxiv.org/pdf/2302.02477.pdf)
* Komorowski et al., [The Artificial Intelligence Clinician learns optimal treatment strategies for sepsis in intensive care](https://www.nature.com/articles/s41591-018-0213-5)
* Li et al., [Testing Stationarity and Change Point Detection in Reinforcement Learning
](https://arxiv.org/abs/2203.01707)
* Luckett et al., [Estimating Dynamic Treatment Regimes in Mobile Health Using V-Learning](https://www.tandfonline.com/doi/abs/10.1080/01621459.2018.1537919)
* Shi et al., [Does the Markov Decision Process Fit the Data:
Testing for the Markov Property in Sequential Decision Making](http://proceedings.mlr.press/v119/shi20c/shi20c.pdf)
* Zhou et al., [Estimating Optimal Infinite Horizon Dynamic
Treatment Regimes via pT-Learning](https://arxiv.org/pdf/2110.10719.pdf)

#### Ridesharing

* Xu et al., [large scale fleet management a planning and learning approach](https://users.wpi.edu/~yli15/courses/DS504Fall18/includes/p1774-lin.pdf)
* Shi et al., [Off-Policy Confidence Interval Estimation
with Confounded Markov Decision Process](https://arxiv.org/pdf/2202.10589.pdf)
* Shi et al., [Dynamic Causal Effects Evaluation in A/B Testing with a Reinforcement Learning Framework](https://www.tandfonline.com/doi/full/10.1080/01621459.2022.2027776)
* Tang et al., [A Deep Value-network Based Approach for Multi-Driver Order
Dispatching](https://arxiv.org/pdf/2106.04493.pdf)
* Wan et al., [Pattern Transfer Learning for Reinforcement Learning in Order Dispatching](https://arxiv.org/pdf/2105.13218.pdf)

#### Protein structure prediction

* Senior et al, [AlphaFold: Improved protein structure prediction using potentials from deep learning](https://deepmind.com/research/publications/AlphaFold-Improved-protein-structure-prediction-using-potentials-from-deep-learning)

#### Finance

* Deng et al, [Deep direct reinforcement learning for financial
signal representation and trading](http://www.cslt.org/mediawiki/images/a/aa/07407387.pdf), IEEE Trans. on Neural Networks and Learning Systems, 2016

### Some past project topics

* Creating a conversational ChatBot using deep Q-network
* Fairness or efficiency: strategy analysis for coronavirus medical treatment using RL
* Financial portfolio management using deep RL
* Deep direct recurrent reinforcement learning for algorithmic trading
* Reinforcement learning for trade execution with Alpha and risk aversion
* Solving ATT48 by deep reinforcement learning
* Stock trading by deep reinforcement learning
