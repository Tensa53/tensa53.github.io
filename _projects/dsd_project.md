---
layout: page
title: Data Smell Detection+
description: A simulation of a maintenance activity for a tool that finds data smells on an uploaded dataset.
img: assets/img/dsd/logo/dsd_logo.png
category: master degree classes
importance: 2
---

<a href="https://github.com/CpDant/DSD-plus">Data Smell Detection+</a> (DSD+) is based on the open-source data
validation tool Great Expectations, and it uses rule-based techniques for detecting smells by analyzing a dataset.

The main functionalities of this tool are:

- **Upload a file**: In order to correct compute the results, the dataset to be uploaded has to be a .csv file;
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/dsd/screen/dsd_screen1.png" 
      title="upload image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

- **Customize the detection**: You can customize the detection, setting the desired data smells and other parameters;
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/dsd/screen/dsd_screen2.png" 
      title="customization image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

- **View the result of the analysis**: After the analysis is complete, you can display the results by columns.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/dsd/screen/dsd_screen3.png" 
      title="result image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

We made a contribution for this tool (that's where the '+' comes from) in order to improve it and to simulate a
maintenance activity. This project was evaluated for the Software Engineering, Management and Evolution (IGES)
and Software Engineering for Artificial Intelligence (SE4AI) classes.
During the maintenance we have mainly completed three change requests:

- **Extend the detection suite of the tool**: We added more implementation for the detection of new data smells;
- **Compute the data quality dimensions**: After computing the results, we also calculated some data quality dimensions;
- **Improve the results visualization**: We improved the results page, adding graphs and grouping up better the results;

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/dsd/screen/dsd_screen4_gresized.png" 
      title="new result image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/dsd/screen/dsd_screendoc.png" 
      title="docs image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The screenshot of the new results page and the frontmatter of the documentation.
</div>

Aside from the tool, for this project we have the following deliverables:

- **IGES Documentation (in Italian)**: In this documentation we mainly gave focus on all the formal aspects of a
  maintenance activity, such as Reengineering, Impact Analysis, Software Testing;
- **SE4AI Documentation (in English)**: In this documentation we mainly gave focus on the more technical aspects of the
  goal of the original tool, such as describing what is a data smell and a data quality dimension, which datasets can be
  used to try the tool, what are the future works for other improvement on this tool.

For this project I've collaborated with <a href="https://github.com/CPDant">CPDant</a> and
<a href="https://github.com/adriano22jr">adriano22jr</a>.

You can find any other information for this project on the dedicated GitHub repository.
