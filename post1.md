# The Learning Project

Ever since I finished reading Scott H. Young's book titled ***"Ultralearning"***, I wanted to try my hand at challenging myself to learn what I can call, "the project".
This project involves learning and developing the skills and processes involved in software engineering, data engineering, data science, and machine learning - and it is quite a big list.
Fortunately, the skills build upon each other, and the processes follow a pipeline.
During this learning project, I'll be following Scott Young's framework that he introduced in his book, with some slight adjustments due to
the scope of the project and my end goal which is mostly self-enrichment.
The framework itself can be easily defined, but the follow through is a different challenge in itself.
I'll start with how Scott Young defined the steps, followed by a brief explanation of what needs to be done, and how I will apply it on as I go through the challenge.

## Step 1: Metalearning

The first step and possibly the most impactful step in an Ultralearning project is to draw a map of what I will be tackling.
He called this step **metalearning**, or learning how to learn the subject.
It entails looking for the best resources on how to learn the subject, identify the core skills that it relies on,
and adopting the pathway that others followed to learn or even master the subject in question.
Since my project can be done in a formal academic setting, I will base my curriculum on the course outline from a few Universities while omitting unnecessary elective if I choose to do so.

The following sub-headings list topics where computer science, software engineering, data science and machine learning converge.
Please note that I used Qwen3 to help me map out these concepts.

### On Mathematical Preliminaries

Below is the list of foundational mathematics that I need to cover. I do think I don't need to go past Optimization Theory in the current scope of the project.

| Domain | Core Topics | Relevance to CS/DS Convergence |
|--------|-------------|-------------------------------|
| **Calculus** | Single-variable, multivariable/vector calculus, partial derivatives, gradients | Essential for understanding optimization landscapes in machine learning; gradients drive backpropagation in neural networks |
| **Linear Algebra** | Vector spaces, matrix operations, eigenvalues/eigenvectors, SVD, PCA | The language of data representation; powers dimensionality reduction, neural networks, and recommendation systems |
| **Probability Theory** | Random variables, distributions, Bayes' theorem, stochastic processes | Quantifies uncertainty in predictions; foundational for Bayesian methods and probabilistic graphical models |
| **Mathematical Statistics** | Hypothesis testing, confidence intervals, regression theory, experimental design | Enables inference from data; distinguishes signal from noise in model evaluation |
| **Discrete Mathematics** | Logic, set theory, combinatorics, graph theory, proof techniques | Provides formal reasoning tools for algorithms, database theory, and computational complexity |
| **Optimization Theory** | Convex/non-convex optimization, gradient descent variants, Lagrange multipliers | The engine of machine learning training; most ML algorithms reduce to optimization problems |
| **Numerical Analysis** | Numerical integration, interpolation, stability analysis, error propagation | Bridges continuous mathematics to finite-precision computation; critical for implementing algorithms reliably |
| **Real Analysis** | Limits, continuity, measure theory, function spaces | Provides rigorous foundations for convergence proofs in learning theory (advanced but increasingly relevant) |
| **Abstract Algebra** | Groups, rings, fields, finite fields | Underpins modern cryptography and secure computation; essential for privacy-preserving ML |
| **Topology** | Homotopy, persistent homology, manifold learning | Enables Topological Data Analysis (TDA) to extract shape-based features from complex datasets |
| **Information Theory** | Entropy, mutual information, channel capacity, coding theory | Quantifies information content; informs feature selection, model compression, and communication protocols |

### On the foundations of Computer Science and Data Science

| Area | Convergent Topics | Intersection Point |
|------|-------------------|-------------------|
| **Algorithms & Data Structures** | Hashing, trees, graphs, dynamic programming, amortized analysis | Efficient data manipulation at scale; algorithmic complexity directly impacts model training time |
| **Computational Complexity Theory** | P/NP classification, time/space complexity, approximation algorithms | Determines feasibility of learning problems; guides algorithm selection for large datasets |
| **Database Systems** | Relational algebra, query optimization, indexing, transaction processing | Data engineering pipeline foundation; bridges storage to analytics |
| **Distributed Systems** | Consensus protocols, fault tolerance, MapReduce, Spark RDDs | Enables processing of datasets beyond single-machine capacity; core to modern data platforms |
| **Machine Learning** | Supervised/unsupervised learning, reinforcement learning, deep learning architectures | The primary convergence zone where CS algorithms meet statistical modeling |
| **Natural Language Processing** | Tokenization, parsing, embeddings, transformer architectures | Applies linguistic theory + CS algorithms to extract meaning from unstructured text |
| **Graph Theory / Network Science** | Centrality measures, community detection, random walks, spectral graph theory | Models relational data (social networks, knowledge graphs); increasingly vital for recommendation systems |

## Step 2 Focus

The next step is about the development of my ability to concentrate on learning these skills. He also identified three common hurdles that
any learner would face. And these are hurdles on starting (procrastination), sustained concentration (distraction), and finding and staying in the "flow".
Young did suggest ways on how to tackle the three hurdles.

### Procrastination

**The Five-minute Rule** - suggests that we only have to start working on our tasks for 5 minutes, as the mental resistance disappears within five minutes in to the activity.
**Recognize the "Urge"** - By being mindful of our urges to stepping away from our task, we take away that urge once we recognize that its there.
**Scheduling** - Set specific "low-intensity" time during the day.

### Distractions

**Environmental Optimization** - a clear workspace that is free of any possible distractions. This can be putting your phone on do not disturb mode,
or blocking access to specific apps or even access to the internet if need be.
**Desirable Difficulty** - sometimes our learning materials are the problem, try to find the goldilocks zone where difficulty and engagement are balanced.
**Keep your head in the game** - there are times that our brains are the source of distraction. If a random task pop into our head, write it down so that you can handle it later and then go back to work.

There are similar techniques that Dr. Justin Sung and his team in ICandStudy.com teach to learners enrolled on their website, but if you can't afford a subscription Dr. Sung has talked about distraction in his youtube channel. There are also other Youtube content creator that teaches skills related to distraction management.

### Flow state

Flow has been defined as a state of absorption and immersion on the current task. However people often struggle to reach it, or they wait for the flow state
which then prevents them into doing relevant "deep work". A steady and concentrated effort is more reliable, than forcing ourselves to get into this mental state (This never happens).

## Step 3 Directness

Directness, or if we want a more elegant phrasing, deliberate practice is when we 