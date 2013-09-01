---
title: Research Interests
layout: default
headline: Research in probability modeling, anomaly detection, and other areas.
---
This is a great time to be working in machine learning and cyber security.  There are a lot of important operational problems in cyber security that could benefit from mathematical reasoning and machine learning approaches, except that they are not yet sufficiently well posed.  A good way to pose the problem will lead to useful solutions and new theory. 

I like to draw on methods from probabilistic modeling, Bayesian inference, and machine learning.  It's also fun to be able to draw on pure and applied mathematics, such as graph theory, combinatorial commutative algebra, representation theory, group theory, and computational topology.  The two great benefits of doing this are (1) the application of new, enriching methods to existing problems, and (2) the re-invigoration of a theoretical subject with operationally motivated problems.   Here's a few areas I've been working on.  See my CV (linked to in the sidebar) for references to papers in these areas.

### Anomaly Detection
What is an anomaly?  This is as much a philosophical question as a machine learning question.  My view is that one well founded way to define anomalies is as unusual events.  (Another good approach would be in terms of deviations from a specificaiton.)  A lot of research has defined anomalies in terms of the rarity of an event.  However, sampling from a collection of one million equally likely events, it is a guarantee that the result will have probability one in a million.  Is every event then anomalous?  In my previous work, I've argued that the anomalousness of an event must take into account the entire distribution and give a \(p\)-value of the probability of the event.  This can be generalized to discrete, continuous, and hybrid distributions.  It can be shown that this perspective has important operational benefits in terms of being able to regulate false positives and compare between different anomaly detectors. 

### Large Data Machine Learning
Machine learning algorithms tend to give a similar answer for subsets of data as they give for the entire data set, although with less precision.  However, the algorithms run faster on smaller data sets.  I've looked into ways of using classifiers learned on subsets to estimate or create a classifier for the whole data set.  In the case of Support Vector Machines, there are special properties of support vectors that help facilitate this.  This can be viewed as an inference problem: is a vector a support vector for the whole data set given the results of the subset classifiers?

### Cyber Physical Security
Control theory provides a large body of knowledge on creating and analyzing control systems in the presence of noise, failures, and other changes.  To what extent do targeted intelligent attacks require the development of new, improved methods of analysis?  One difference is in distinguishing between random failures and targeted attacks.  To some extent, robust control theory addresses this issue when it considers worst-case analysis.  Moreover, if the defender and the attacker are both free to make tactical decisions, then a game-theoretic analysis will play an important role.  Concepts of resilience based on controllability and observability can be viewed in terms of the algebraic and combinatorial properties of the matrices that define the (linear) control system.

### Cyber Security Analysis
Since cyber conflicts involve two or more adversarial parties, it makes sense to view the conflict in terms of a (mathematical) game.  However, the theory to do so is still very elementary and not appropriate for realistic scenarios.  I have developed a framework for representing "the game", including the status of the board and the available moves.  Additional research is required to build a board based on real-world assets and data, and to develop the game theory appropriate to this application.

