---
layout: page
title: ArchiVehicle
description: A data engineering process for the information management of a vehicle park of a car dealer.
img: assets/img/archivehicle/logo/archivehicle_logo.png
category: data engineering and analysis
importance: 2
---

<a href="https://github.com/Tensa53/archivehicle">ArchiVehicle</a> aims to simplify and digitalize the
information management about a vehicle park, through a data engineering process.

The main steps of this process are:

- **Data Collection**: In order to simulate the vehicle infos, a <a href="https://www.kaggle.com/datasets/kanchana1990
/vehicle-dataset-2024">dataset</a> from Kaggle has been picked;
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/archivehicle/screen/archivehicle_screen1.png" 
            title="vehicle image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

- **Data Augmentation**: There were no info about the vehicles manufacturer, so through ChatGPT a new csv dataset has
been generated with the main info needed;
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/archivehicle/screen/archivehicle_screen2.png" 
            title="manufacturers image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

- **Data Cleaning**: Given the two datasets, some operations of cleaning, such as removing null values, changing data
types and renaming columns, have been done with Pandas and Jupyter Notebook.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/archivehicle/screen/archivehicle_screen3.png" 
            title="search image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

After all the data cleaning, the two obtained .csv dataset where prepared and used for the:

- **Data Storage**: The datasets have been used to create a No-SQL Database in MongoDB, through the Compass UI

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/archivehicle/screen/archivehicle_screen4_gresized.png" 
            title="stats image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/archivehicle/screen/archivehicle_screendoc.png" 
            title="docs image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The screenshot of the stats page and the frontmatter of the documentation.
</div>

Aside from the data engineering artifacts, for this project we have the following deliverables:

- **Documentation (Both in Italian and English)**: In this documentation, we describe all the activities made in order
  to analyze the dataset;
- **Json Database**: After the first import of the datasets, for an easy replicability, the database has been exported
  in a .json format;
- **WebApplication**: A very simple form-based web-application where you can do CRUD operations on the vehicles and
  manufacturer information, search and view the vehicles catalog.

This project was realized for the Database II Class.

You can find any other information for this project on the dedicated GitHub repository.
