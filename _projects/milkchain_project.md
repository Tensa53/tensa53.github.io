---
layout: page
title: Milkchain
description: A blockchain driven web-app for the certification of the parmigiano cheese production steps.
img: assets/img/milkchain/logo/milkchain_logo.png
category: software dependability and security
importance: 3
---

<a href="https://github.com/francesco-giorgione/SDD-webapp">Milkchain</a> aims to digitalize and simplify the 
traceability and certification of parmigiano cheese production supply chain.

The main functionalities of the webapp are:

- **Trace a piece of cheese**: Given the id of a piece of cheese, you can retrieve all the information about the 
production from the cheese where the piece is being sliced from to the milk silos used to produce it;

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/milkchain/screen/milkchain_screen1.png" 
            title="trace cheese piece image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

- **Insert production information**: To guarantee the traceability of the cheese piece, all the information about the 
different steps to produce a cheese are added through some forms and memorized;

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/milkchain/screen/milkchain_screen2.png" 
            title="insert prod info image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

- **Show the movements**: Every movement of a member of the parmigiano supply chain that has to buy a product 
from the previous one and sell it to the next one, are visualized and memorized;

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/milkchain/screen/milkchain_screen3.png" 
            title="show movements image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

In order to complete this webapp, we had to set up a blockchain environment with hyperledger firefly:

- **Create a Firefly Stack**: We created the minimum (4) node required to create a firefly stack for the supply chain;
- **Smart Contracts Deploy**: We compiled and deployed the smart contracts on the stack to implement the logic for 
storing all the information on the blockchain;
- **ABI and API Creation**: We used extract the ABI from the compiled contracts and created the API through the firefly 
dashboard.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/milkchain/screen/milkchain_screen4_gresized.png" 
            title="firefly dashboard image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/milkchain/screen/milkchain_screendoc.png" 
            title="doc image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The screenshot of the Hyperledger Firefly Dashboard and the frontmatter of the documentation.
</div>

For this project, we also have the following deliverables:

- **Documentation (In Italian)**: In this documentation we elicited and analyzed all the client requirements and created
some use cases identifying all the users of the system;

This project was realized for the Data Security Class and I've collaborated with
<a href="https://github.com/francesco-giorgione">francesco-giorgione</a>.

You can find any other information for this project on the dedicated GitHub repository.
