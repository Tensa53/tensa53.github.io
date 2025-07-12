---
layout: page
title: Momentum:2
description: A penetration testing process for the security analysis of the Momentum:2 virtual machine.
img: assets/img/momentum/logo/momentum_logo.png
category: software dependability and security
importance: 1
---

<a href="https://github.com/Tensa53/Momentum2_Pentest">Momentum:2 Pentest</a> is a penetration testing conducted on
a virtual asset from Vulnhub in order to complete all the phases of a Penetration Testing Framework.

The phases are grouped in:

- **Pre-Exploitation**: All the phases where you analyze the asset and get all the possible 
information on many different aspects, such as network configuration, operating system, port scanning, 
related vulnerabilities;

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/momentum/screen/momentum_screen1.png" 
            title="pre-exploit image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

- **Exploitation**: Given the obtained information during the previous phases group, it is possible to build an exploit 
and send a payload to be able to execute a reverse shell and access the asset machine;

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/momentum/screen/momentum_screen2.png" 
            title="exploit image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

- **Post-Exploitation**: After a successful exploitation on the machine through the webapp, many ways are explored 
to obtain a shell from root user or other normal users and install a backdoor to maintain the access on the machine;

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/momentum/screen/momentum_screen3.png" 
            title="post-exploit image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

All the completed practical phases are executed inside a Virtual Box Environment with three machines:

- **<a href="https://cdimage.kali.org/kali-2025.1c/kali-linux-2025.1c-virtualbox-amd64.7z">Kali Linux 2025.1c</a>**: 
The latest available version of Kali Linux when the penetration testing activity started;
- **<a href="https://vulnhub.com/entry/momentum-2,702/">Momentum:2</a>**:The virtual machine downloadable from Vulnhub
and used as the analyzed asset of this process;
- **<a href="https://www.greenbone.net/en/greenbone-free/">Greenbone</a>**: The virtual machine that offers the free
version of the OpenVAS tool used for the vulnerability mapping activity.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/momentum/screen/momentum_screen4_gresized.png" 
            title="plot report image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/momentum/screen/momentum_screendoc.png" 
            title="doc image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The plot realized for counting the vulnerabilities and the frontmatter of the documentation.
</div>

For this project, we have the following deliverables:

- **Documentation (In Italian)**: The documentation provides a document for the full replicability of the process and
a document for the report of the security issues and vulnerability found, with some possible remediation;
- **Tool Report**: The report of all the tools that generated some detailed results, such as Nessus, OpenVAS, ZAP;
- **Project Scripts and Exploit**: All the created script used to automate some activities and the used exploit;

This project was realized for the Penetration Testing and Ethical Hacking class.

You can find any other information for this project on the dedicated GitHub repository.
