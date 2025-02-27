# Awesome-AutoML-Papers

A curated list of automated machine learning papers, articles, tutorials, slides and projects.

# Introduction to AutoML
Machine learning (ML) has achieved considerable successes in recent years and an ever-growing number of disciplines rely on it. However, this success crucially relies on human machine learning experts to perform the following tasks:
+ Preprocess the data
+ Select appropriate features
+ Select an appropriate model family
+ Optimize model hyperparameters
+ Postprocess machine learning models
+ Critically analyze the results obtained.

As the complexity of these tasks is often beyond non-ML-experts, the rapid growth of machine learning applications has created a demand for off-the-shelf machine learning methods that can be used easily and without expert knowledge. We call the resulting research area that targets progressive automation of machine learning *AutoML*.

AutoML draws on many disciplines of machine learning, prominently including
+ Bayesian optimization
+ Regression models for structured data and big data
+ Meta learning
+ Transfer learning, and
+ Combinatorial optimization.

# Table of Contents

+ [Papers](#papers)
  - [Automated Feature Engineering](#automated-feature-engineering)
    - [Expand Reduce](#expand-reduce)
    - [Hierarchical Organization of Transformations](#hierarchical-organization-of-transformations)
    - [Meta Learning](#meta-learning)
    - [Reinforcement Learning](#reinforcement-learning)
  - [Architecture Search](#architecture-search)
    - [Evolutionary Algorithms](#evolutionary-algorithms)
    - [Local Search](#local-search)
    - [Meta Learning](#meta-learning)
    - [Reinforcement Learning](#reinforcement-learning)
    - [Transfer Learning](#transfer-learning)
  - [Hyperparameter Optimization](#hyperparameter-optimization)
    - [Bayesian Optimization](#bayesian-optimization)
    - [Evolutionary Algorithms](#evolutionary-algorithms)
    - [Lipschitz Functions](#lipschitz-functions)
    - [Local Search](#local-search)
    - [Meta Learning](#meta-learning)
    - [Particle Swarm Optimization](#particle-swarm-optimization)
    - [Random Search](#random-search)
    - [Transfer Learning](#transfer-learning)
  - [Performance Prediction](#performance-prediction)
    - [Performance Prediction](##)
  - [Frameworks](#frameworks)
  - [Miscellaneous](#miscellaneous)
+ [Tutorials](#tutorials)
  - [Bayesian Optimization](#bayesian-optimization)
  - [Meta Learning](#meta-learning)
+ [Articles](#articles)
  - [Bayesian Optimization](#bayesian-optimization)
  - [Meta Learning](#meta-learning)
+ [Slides](#slides)
  - [Bayesian Optimization](#bayesian-optimization)
+ [Books](#books)
  - [Meta Learning](#meta-learning)
+ [Projects](#projects)
+ [Prominent Researchers](#prominent-researchers)

# Papers
### Automated Feature Engineering
+ #### Expand Reduce
  - 2017 | AutoLearn — Automated Feature Generation and Selection | Ambika Kaul, et al. | ICDM | [`PDF`](https://ieeexplore.ieee.org/document/8215494/)
  - 2017 | One button machine for automating feature engineering in relational databases | Hoang Thanh Lam, et al. | arXiv | [`PDF`](https://arxiv.org/pdf/1706.00327.pdf)
  - 2016 | Automating Feature Engineering | Udayan Khurana, et al. | NIPS | [`PDF`](http://workshops.inf.ed.ac.uk/nips2016-ai4datasci/papers/NIPS2016-AI4DataSci_paper_13.pdf)
  - 2016 | ExploreKit: Automatic Feature Generation and Selection | Gilad Katz, et al. | ICDM | [`PDF`](http://ieeexplore.ieee.org/document/7837936/)
  - 2015 | Deep Feature Synthesis: Towards Automating Data Science Endeavors | James Max Kanter, Kalyan Veeramachaneni | DSAA | [`PDF`](http://www.jmaxkanter.com/static/papers/DSAA_DSM_2015.pdf)
+ #### Hierarchical Organization of Transformations
  - 2016 | Cognito: Automated Feature Engineering for Supervised Learning | Udayan Khurana, et al. | ICDMW | [`PDF`](http://ieeexplore.ieee.org/document/7836821/)
+ #### Meta Learning
  - 2017 | Learning Feature Engineering for Classification | Fatemeh Nargesian, et al. | IJCAI | [`PDF`](https://www.ijcai.org/proceedings/2017/0352.pdf)
+ #### Reinforcement Learning
  - 2017 | Feature Engineering for Predictive Modeling using Reinforcement Learning | Udayan Khurana, et al. | arXiv | [`PDF`](https://arxiv.org/pdf/1709.07150.pdf)
  - 2010 | Feature Selection as a One-Player Game | Romaric Gaudel, Michele Sebag | ICML | [`PDF`](https://hal.archives-ouvertes.fr/inria-00484049/document)
### Architecture Search
+ #### Evolutionary Algorithms
  - 2017 | Large-Scale Evolution of Image Classifiers | Esteban Real, et al. | PMLR | [`PDF`](https://arxiv.org/abs/1703.01041)
  - 2002 | Evolving Neural Networks through Augmenting Topologies | Kenneth O.Stanley, Risto Miikkulainen | Evolutionary Computation | [`PDF`](http://nn.cs.utexas.edu/downloads/papers/stanley.ec02.pdf)
+ #### Local Search
  - 2017 | Simple and Efficient Architecture Search for Convolutional Neural Networks | Thomoas Elsken, et al. | ICLR | [`PDF`](https://arxiv.org/pdf/1711.04528.pdf)
+ #### Meta Learning
  - 2016 | Learning to Optimize | Ke Li, Jitendra Malik | arXiv | [`PDF`](https://arxiv.org/pdf/1606.01885.pdf)
+ #### Reinforcement Learning
  - 2018 | Efficient Neural Architecture Search via Parameter Sharing | Hieu Pham, et al. | arXiv | [`PDF`](https://arxiv.org/abs/1802.03268)
  - 2017 | Neural Architecture Search with Reinforcement Learning | Barret Zoph, Quoc V. Le | ICLR | [`PDF`](https://arxiv.org/pdf/1611.01578.pdf)
+ #### Transfer Learning
  - 2017 | Learning Transferable Architectures for Scalable Image Recognition | Barret Zoph, et al. | arXiv | [`PDF`](https://arxiv.org/abs/1707.07012)
+ #### Network Morphism
  - 2018 | Efficient Neural Architecture Search with Network Morphism | Haifeng Jin, et al. | arXiv | [`PDF`](https://arxiv.org/abs/1806.10282)
+ #### Gradient Base
  - 2018 | Darts: Differentiable architecture search | Hanxiao Liu, et al. | arXiv | [`PDF`](https://arxiv.org/pdf/1806.09055.pdf)
### Frameworks
+ 2017 | Google Vizier: A Service for Black-Box Optimization | Daniel Golovin, et al. | KDD |[`PDF`](https://static.googleusercontent.com/media/research.google.com/zh-CN//pubs/archive/46180.pdf)
+ 2017 | ATM: A Distributed, Collaborative, Scalable System for Automated Machine Learning | T. Swearingen, et al. | IEEE | [`PDF`](https://cyphe.rs/static/atm.pdf)
+ 2015 | AutoCompete: A Framework for Machine Learning Competitions | Abhishek Thakur, et al. | ICML | [`PDF`](https://arxiv.org/pdf/1507.02188.pdf)
### Hyperparameter Optimization
+ #### Bayesian Optimization
  - 2018 | High-Dimensional Bayesian Optimization via Additive Models with Overlapping Groups. |  PMLR | [`PDF`](https://arxiv.org/pdf/1802.07028v2.pdf)
  - 2018 | A Tutorial on Bayesian Optimization. | [`PDF`](https://arxiv.org/pdf/1807.02811.pdf)
  - 2016 | Bayesian Optimization with Robust Bayesian Neural Networks | Jost Tobias Springenberg， et al. | NIPS | [`PDF`](https://papers.nips.cc/paper/6117-bayesian-optimization-with-robust-bayesian-neural-networks.pdf)
  - 2016 | Scalable Hyperparameter Optimization with Products of Gaussian Process Experts | Nicolas Schilling, et al. | PKDD | [`PDF`](https://link.springer.com/chapter/10.1007/978-3-319-46128-1_3)
  - 2016 | Taking the Human Out of the Loop: A Review of Bayesian Optimization | Bobak Shahriari, et al. | IEEE | [`PDF`](http://ieeexplore.ieee.org/document/7352306/)
  - 2016 | Towards Automatically-Tuned Neural Networks | Hector Mendoza, et al. | JMLR | [`PDF`](http://aad.informatik.uni-freiburg.de/papers/16-AUTOML-AutoNet.pdf)
  - 2016 | Two-Stage Transfer Surrogate Model for Automatic Hyperparameter Optimization | Martin Wistuba, et al. | PKDD | [`PDF`](https://link.springer.com/chapter/10.1007/978-3-319-46128-1_13)
  - 2015 | Efficient and Robust Automated Machine Learning | [`PDF`](https://papers.nips.cc/paper/5872-efficient-and-robust-automated-machine-learning.pdf)
  - 2015 | Hyperparameter Optimization with Factorized Multilayer Perceptrons | Nicolas Schilling, et al. | PKDD | [`PDF`](https://link.springer.com/chapter/10.1007/978-3-319-23525-7_6)
  - 2015 | Hyperparameter Search Space Pruning - A New Component for Sequential Model-Based Hyperparameter Optimization | Martin Wistua, et al. | [`PDF`](https://dl.acm.org/citation.cfm?id=2991491)
  - 2015 | Joint Model Choice and Hyperparameter Optimization with Factorized Multilayer Perceptrons | Nicolas Schilling, et al. | ICTAI | [`PDF`](http://ieeexplore.ieee.org/abstract/document/7372120/)
  - 2015 | Learning Hyperparameter Optimization Initializations | Martin Wistuba, et al. | DSAA | [`PDF`](http://ieeexplore.ieee.org/abstract/document/7344817/)
  - 2015 | Scalable Bayesian optimization using deep neural networks | Jasper Snoek, et al. | ACM | [`PDF`](https://dl.acm.org/citation.cfm?id=3045349)
  - 2015 | Sequential Model-free Hyperparameter Tuning | Martin Wistuba, et al. | ICDM | [`PDF`](http://ieeexplore.ieee.org/abstract/document/7373431/)
  - 2013 | Auto-WEKA: Combined Selection and Hyperparameter Optimization of Classification Algorithms | [`PDF`](http://www.cs.ubc.ca/labs/beta/Projects/autoweka/papers/autoweka.pdf)
  - 2013 | Making a Science of Model Search: Hyperparameter Optimization in Hundreds of Dimensions for Vision Architectures | J. Bergstra | JMLR | [`PDF`](http://proceedings.mlr.press/v28/bergstra13.pdf)
  - 2012 | Practical Bayesian Optimization of Machine Learning Algorithms | [`PDF`](https://papers.nips.cc/paper/4522-practical-bayesian-optimization-of-machine-learning-algorithms.pdf)
  - 2011 | Sequential Model-Based Optimization for General Algorithm Configuration(extended version) | [`PDF`](https://www.cs.ubc.ca/~hutter/papers/10-TR-SMAC.pdf)
+ #### Evolutionary Algorithms
  - 2018 | Autostacker: A Compositional Evolutionary Learning System | Boyuan Chen, et al. | arXiv | [`PDF`](https://arxiv.org/pdf/1803.00684.pdf)
  - 2017 | Large-Scale Evolution of Image Classifiers | Esteban Real, et al. | PMLR | [`PDF`](https://arxiv.org/pdf/1703.01041.pdf)
  - 2016 | Evaluation of a tree-based pipeline optimization tool for automating data science | Randal S. Olson, et al. | GECCO | [`PDF`](https://dl.acm.org/citation.cfm?id=2908918)
  - 2016 | Automating biomedical data science through tree-based pipeline optimization | Randal S. Olson, et al. | ECAL | [`PDF`](https://arxiv.org/pdf/1601.07925.pdf)
+ ####  Lipschitz Functions
  - 2017 | Global Optimization of Lipschitz functions | C´edric Malherbe, Nicolas Vayatis | arXiv | [`PDF`](https://arxiv.org/pdf/1703.02628.pdf)
+ #### Local Search
  - 2009 | ParamILS: An Automatic Algorithm Configuration Framework | Frank Hutter, et al. | JAIR | [`PDF`](https://arxiv.org/pdf/1401.3492.pdf)
+ #### Meta Learning
  - 2008 | Cross-Disciplinary Perspectives on Meta-Learning for Algorithm Selection | [`PDF`](https://dl.acm.org/citation.cfm?id=1456656)
+ #### Particle Swarm Optimization
  - 2017 | Particle Swarm Optimization for Hyper-parameter Selection in Deep Neural Networks | Pablo Ribalta Lorenzo, et al. | GECCO | [`PDF`](https://dl.acm.org/citation.cfm?id=3071208)
  - 2008 | Particle Swarm Optimization for Parameter Determination and Feature Selection of Support Vector Machines | Shih-Wei Lin, et al. | Expert Systems with Applications | [`PDF`](http://www.sciencedirect.com/science/article/pii/S0957417407003752)
+ #### Random Search
  - 2016 | Hyperband: A Novel Bandit-Based Approach to Hyperparameter Optimization | Lisha Li, et al. | arXiv |  [`PDF`](https://arxiv.org/pdf/1603.06560.pdf)
  - 2012 | Random Search for Hyper-Parameter Optimization | James Bergstra, Yoshua Bengio | JMLR | [`PDF`](http://www.jmlr.org/papers/volume13/bergstra12a/bergstra12a.pdf)
  - 2011 | Algorithms for Hyper-parameter Optimization | James Bergstra, et al. | NIPS | [`PDF`](https://dl.acm.org/citation.cfm?id=2986743)
+ #### Transfer Learning
  - 2016 | Efficient Transfer Learning Method for Automatic Hyperparameter Tuning | Dani Yogatama, Gideon Mann | JMLR | [`PDF`](https://pdfs.semanticscholar.org/75f2/6734972ebaffc6b43d45abd3048ef75f15a5.pdf)
  - 2016 | Flexible Transfer Learning Framework for Bayesian Optimisation | Tinu Theckel Joy, et al. | PAKDD | [`PDF`](https://link.springer.com/chapter/10.1007/978-3-319-31753-3_9)
  - 2016 | Hyperparameter Optimization Machines | Martin Wistuba, et al. | DSAA | [`PDF`](http://ieeexplore.ieee.org/abstract/document/7796889/)
  - 2013 | Collaborative Hyperparameter Tuning | R´emi Bardenet, et al. | ICML | [`PDF`](http://proceedings.mlr.press/v28/bardenet13.pdf)
### Miscellaneous
- 2018 | Accelerating Neural Architecture Search using Performance Prediction | Bowen Baker, et al. | ICLR | [`PDF`](https://openreview.net/pdf?id=BJypUGZ0Z)
- 2017 | Automatic Frankensteining: Creating Complex Ensembles Autonomously | Martin Wistuba, et al. | SIAM | [`PDF`](http://epubs.siam.org/doi/pdf/10.1137/1.9781611974973.83)

# Tutorials
### Bayesian Optimization
+ 2010 | A Tutorial on Bayesian Optimization of Expensive Cost Functions, with Application to Active User Modeling and Hierarchical Reinforcement Learning | [`PDF`](https://arxiv.org/pdf/1012.2599v1.pdf)
### Meta Learning
+ 2008 | Metalearning - A Tutorial | [`PDF`](https://pdfs.semanticscholar.org/5794/1a4891f673cadf06fba02419372aad85c3bb.pdf)

# Articles
### Bayesian Optimization
+ 2016 | Bayesian Optimization for Hyperparameter Tuning | [`Link`](https://arimo.com/data-science/2016/bayesian-optimization-hyperparameter-tuning/)
### Meta Learning
+ 2017 | Why Meta-learning is Crucial for Further Advances of Artificial Intelligence? | [`Link`](https://chatbotslife.com/why-meta-learning-is-crucial-for-further-advances-of-artificial-intelligence-c2df55959adf)
+ 2017 | Learning to learn | [`Link`](http://bair.berkeley.edu/blog/2017/07/18/learning-to-learn/)

# Slides
### Automated Feature Engineering
+ Automated Feature Engineering for Predictive Modeling | Udyan Khurana, etc al. | [`PDF`](https://github.com/hibayesian/awesome-automl-papers/blob/master/resources/slides/%5Bslides%5D-automated-feature-engineering-for-predictive-modeling.pdf)
### Hyperparameter Optimization
#### Bayesian Optimization
+ Bayesian Optimisation | [`PDF`](https://github.com/hibayesian/awesome-automl-papers/blob/master/resources/slides/%5Bslides%5D-bayesian-optimisation.pdf)
+ A Tutorial on Bayesian Optimization for Machine Learning | [`PDF`](https://github.com/hibayesian/awesome-automl-papers/blob/master/resources/slides/%5Bslides%5D-a-tutorial-on-bayesian-optimization-for-machine-learning.pdf)

# Books
### Meta Learning
+ 2009 | Metalearning - Applications to Data Mining | Springer | [`PDF`](http://www.springer.com/la/book/9783540732624)

# Projects
+ Advisor | `Python` | `Open Source` | [`Code`](https://github.com/tobegit3hub/advisor)
+ Auger | `Python` | `Commercial` | [`Link`](https://auger.ai)
+ auto-sklearn | `Python` | `Open Source` | [`Code`](https://github.com/automl/auto-sklearn)
+ Auto-Keras | `Python` | `Open Source` | [`Code`](https://github.com/jhfjhfj1/autokeras)
+ Auto-WEKA | `Java` | `Open Source` | [`Code`](https://github.com/automl/autoweka)
+ Hyperopt | `Python` | `Open Source` | [`Code`](https://github.com/hyperopt/hyperopt)
+ Hyperopt-sklearn | `Python` | `Open Source` | [`Code`](https://github.com/hyperopt/hyperopt-sklearn)
+ SigOpt | `Python` | `Commercial` | [`Link`](https://sigopt.com/)
+ SMAC3 | `Python` | `Open Source` | [`Code`](https://github.com/automl/SMAC3)
+ RoBO | `Python` | `Open Source` | [`Code`](https://github.com/automl/RoBO)
+ BayesianOptimization | `Python` | `Open Source` | [`Code`](https://github.com/fmfn/BayesianOptimization)
+ Scikit-Optimize | `Python` | `Open Source` | [`Code`](https://github.com/scikit-optimize/scikit-optimize)
+ HyperBand | `Python` | `Open Source` | [`Code`](https://github.com/zygmuntz/hyperband)
+ BayesOpt | `C++` | `Open Source` | [`Code`](https://github.com/rmcantin/bayesopt)
+ Optunity | `Python` | `Open Source` | [`Code`](https://github.com/claesenm/optunity)
+ TPOT | `Python` | `Open Source` | [`Code`](https://github.com/rhiever/tpot)
+ ATM | `Python` | `Open Source` | [`Code`](https://github.com/HDI-Project/ATM)
+ Cloud AutoML | `Python` | `Commercial`| [`Link`](https://cloud.google.com/automl/)
+ H2O | `Python` | `Commercial` | [`Link`](https://www.h2o.ai/)
+ DataRobot | `Python` | `Commercial` | [`Link`](https://www.datarobot.com/)
+ MLJAR | `Python` | `Commercial` | [`Link`](https://mljar.com/)
+ MateLabs | `Python` | `Commercial` | [`Link`](http://matelabs.in/)
+ FAR-HO | `Python` | `Open Source` | [`Code`](https://github.com/lucfra/FAR-HO)
+ TransmogrifAI | `Scala` | `Open Source` | [`Code`](https://github.com/salesforce/TransmogrifAI)
+ DEvol | `Python` | `Open Source` | [`Code`](https://github.com/joeddav/devol)
+ HyperparameterHunter | `Python` | `Open Source` | [`Code`](https://github.com/HunterMcGushion/hyperparameter_hunter)
+ NNI | `Python & Typescript` | `Open Source` | [`Code`](https://github.com/Microsoft/nni)

# Prominent Researchers
+ [Frank Hutter](http://aad.informatik.uni-freiburg.de/people/hutter/index.html) | University of Freiburg
+ [Martin Wistuba](https://researcher.watson.ibm.com/researcher/view.php?person=ibm-Martin.Wistuba) | IBM Research

# Acknowledgement
Special thanks to everyone who contributed to this project.
+ [endymecy](https://github.com/endymecy)
+ [tengben0905](https://github.com/tengben0905)
+ [Saket Maheshwary](https://github.com/sakimahesh)
+ [derekflint](https://github.com/derekflint)
+ [Randy Olson](https://github.com/rhiever)
+ [sophia-wright-blue](https://github.com/sophia-wright-blue)
+ [xuehui](https://github.com/xuehui1991)
+ [shaido987](https://github.com/shaido987)

# Licenses
Awesome-AutoML-Papers is available under Apache Licenses 2.0.

# Contact & Feedback
If you have any suggestions (missing papers, new papers, key researchers or typos), feel free to pull a request. Also you can mail to:
+ hibayesian (hibayesian@gmail.com).
