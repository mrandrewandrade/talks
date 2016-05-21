========================================================
title: Data Science Framework and Machine Learning 101
author: Andrew Andrade, Stats and Data Science Club
date: June 2, 2016



Why?
========================================================

![](http://i.stack.imgur.com/mlhO9.jpg)

Let's not jump to big data before we work on some data!

Let's not jump to neural networks before we work on some logistic regression!

Let's not jump to random forest before we work on some simpler branches!


Goals
========================================================

1. How to Think Like a Data Scientist
2. Learn Structured Data Science Framework
3. Learn Basics of Machine Learning and Data Mining

Slides online:  

[mrandrewandrade.com/talks/data-science-framework](http://mrandrewandrade.com/talks/data-science-framework.html)



About Me:
========================================================

# Andrew Andrade

## Co-op experience:
- Start-ups in oil and gas and semiconductor
- Chrysler, PetroCanada (Suncor), Facebook
- PetroPredict

## Research:
Applications of Machine Learning and Intelligence amplification:

- Self-driving Vehicles
- Production Optimization
- Hardware and Manufacturing
- Educational Data Mining


What is a Data Scientist?
========================================================

![](http://i2.wp.com/blog.udacity.com/wp-content/uploads/2014/11/blog_dataChart_white.png?resize=640%2C740)

Source: [Udacity](http://blog.udacity.com/2014/11/data-science-job-skills.html)

What is Data Science?
========================================================

![](http://b-i.forbesimg.com/gilpress/files/2013/05/Data_Science_VD.png)

Source: [Drew Conway](http://drewconway.com)

What is Data Science to Andrew Andrade
========================================================


Shifting between deductive (hypothesis-based) to inductive (pattern-based) reasoning.


What is Data Science to Andrew Andrade
========================================================

Bottom up meets top down

Intelligence amplification
========================================================

The creation of the man-machine symbiosis

![](http://i.imgur.com/yYC26PU.png)

Source: Joe Lonsdale / Formation8


Intelligence amplification
========================================================


![](http://i.imgur.com/PURXSbQ.png)

Source: Joe Lonsdale / Formation8

Intelligence amplification
========================================================

![](http://i.imgur.com/3NJc0w6.png)
Source: Joe Lonsdale / Formation8


What is Data Mining?
========================================================

Explaining the past and predicting the future by means of data analysis


What is Data Mining?
========================================================

![](http://www.saedsayad.com/images/DM.png)


Intelligence Amplification
========================================================
![](http://i.imgur.com/TA9sA85.png)
Source: Joe Lonsdale / Formation8


The Data Science Framework
========================================================


Ask > Acquire > Assimilate > Analyze > Answer > Advise > Act


1. Ask
========================================================

__Ask__ > 


Data Science starts by asking the right questions


Be a Star
========================================================

Solve exceptional problems

[beastar.uwaterloo.ca](http://beastar.uwaterloo.ca/)



2, 3. Acquire and Assimilate
========================================================

Ask > ___Acquire > Assimilate___ > Analyze > Answer > Advise > Act

1. What data would be necessary?

2. What data is available?

3. What form is the data in?

4. How to transform data?

5. Repeat


Feature Engineering
========================================================


When working on a machine learning problem, feature engineering is manually designing what the input x's should be.
— Shayne Miel, "What is the intuitive explanation of feature engineering in machine learning?"


What is Feature Engineering?
========================================================

Feature engineering is the process of transforming raw data into features that better represent the underlying problem to the predictive models, resulting in improved model accuracy on unseen data.


Feature Engineering
========================================================

Coming up with features is difficult, time-consuming, requires expert knowledge. "Applied machine learning" is basically feature engineering.

— Andrew Ng


Importance Feature Engineering
========================================================


1. Better features means flexibility.
2. Better features means simpler models.
3. Better features means better results.


Importance of Feature Engineering
========================================================

…some machine learning projects succeed and some fail. What makes the difference? Easily the most important factor is the features used.

— Pedro Domingos, in "A Few Useful Things to Know about Machine Learning"


Garbage In, Garbage Out
========================================================


![](http://i.stack.imgur.com/yZQgZ.gif)



Further Reading
========================================================

[Discover Feature Engineering, How to Engineer Features and How to Get Good at It](http://machinelearningmastery.com/discover-feature-engineering-how-to-engineer-features-and-how-to-get-good-at-it/)





4. Analyze
========================================================


Ask > Acquire > Assimilate > ___Analyze___ > Answer > Advise > Act

1. Exploratory Data Analysis
2. Unsupervised Machine Learning
3. Supervised Machine Learning


Understand your data!
========================================================

Most important step in Analyze!

Exploratory Data Analysis
========================================================

1. Summary statistics and visualizations to better understand data

2. Find clues about the tendencies of the data, its quality

3. Formulate assumptions and the hypothesis of your analysis. 

4. Quick and dirty visualizations

5. Not infographics!



A Facebook Primer
========================================================

![](http://i.imgur.com/MecxGG7.png)


Exploratory Data Analysis
========================================================
![](http://i.stack.imgur.com/3ngU8.png)

Source: XKCD

View outliers
========================================================
![](http://bp1.blogger.com/_x7QjiZypFj0/Rp9dcGTsBKI/AAAAAAAAAA0/VWwfWDv6nzM/s400/Outlier.jpg)

Source: Ben Shabad 


View Error Bounds
========================================================
![](http://i.stack.imgur.com/c6ECF.png)

Source: http://velica.deviantart.com

Example of Bad Practice: Junk Charts
========================================================


![](http://static4.businessinsider.com/image/51bf1e9becad048c0a000002-620-/screen%20shot%202013-06-17%20at%2010.34.08%20am.png)

Example of Bad Practice: Junk Charts
========================================================

![](http://static2.businessinsider.com/image/51bf0aa8ecad04a05d00004a-995-382/screen%20shot%202013-06-17%20at%209.07.44%20am.png)

Another example of Junk Charts
========================================================
![](https://i2.wp.com/cdn3.vox-cdn.com/assets/4824510/pev-sales-june.png?zoom=2)

Another example of Junk Charts Fixed
========================================================

![](https://solomonmessing.files.wordpress.com/2014/10/6008e-6a00d8341e992c53ef01a3fd3fdcc3970b-pi.png?w=400)

Further Reading
========================================================

The Visual Display of Quantitative Information

Edward Tufte

Box Plots
========================================================

[![](http://stanford.edu/~mwaskom/software/seaborn/_images/horizontal_boxplot.png)](http://stanford.edu/~mwaskom/software/seaborn/examples/horizontal_boxplot.html)


Histograms
========================================================


[![](http://matplotlib.org/1.3.1/_images/histogram_demo_extended_00.png)](http://matplotlib.org/1.3.1/examples/pylab_examples/histogram_demo_extended.html)


Violin Plots
========================================================


[![](https://web.stanford.edu/~mwaskom/software/seaborn/_images/simple_violinplots.png)](https://web.stanford.edu/~mwaskom/software/seaborn/examples/simple_violinplots.html)



Scatter Plots
========================================================

[![](http://matplotlib.org/_images/scatter_symbol.png)](http://matplotlib.org/examples/pylab_examples/scatter_symbol.html)


Line chart
========================================================

[![](http://matplotlib.org/_images/plotfile_demo_00.png)](http://matplotlib.org/examples/pylab_examples/plotfile_demo.html)

Multifacted Line Charts
========================================================
[![](https://web.stanford.edu/~mwaskom/software/seaborn/_images/many_facets.png)](https://web.stanford.edu/~mwaskom/software/seaborn/examples/many_facets.html)



Multivariate Visualization
========================================================


[![](http://matplotlib.org/_images/scatter3d_demo.png)](http://matplotlib.org/examples/mplot3d/scatter3d_demo.html)

Multivariate Visualization
========================================================

[![](http://stanford.edu/~mwaskom/software/seaborn/_images/scatterplot_matrix.png)](http://stanford.edu/~mwaskom/software/seaborn/examples/scatterplot_matrix.html)


Multivariate Visualization
========================================================
[![](http://matplotlib.org/_images/mri_with_eeg.png)](http://matplotlib.org/examples/pylab_examples/mri_with_eeg.html)


Image classification
========================================================

[![](http://scikit-learn.sourceforge.net/0.6/_images/plot_face_recognition.png)](http://scikit-learn.sourceforge.net/0.6/auto_examples/applications/plot_face_recognition.html)


Decomposed Images
========================================================

[![](http://scikit-learn.org/stable/_images/plot_faces_decomposition_002.png)](http://scikit-learn.org/stable/auto_examples/decomposition/plot_faces_decomposition.html)


Simple Example: MSCI 723
========================================================

![](http://datascienceguide.github.io/images/mark_vs_time_studying.png)



4. Analyze: Unsupervised Machine Learning
========================================================


Ask > Acquire > Assimilate > ___Analyze___ > Answer > Advise > Act

1. Exploratory Data Analysis
2. ____Unsupervised Machine Learning___
3. Supervised Machine Learning


4.1 Unsupervised Machine Learning
========================================================

1. Dimensionality Reduction
2. Outlier Detection
3. Clustering
4. Association

4.1.1 Dimensionality Reduction
========================================================

![](http://www.holehouse.org/mlclass/14_Dimensionality_Reduction_files/Image%20%5B1%5D.png)

Source: Andrew Ng, Machine Learning

4.1.1 Dimensionality Reduction
========================================================
![](http://www.holehouse.org/mlclass/14_Dimensionality_Reduction_files/Image%20%5B10%5D.png)


4.1.2 Outlier Detection
========================================================

![](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4e/LOF-idea.svg/375px-LOF-idea.svg.png)

Comparing the local density of a point with the densities of its neighbors


4.1.3 Clustering
========================================================

![](https://datasciencelab.files.wordpress.com/2013/12/p_n200_k3_g.gif?w=830)

K means Clustering
========================================================

![](https://datasciencelab.files.wordpress.com/2013/12/p_n200_k3_g.gif?w=830)


Fuzzy C Means Clustering
========================================================

[![](http://pythonhosted.org/scikit-fuzzy/_images/plot_cmeans_4.png)](http://pythonhosted.org/scikit-fuzzy/auto_examples/plot_cmeans.html)


Clustering Algorithm Comparison
========================================================

[![](http://scikit-learn.org/stable/_images/plot_cluster_comparison_001.png)](http://scikit-learn.org/stable/auto_examples/cluster/plot_cluster_comparison.html)











# Questions?

### andrew@andrewandrade.ca

 	