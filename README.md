# Exoplanetas y Exobiologia 2021-2022</br>

**[Dr. Hannu Parviainen](mailto:hannu@iac.es)**</br>
**[Universidad de la Laguna](https://www.ull.es)**</br>
**Last modified: 22.4.2022**

## Introduction

This git repository contains the lab exercises to the ULL Exoplanetas y Exobiologia course
2021-2022. The exercises will teach you the basics of how to 

- estimate the orbital period of an exoplanet together with its minimum planetary from a radial 
  velocity signal,
- estimate the exoplanet's radius and orbital properties from a transit light curve.

The exercises will also introduce you to some of the common tools used in astronomy and 
astrophysics, such as [git](https://git-scm.com), [Python](https://www.python.org/), 
and [Jupyter notebooks](https://jupyter.org/).

## Prerequisites

You'll need to install PyTransit 

    pip install pytransit 

And you may still need to install some additional packages required by PyTransit.

## Setting up Git

First, you'll need to create a GitHub account (if you don't have one already) and email it to me  so that I can
add you to the repo as a collaborator. Next, you'll need to clone the lab exercise repository from GitHub

    git clone https://github.com/hpparvi/ull_exoexo_2021.git

After which you can create your own git branch and do an initial push back to GitHub

    cd ull_exoexo_2021
    git branch aluxxxxxxxxxx
    git checkout aluxxxxxxxxxx
    git push --set-upstream origin aluxxxxxxxxxx

where `aluxxxxxxxxxx` is your student id.

## Exercises

The exercises have been organised into two Jupyter notebooks. You'll need to start a Jupyter notebook
server from the directory you cloned the repo into

    cd ull_exoexo_2021
    jupyter notebook

After which you can open, edit, and run the notebooks.