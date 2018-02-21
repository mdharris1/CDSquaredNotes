My approach for learning Data Science will be modeled after the simplied question and answer method used by A.A. Klaf in a dover series of mathematics book. 

1. [Data Science Basics](#data-science-basics)
2. Quantitative Methods 
3. Programming and Software Engineering
4. [Data Engineering and Data Sources](#data-engineering)
5. [Machine Learning Process and Algorithms](#machine-learning)
6. Applications
7. [Quantum Computing and Machine Learning](#quantum)

<a name="data-science-basics"><a/>
## [Data Science Basics] 
## [Quantitative Methods]
## [Programming and Software Engineering]
  <a name="data-engineering"><a/>
## [Data Engineering and Data Sources]
   [What is data engineering?](#what-data-engineering)
<a name="machine-learning"><a/>
## [Machine Learning Process and Algorithms]
## [Application]
  <a name="quantum"><a/>
## [Quantum Computing and Machine Learning] 


What is Data Engineering?<a name="what-data-engineering"><a/>

Data Engineering is gatheriing and collecting data, stores it, processing (real-time or batch), and serves it via an API.(1). In other words, data engineering is building and maintaining various stages of a data pipeline. The final destination for data is usually a data warehouse. The data is ingested, transformed from raw form to analytical ready form, and loaded to the destination where the data will be served like an API, ERM, Datawarehouse. A datawarehouse is a central place for analytics ready data. The latter pattern to ingest raw data, transform, and load data is called ETL. There are many frameworks to do ETL. There are products for data warehousing. 

What is ETL? 
ETL stands for extract, transform, and load. The ETL Pattern is how most data pipelines are designed and structured.(1) 
    1. Extract is how data is gathered from source locations
    2. Transform is the process where operations are applied to raw data to get in analysis ready form
    3. Load is pushing the data upstream to final destination to be used for analysis. At large companies this is often a data warehouse. 

1. As it relates to electron orbiting a nuclear what does |0> and |1> represent?
excited state and ground state repectively
1. As it relates tophoton what does |0> and |1> represent?
polarization ogf the photon
1. As of 2017 has a fully quantum computer been realized?
No
1. At the time of measurment, if one entangled particle in a pair is in spin state of "down", then behavor of the opposite will be in spin state?
"up"
1. Because a quantum computer has not been realized yet, how are companies like microsoft running quantum computing algorithms?
simulation
1. How are linear systems used in Machine Learning?
linear algebra operations
1. How can you find eigenvalues and eigenvectors using a quantum computer?
quantum eigenvector application to large eigenvalues data matrix
1. How do classical computers perform operations?
bits
1. How do quantum computers perform operations?
qubits
1. How do reinforcement algorithms normally learn optimal actions?
trail and errors
1. How does quantum computing fit in with machine learning?
performing classical machine learning algorithms on quantum problems or develop machine learning algorithms for quantum computers
1. How does quantum computing unlock immense parellelism?
simultaneous processing of solutions
1. How is a quibit with a state of spin pointed directly down denoted?
|1>
1. How is a quibit with a state of spin pointed directly up denoted?
|0>
1. How is/are eigenvalue(s) used in Machine Learning?
perform classical PCA by taking eigenvalue decomposition of a data covariance matrix
1. How many possible solutions can a 300 classical bit computer explore simultaneously?
x=log (2) 300
1. How many possible solutions can a 300 qubit computer explore simultaneously?
2^300
1. How will quantum binary classification possible outperform classical binary classifiers?
grows only logarithmatically as train set increases
1. How will quantum compuiting solve linear systems?
better approximation of expetation value
1. How will quantum computers improve machine learning practioners use principal component analysis?
Quantum PCA of an unknown low-rank density matrix, can reveal the quantum eigenvectors associated with the large eigenvalues, exponentially faster than a linearly-scaled classical algorithm
1. How will quantum computing improve the Higgs Boson experiment? 
seperating signal from background
1. How would a classical computer store the four forms of two classical bits?
groupings of on/off switches
1. How would a quantum computer store the four forms of two classical bits?
sumltaneously
1. How would quantum PCA be faster than classical PCA?
reveal quantum eigenvectors exponentially fater than linear scaled classical algorithm
1. How would you find nearest neighbor on a quantum computer?
reduce query complexity by exponential or polynomial amounts
1. In general n bits can be repserented with how many qubits? 
x = log(2) x
1. In general 'n' qubits can represent how many classical bits?
2^N
1. In order to solve linear system of equations with an quantum algorithm, what do we need to know? 
approximation of the expectation value of some operator associated with x
1. What a linear system?
mathematical model based on use of linear operator
1. What action causes a particle to lose its superposition and exist in only one state?
measuring it
1. What are the appproaches of Quantum Machine Learning?
Classical ML to analyze quantum systems and quantum versions of ML algorithms
1. What are the computational methods to solve linear systems?
linear algebra operations
1. What are the four forms two classical bits can take?
00,01,10,11
1. What are the three categories of machine learning? 
supervised, unsupervised, and reinforcement 
1. What are the three types of unsupervised learning problems?
association, clustering, and dimentionality reduction
1. What are the two methods for dimensionality reduction?
feature extraction and feature selection methods
1. What are the two sets of Supervised Learning problems?
Classifications and regressions
1. What are the two ways qubits can be represented?
an electron orbiting a nucleus
1. What does covariance measure?
measure of variables moving in tandem
1. What does feature extraction do?
Feature Extraction performs data transformation from a high-dimensional space to a low-dimensional space.
1. What does feature selection do?
feature selection selects the subset of the original variables 
1. What does it mean for a particle spin state to be pointed down?
particle is in lowest energy state and aligned with its magnetic field
1. What does quantum decohenrence lead to?
loss of quantum behavior
1. What does quantum entanglement allow qubits to do?
interact instantaneously
1. What example did Satya Nadella use to analogize quantum computer to classical computer performance?
corn maze
1. What is a classification problem in machine learning in supervised learning?
To predict the outcome of a given sample where the output variable is in the form of categories
1. What is a quanta?
energy of a body in discrete packet at atomic and subatomic scale
1. What is a quantum?
smllest physical unit/entity
1. What is a regression problem in machine learning in supervised learning?
To predict the outcome of a given sample where the output variable is in the form of real values.
1. What is a supervised learning?
learning the function that maps the input to the output
1. What is association learning in unsupervised machine learning?
discover the probability of the co-occurrence of items in a collection
1. What is clustering in unsupervised machine learning?
To group samples such that objects within the same cluster are more similar to each other than to the objects from another cluster.
1. What is dimensionality reduction in unsupervised machine learning?
Dimensionality Reduction means reducing the number of variables of a dataset while ensuring that important information is still conveyed
1. What is microsoft quantum simulator name?
LIQUi|>
1. What is quantum decoherence?
quantum system not isolated, there is a loss of information from system into environment
1. What is quantum entanglement?
phenomenon interacting with each other and described in reference to each other, not independently, even when seperated by large distances
1. What is Quantum Machine Learning?
interdisplinary field quantum physics and machine learning
1. What is quibit superposition?
qubit existing as both zero and 1
1. What is reinforcement learning?
Type of machine learning algorithm that allows the agent to decide the best next action based on its current state, by learning behaviours that will maximize the reward.
1. What is the Apriori algorithm purpose?
in transactional database to mine frequent itemsets and ten generate association rules
1. What is the bagging with random forest technique purpose?
combing multiple methods for improved results by voting or averaging
1. What is the benefit for quantum computers to classical computers?
parellelism
1. What is the boosting with AdaBoost technique purpose?
improved results to obtain final outcome
1. What is the CART algorithm purpose?
make predictions of series of node classifiers
1. What is the equation to describe Supervised Learning?
Y = f (X)
1. What is the k-Means algorithm purpose?
group similar data into clusters
1. What is the kNN algorithm purpose purpose?
find k nearest instances for k
1. What is the linear regression algorithm purpose?
determine continuous variable y (e.g. eps)
1. What is the logistic regression algorithm purpose?
determine discrete variable usually for binary classifier (e.g. pass/fail)
1. What is the Naïve Bayes algorithm purpose?
calculate probability an even will occur, given that another event has alrerady occured
1. What is the Principal Component Analysis algorithm purpose?
make data easier to explore and visualize
1. What is unsupervised leearning?
hidden structure in unlabeled data
1. What is wave-particle duality?
characteristic of quantic particles behave as wave sometimes and particle others
1. What quantitative theory is used to find a particle at given point(x) in space?
probability theory
1. What specific business problem is association learning normally used in?
market-basket analysis
1. What temperature do subatomic particles need to be stored at to be stable in Farenheit?
-452 F
1. What type of dimentionality reduction does PCA belong to?
Feature extraction
1. What types of computing task is a quantum computer not optimal for?
general purpose task like watching videos or word processing
1. What types of scientific problems will quantum computers be able to solve?
molecular modelling, creation of high temperature superconductors, drug modelling and testing, 
1. Where is the quibit represented in the figure?
pair of complex vectors pointing to spot on unit sphere
1. Which category of algorithms do Apriori belong to?
Unsupervised learning algorithms
1. Which category of algorithms do Bagging with Random Forests belong to?
Emsemble learning techniques
1. Which category of algorithms do Boosting with AdaBoost belong to?
Emsemble learning techniques
1. Which category of algorithms do CART belong to?
Supervised learning algorithms
1. Which category of algorithms do k-means belong to?
Unsupervised learning algorithms
1. Which category of algorithms do kNN belong to?
Supervised learning algorithms
1. Which category of algorithms do linear regressions belong to?
Supervised learning algorithms
1. Which category of algorithms do logistic regression belong to?
Supervised learning algorithms
1. Which category of algorithms do Naïve Bayes belong to?
Supervised learning algorithms
1. Which category of algorithms do PCA belong to?
Unsupervised learning algorithms
1. Which category of algorithms would a machine learning practioner use to have a robot perform a task better?
Reinforcement algorithms
1. Which specific machine learning method would tell you the following "If a customer purchases bread, he is 80% likely to also purchase eggs."?
market-basket analysis/association learning 
1. Which type of problem task would labeling male/female be?
Classifications
1. Which type of problem task would labeling sick/healthy be?
Classifications
1. Which type of problem task would real-value labeled for amount of rain be?
regression
1. Which type of problem task would real-value labeled for height of a person be?
regression
1. Who proposed the theory of a quanta?
Max Planck
1. Why does quantum nearest neighbor show potential for superior peroformance? 
query complexity reduction or computing distances
1. Why hasn't a quantum computer been realzied yet?
temperature stability adding qubits is difficult







- [ ] 1. A Beginner’s Guide to Data Engineering  –  Part I by Robert Chang, Airbnb (https://www.kdnuggets.com/2018/01/beginners-guide-data-engineering-1.html)
- [ ] 2. The 8 Neural Network Architectures Machine Learning Researchers Need to Learn By James Le, Freelance Full Stack Web Developer https://www.kdnuggets.com/2018/02/8-neural-network-architectures-machine-learning-researchers-need-learn.html/2
- [ ] 3. The 10 Deep Learning Methods AI Practitioners Need to Apply By James Le, Freelance Full Stack Web Developer https://www.kdnuggets.com/2017/12/10-deep-learning-methods-ai-practitioners-need-apply.html
- [x] 4. Quantum Machine Learning: An Overview By Reena Shaw, KDnuggets https://www.kdnuggets.com/2018/01/quantum-machine-learning-overview.html
- [ ] 5. The 10 Statistical Techniques Data Scientists Need to Master By James Le, Freelance Full Stack Web Developer.https://www.kdnuggets.com/2017/11/10-statistical-techniques-data-scientists-need-master.html
- [ ] 6. The 10 Algorithms Machine Learning Engineers Need to Know By James Le, New Story Charity. https://www.kdnuggets.com/2016/08/10-algorithms-machine-learning-engineers.html
- [ ] 7. Top 10 Machine Learning Algorithms for Beginners By Reena Shaw, KDnuggets.https://www.kdnuggets.com/2017/10/top-10-machine-learning-algorithms-beginners.html
- [ ] 8. Why Implement Machine Learning Algorithms From Scratch? By Sebastian Raschka, Michigan State University. https://www.kdnuggets.com/2016/05/implement-machine-learning-algorithms-scratch.html
- [ ] 9. Quantum Algorithms for Nearest-Neighbor Methods for Supervised and Unsupervised Learning by Nathan Wiebe, Ashish Kapoor, Krysta Svore (Submitted on 9 Jan 2014 (v1), last revised 18 Jul 2014 (this version, v2))https://arxiv.org/abs/1401.2142
- [ ] 10. Quantum principal component analysis by Seth Lloyd, Masoud Mohseni & Patrick Rebentrost, Nature Physics volume 10, pages 631–633 (2014)https://www.nature.com/articles/nphys3029
- [ ] 11. https://www.youtube.com/watch?v=g_IaVepNDT4
- [ ] 12. Getting Started with LIQUi|> and Quantum Computing by Lee Stott https://blogs.msdn.microsoft.com/uk_faculty_connection/2017/10/11/getting-started-with-liqui-and-quantum-computing/
- [ ] 13. Quantum Mystery of Light Revealed by New Experiment By Clara Moskowitz https://www.livescience.com/24509-light-wave-particle-duality-experiment.html
- [ ] 14. Lecture 22: Quantum Computing, November 20, 2013 Lecturer: John Wright, http://www.cs.cmu.edu/~odonnell/toolkit13/lecture22.pdf


