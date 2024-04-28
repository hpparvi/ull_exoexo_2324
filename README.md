# Exoplanetas y Exobiologia 2023-2024</br>

**[Dr. Hannu Parviainen](mailto:hannu@iac.es)**</br>
**[Universidad de la Laguna](https://www.ull.es)**</br>
**Last modified: 28.4.2024**

## Introduction

This git repository contains the lab exercises to the ULL Exoplanetas y Exobiologia course
2023-2024. The exercises will teach you the basics of how to 

- estimate the orbital period of an exoplanet together with its minimum mass from a radial 
  velocity signal,
- estimate the exoplanet's radius and orbital properties from a transit light curve.

The exercises will also introduce you to some of the common tools used in astronomy and 
astrophysics, such as [git](https://git-scm.com), [Python](https://www.python.org/), 
and [Jupyter notebooks](https://jupyter.org/).

## Prerequisites

You need a working Python environment with Jupyter, and you need to install PyTransit 

    pip install pytransit 

Also, a basic understanding of version control (and especially Git) is very useful. At minimum, 
you should read Pro Git Book sections [1.1](https://git-scm.com/book/en/v2/Getting-Started-About-Version-Control), 
[1.3](https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F), 
and [2.1](https://git-scm.com/book/en/v2/Git-Basics-Getting-a-Git-Repository), and maybe also watch the
[four videos describing the basics of version control and Git](https://git-scm.com/videos). 

## Setting up Git

First, you'll need to create a GitHub account and fork the lab exercise repository into your own account. Next, 
you'll need to clone the lab exercise repository from your account in GitHub to your own computer

    git clone https://github.com/YOUR_GITHUB_USERNAME/ull_exoexo_2324.git

## Exercises

The exercises have been organised into two Jupyter notebooks. You'll need to start a Jupyter notebook
server from the directory you cloned the repo into

    cd ull_exoexo_2324
    jupyter notebook

After which you can open, edit, and run the notebooks.

## Returning the exercises

Commit the changes in git, push the edited notebooks to your own fork in GitHub, and write to me that you're finished.
