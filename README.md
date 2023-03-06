
<!-- badges: start -->

[![Launch
Binder](http://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/IdoBar/3030NSC-workshops-binder/main)
<!-- badges: end -->

<img src="https://www.griffith.edu.au/__data/assets/image/0018/653121/Griffith_Full_Logo_scaled.png" width="25%" style="display: block; margin: auto 0 auto auto;" />

# 3030NSC Workshops (Binder-ready)

This repository was developed as an educational tutorials/workshops for
the Applied Bioinformatics course (3030NSC/7104ESC) offered at Griffith
University (see [course
details](https://www.griffith.edu.au/study/courses/applied-bioinformatics-3030NSC)).
The tutorials cover basic bioinformatics skills taught in the course,
particularly those based on command-line tools and R (for example
retrieval of information and sequences from NCBI databases, multiple
sequence alignment and phylogeny inference, differential gene expression
analysis and visualisation in R using `DESeq2`, etc.).  
The teaching material for the workshops were developed by Dr. Alex
Cristion (<a.cristino@griffith.edu.au>) and Dr. Ido Bar
(<i.bar@griffith.edu.au>) and prepared as a
[Binder](https://mybinder.org/) repository.

The tutorial is designed to be run live and interactively in class
either locally on the students’ computers or using
[Binder](https://mybinder.org/) through Jupyter and RStudio servers (see
instructions below).

## Instructions

<!-- ### ![](README_files/figure-gfm/fa-icon-4e1ff21742f03e860864476dae02cf91.svg){height=1em width=1.13em} -->

### Jupyter

The Jupyter Notebook is an open source web application that you can use
to create and share documents that contain live code (supporting over 40
computing languages, including Python, R, Julia, Linux Bash and many
more), equations, visualizations, and text. Jupyter Notebook is
maintained by the people at Project Jupyter. You can learn more about
Jupyter Notebooks in the official
<a href="https://jupyter-notebook.readthedocs.io/en/stable/"
target="_blank">documentation</a> and in
<a href="https://realpython.com/jupyter-notebook-introduction/"
target="_blank">Jupyter Notebook: An Introduction</a> by Mark Driscoll

### R

R is a programming language and free software environment for
statistical computing and graphics supported by the R Foundation for
Statistical Computing. The R language is widely used among statisticians
and data miners for developing statistical software and data analysis.

### RStudio

RStudio is a set of integrated tools designed to help you be more
productive with R. It includes a console, syntax-highlighting editor
that supports direct code execution, and a variety of robust tools for
plotting, viewing history, debugging and managing your workspace. It
requires R to be installed prior to be able to send commands to the
interpreter.

### Using R and RStudio from Cloud services

If we want to keep things simple (for this course) or we would like to
use R on shared computers, where we can’t install software, we can run R
and Rstudio through a web client that is hosted on a remote server.  
We will use the
<a href="https://mybinder.org/" target="_blank">Binder</a> service,
which is free, easy to use and can be launched from a single GitHub
repository (more about this in the workshop).

#### Launching Binder

Using Binder is as simple as clicking on the Binder badge - <a
href="https://mybinder.org/v2/gh/IdoBar/3030NSC-workshops-binder/main"
target="_blank"><img src="http://mybinder.org/badge_logo.svg"
alt="Launch Binder" /></a> and choosing the appropriate server (Jupyter,
RStudio or Terminal).  
Alternatively, you can navigate to the
<a href="https://mybinder.org/" target="_blank">Binder</a> homepage and
enter the URL of this tutorial
<a href="https://github.com/IdoBar/3030NSC-workshops-binder.git"
target="_blank">GitHub repository</a>
`https://github.com/IdoBar/3030NSC-workshops-binder.git` and click on
the **launch** button (see screenshot in Figure 1 below).

<div class="figure" style="text-align: center">

<img src="https://github.com/IdoBar/6003ESC_workshops_binder/raw/main/figs/Screenshot_The_Binder_Project.png" alt="Figure  1: Binder launch screenshot." width="100%" />
<p class="caption">
Figure 1: Binder launch screenshot.
</p>

</div>

Now be patient while the environment is loading…  
You should now see in your web browser the Binder interface, where you
can choose the server to work with (Jupyter, Terminal or RStudio) and
you can start working in “The Cloud”! <img
src="README_files/figure-gfm/fa-icon-9e56b5ca2b62ac7e60ebed27cb682b8e.svg"
style="width:1.25em;height:1em" /><img
src="README_files/figure-gfm/fa-icon-9e56b5ca2b62ac7e60ebed27cb682b8e.svg"
style="width:1.25em;height:1em" /><img
src="README_files/figure-gfm/fa-icon-9e56b5ca2b62ac7e60ebed27cb682b8e.svg"
style="width:1.25em;height:1em" />

#### Downloading files from Binder

We can upload and download files to the Binder environment using the
file explorer on the left of the interface (use the <img
src="README_files/figure-gfm/fa-icon-bec7d79858c194ffd22334cf8751fe4d.svg"
style="width:1em;height:1em" /> button to upload files and right click
on a file/folder and select “Download” to download it, see screenshot in
Figure 2 below).

<div class="figure" style="text-align: center">

<img src="https://github.com/IdoBar/3030NSC-workshops-binder/raw/main/img/binder_main_menu.png" alt="Figure  2: Binder main screen and file access screenshot." width="75%" />
<p class="caption">
Figure 2: Binder main screen and file access screenshot.
</p>

</div>

If we are using RStudio, we can download any output files (summary
tables and figures) by using the `files` tab in RStudio (bottom right
pane).  
Select the files/folders that you would like to download and click on
<img
src="README_files/figure-gfm/fa-icon-53e5124836ad6f0251c100a082e4c38c.svg"
style="width:1em;height:1em" />More <img
src="README_files/figure-gfm/fa-icon-9c4b7891d944df9651aec42eb5d609d3.svg"
style="width:1em;height:1em" />Export… (see screenshot in Figure 3
below) to save the file on your computer.

<div class="figure" style="text-align: center">

<img src="https://github.com/IdoBar/6003ESC_workshops_binder/raw/main/figs/Rstudio_export_screenshot.png" alt="Figure  3: Download files from Binder/RStudio screenshot." width="75%" />
<p class="caption">
Figure 3: Download files from Binder/RStudio screenshot.
</p>

</div>

### Additional Information

For more details and instructions how to setup a similar repository,
please visit [From Zero to Binder in
R!](https://github.com/alan-turing-institute/the-turing-way/blob/master/workshops/boost-research-reproducibility-binder/workshop-presentations/zero-to-binder-r.md)
