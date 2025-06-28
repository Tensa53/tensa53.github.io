---
layout: page
title: Phishing Domains
description: A statistical report on a dataset of suspiscious phishing urls.
img: assets/img/phishingdomains/logo/phishingdomains_logo.png
category: data engineering and analysis
importance: 1
---

<a href="https://github.com/mariantonietta-maselli/Progetto_SAD">Phishing Domains</a> is an analysis that we
conduct on the <a href="https://www.frontiersin.org/journals/computer-science/articles/10.3389/fcomp.2024.1308634/full">
dataset</a> in order to analyze some features related to the domains considering different statistical aspects.

The main activities we have completed are:

- **Descriptive Statistics**: We have analyzed the central tendency and dispersion of the features, also describing its
form by the skewness and kurtosis of the frequency distribution;
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/phishingdomains/screen/phishingdomains_screen1.png" 
            title="plot image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

- **Inferential Statistics**: We have analyzed a sample of the dataset to carry out a test of normality and calculate
some estimates related on the mean and variance of the population;
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/phishingdomains/screen/phishingdomains_screen2.png" 
            title="test image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

- **Synthetic Data Generation**: We have defined a prompt to ask an LLM to generate a synthetic sample of the dataset
and try to see if the synthetic sample can replace the real one.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/phishingdomains/screen/phishingdomains_screen3.png" 
            title="chat image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

During this analysis we also completed some other activities:

- **Dimensionality Reduction**: We removed some features of the dataset based on their low variance, high redundancy
  and easy derivability;
- **Data Cleaning**: We removed the outlier and the duplicates from the features, in order to realize a better
  analysis and a more performing model;
- **Simple Linear Regression**: We picked the two highest correlated feature to realize a simple linear regression model
  that estimates the domain length given the entropy value of the domain;

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/phishingdomains/screen/phishingdomains_screen4_gresized.png" 
            title="model image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/phishingdomains/screen/phishingdomains_screendoc2.png" 
            title="docs image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The scatterplot with the line of best fit from the model and the frontmatter of the documentation.
</div>

For this project we have the following deliverables:

- **Documentation (In Italian)**: In this documentation, we describe with more detail all the activities showed here;
- **Datasets**: The dataset used for this project and the other versions of it, obtained from several transformation;
- **R Scripts**: Starting from the dataset, all the operations have been automated using some scripts written in R.

This project was realized for the Statistics and Data Analytics Class and I've collaborated with
<a href="https://github.com/mariantonietta-maselli">mariantonietta</a>.

You can find any other information for this project on the dedicated GitHub repository.
