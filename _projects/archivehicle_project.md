---
layout: page
title: ArchiVehicle
description: A very simple form-based web-app where you can manage vehicles info.
img: assets/img/archivehicle/logo/archivehicle_logo.png
category: master degree classes
importance: 4
---

<a href="https://github.com/Tensa53/archivehicle">ArchiVehicle</a> aims to simplify and digitalize the information management about a vehicle park,
through a graphical user interface served by a client/server architecture.

The main functionalities of this web-appliaction are:

- **CRUD Operations for Vehicles**: Create, Read, Update, Delete the document of a vehicle's information;
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/archivehicle/screen/archivehicle_screen1.png" title="vehicle image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

- **CRUD Operations for Manufacturers**: Create, Read, Update, Delete the document of a manufacturer's information;
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/archivehicle/screen/archivehicle_screen2.png" title="manufacturers image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

- **Search for a specific vehicle**: On the home page, you can search for a vehicle and set some filters.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/archivehicle/screen/archivehicle_screen3.png" title="search image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

If you don't know which vehicle to search, you can explore all the vehicles cataloge in the Vehicles Page. ArchVehicle also offer this functionality:

- **Manufacturer Stats**: You can display the number of vehicle for each manufacturer, filter by different features.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/archivehicle/screen/archivehicle_screen4_gresized.png" title="stats image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/archivehicle/screen/archivehicle_screendoc.png" title="docs image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The screenshot of the stats page and the frontmatter of the documentation.
</div>

Aside from the webapplication, for this project we have the following deliverables:

- **Documentation (Both in Italian and English)**: In this documentation, we describe all the activity made in order to obtain the sample of the database used;
- **Datasets**: All the datasets used for this project, one for each entity (vehicles and manufacturers);
- **Notebooks**: Starting from the dataset, we have made some operations of cleaning thanks to the pandas library.

This project was realized for the Database II Class.

You can find any other information for this project on the dedicated GitHub repository.
