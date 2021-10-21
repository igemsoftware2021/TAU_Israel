# Communique iGEM TAU Israel
Communique iGEM TAU 2021 repository

![Alt text](/logo.png?raw=true)

Welcome to Communique, iGEM TAU 2021!
This is our official github repository for the iGEM 2021 competition. 
Our goal was to create a software tool to tailor create a microbiome‫-‬specific version of any genetic information
In order to download our tool, you may download the communique_instal.tar file and follow the user guide to import our
docker image. 

The source code is organized as following- 
1. All front-end design is in the GUI directory, and built using flask
2. Backend development is divided into different modules as specified in our website
3. Model analysis files: used to test our software on real metagenomic data

for any additional information:
Email: igem.tau.21@gmail.com
Website: https://2021.igem.org/Team:TAU_Israel/


## Quick installation guide
Step 1: pull docker image
docker pull igemtau21/communique

Step 2: run the image
docker run -p 5000:5000 igemtau21/communique python main.py

***Recommended installation: dowload and untar the 'communique_install.tar' file, and follow the supplied user guide 



## Credits

Our source code is available at: https://github.com/leviliyam/Igem_TAU_2021

***Enable***
Free Chrome plugin: https://www.enable.co.il/tos/

***Python 3.9 Docker image***
Python official free Docker image: https://hub.docker.com/_/python

***MEME Suite***
Motif finder tool: https://meme-suite.org/meme/
Authors: Timothy L. Bailey, William Noble
Copyright (c) 1994-2019 The Regents of the University of California. All Rights Reserved.

********************************
