![Alt text](/logo.png?raw=true "Title")

>Welcome to Communique, iGEM TAU 2021!
>This is our official github repository for the iGEM 2021 competition. 


Bacteria are one of the most ubiquitous organisms on earth, present in both natural and synthetic communities called microbiomes.
They constantly share genetic information in a process called _lateral gene transfer_, which prevents us from being able to engineer specific members of the community.

Using our software, you can take your gene of intrest along with two subpopulations:
- **Optimized organisms**: the bacteria that should be able to express the genetic modification optimally.
- **Deoptimized organisms**: the bacteria that *should not* be able to express the genetic modification.


And create a **microbiome‫-‬specific version** of any genetic modification- generically and automatically. 

![Alt text](/illustration.png?raw=true "Title")


for any additional information:

Email: igem.tau.21@gmail.com

Website: https://2021.igem.org/Team:TAU_Israel/




## Quick installation guide
### Step 1 
Pull docker image: `docker pull igemtau21/communique`

### Step 2 
Run the image: `docker run -p 5000:5000 igemtau21/communique python main.py`


#### Recommended installation: dowload and un-tar the 'communique_install.tar' file, and follow the supplied user guide 




## Code
The source code is organized as following- 
1. All front-end design is in the GUI directory, and built using flask
2. Backend development is divided into different modules as specified in our website
3. Model analysis files: used to test our software on real metagenomic data




## Credits
Our source code is available at: https://github.com/leviliyam/Igem_TAU_2021

### Enable
Free Chrome plugin: https://www.enable.co.il/tos/

### Python 3.9 Docker image
Python official free Docker image: https://hub.docker.com/_/python

### MEME Suite
Motif finder tool: https://meme-suite.org/meme/
Authors: Timothy L. Bailey, William Noble
Copyright (c) 1994-2019 The Regents of the University of California. All Rights Reserved.
