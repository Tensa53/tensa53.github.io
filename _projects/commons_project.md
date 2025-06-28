---
layout: page
title: Commons-net Dependability
description: A dependability report for a famous open source library of the Apache Commons project.
img: assets/img/commons/logo/commons_logo.png
category: software engineering and management
importance: 2
---

<a href="https://github.com/Tensa53/commons-net">Commons-net</a> Dependability is an analysis that we conduct on this
library in order to improve the dependability properties and more in general the quality of the project.

The main activities we have completed are:

- **Sonarcloud Analysis**: We have executed the Sonarcloud tool in order to obtain the affected issues count about
  the library;

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/commons/screen/commons_screen1.png" 
            title="sonarcloud image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

- **Codecov Analysis**: We have executed the Codecov tool to obtain the info about the test
  coverage of the library's code;

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/commons/screen/commons_screen2.png" 
            title="codecov image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

- **FindSecBugs**: We have executed the FindSecBugs tool in order to detect any additional vulnerability;

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/commons/screen/commons_screen3.png" 
            title="findsecbugs image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

During this analysis we have also completed some other activities:

- **Bug fixing and Code Smells**: We implemented some quick fix to solve some bugs and also removed some code smells;
- **Vulnerability assessment**: We checked some of the spotted vulnerabilities and decided how to deal with them;
- **Coverage improvement**: We used some tools to generate new test cases and try to increase coverage.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/commons/screen/commons_screen4_gresized.png" 
            title="sonarcloud after image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/commons/screen/commons_screendoc.png" 
            title="doc image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The screenshot of SonarCloud analysis after completing the activities and the frontmatter of the documentation.
</div>

For this project, we also have the following deliverables:

- **Documentation (In English)**: In this documentation we explain with more detail all the step described here and show
  the use of other tools;
- **Generated Test Cases**: All the generated test cases were saved but not directly integrated inside the project,
  but they are freely viewable;

This project was realized for the Software Dependability Class and I've collaborated with
<a href="https://github.com/FraPCA">FraPCA</a>.

You can find any other information for this project on the dedicated GitHub repository.
