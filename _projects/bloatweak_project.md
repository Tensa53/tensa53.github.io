---
layout: page
title: BloatWeak
description: A tool that finds bloated dependencies affected by known vulnerabilities in Python projects.
img: assets/img/bloatweak/logo/bloatweak_logo.png
importance: 4
---

<a href="https://github.com/Tensa53/BloatWeak">BloatWeak</a> has the goal to find bloated dependencies affected by known vulnerabilities inside a Python Project, combining the use of different tools and creating a new script.

This project combines:

- **<a href="https://github.com/NJUJisq/DS_Python">PyCD</a> Analysis**: We executed the PyCD tool in order to obtain the dependencies list in a convenient format (.csv file); 

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/bloatweak/screen/bloatweak_screen1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

- **<a href="https://github.com/tweag/FawltyDeps">FawltyDeps</a> Analysis**: We executed the FawltyDeps tool in order to obtain the list of unused dependencies;

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/bloatweak/screen/bloatweak_screen2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

- **<a href="https://github.com/pyupio/safety/">Safety</a> Analysis**: We executed the Safety tool in order to obtain the list of vulnerable dependencies;

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/bloatweak/screen/bloatweak_screen3.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

So with the combination of these three tools, and given a <a href="https://github.com/soarsmu/NICHE">dataset</a> of projects to analyze, we were able to observe:
- **Bloated Dependencies**: We analyzed the diffusion of bloated dependencies by checking how many project were affected by this issue;
- **Software Vulnerabilities**: We analyzed the diffusion of software vulnerabilities by checking how many project were affected by this issue;
- **Combined Issues**: We analyzed the diffusion of the combination of the two above-mentioned issues by checking the different projects;

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/bloatweak/screen/bloatweak_screen4_gresized.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/bloatweak/screen/bloatweak_screendoc.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The screenshot of an execution of the new created script and the frontmatter of the documentation.
</div>

For this project we have also the following deliverables:
- **Bachelor Degree Thesis (in Italian)**: YES, this project was realized for my graduation. Inside the thesis you can find more details about these topics and some consideration on another possible approach we tried;
- **Extra Script**: In order to rapidly download all the project, execute the new script and save the results, some extra script have been realized;
- **Outcome Achieved**: All the initial, intermediate and final results were meticulously grouped in various spreadsheet that are also freely viewable;

You can find any other information for this project on the dedicated GitHub repository.
