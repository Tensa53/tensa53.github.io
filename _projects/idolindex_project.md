---
layout: page
title: IdolIndex
description: A database design process for the information management of idols activities and songs.
img: assets/img/idolindex/logo/idolindex_logo.png
category: data engineering and analysis
importance: 3
---

<a href="https://github.com/Tensa53/IdolIndex">IdolIndex</a> aims to define a database for the
information management about idols activities and song, through a complete database design process.

The process is defined on different phases:

- **Requirements Elicitation**: All the client requests are listed in an informal way;
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/idolindex/screen/idolindex_screen1.png" 
            title="vehicle image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

- **Initial Database Schema**: Through the requirements, a first database schema is being made;
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/idolindex/screen/idolindex_screen2.png" 
            title="manufacturers image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

- **Data Dictionary and Business Rules**: All the information and rules about the schema, are also formalized in a table format.
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/idolindex/screen/idolindex_screen3.png" 
            title="search image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

For this process, other steps are being done:

- **Redundancy Analysis**: The number of access and operations to the different tables are estimated;
- **Scheme Restructuring**: The database schema is restructured in order to handle hierarchies and multi-value 
attributes;
- **Logic Scheme**: A logic scheme is defined to better translate the database design into the specific MySQL DBMS 
instance.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/idolindex/screen/idolindex_screen4.png" 
            title="stats image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/idolindex/screen/idolindex_screenrun.png" 
            title="run image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The logic scheme and the screenshot of the java program for CRUD operations.
</div>

Aside from the database design artifacts, for this project we have the following deliverables:

- **Project Presentation(In Italian)**: The presentation hase some details on redundancy analysis and scheme 
restructuring;
- **SQL Scripts**: There are four SQL Scripts related to table creation, data insertion and query operations;
- **Java Program**: A simple Java Program to try some CRUD operations on a table and execute a query.

This project was realized for the Database I Class.

You can find any other information for this project on the dedicated GitHub repository.
