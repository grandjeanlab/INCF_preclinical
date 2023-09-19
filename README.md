# INCF_preclinical
Code examples for the Practical guide to overcome the reproducibility crisis in small animal neuroimaging: workflows, tools, and repositories

Practical guide to overcome the reproducibility crisis in small animal neuroimaging: workflows, tools, and repositories
Chairs: Markus Aswendt, Joanes Grandjean
Location: Presentation Room 1

The workshop will include interactive seminars given by selected experts in the field covering all aspects of (FAIR) small animal MRI data acquisition, analysis, and sharing. The seminars will be followed by hands-on training where participants will perform use case scenarios using software established by the organizers. This will include an introduction to the basics of using command line interfaces, Python installation, working with Docker/Singularity containers, Datalad/Git, and BIDS.

## **Preparation:**
Questionnaire for the participants [Link to Google Form](https://docs.google.com/forms/d/1B4A9OPNnT2vR1jL2VJwJq_N-pvJnb6zPesnXQ8W4p5s/edit)

<details>
<summary>Install software</summary>

1. Software   
1.1 [Anaconda](https://www.anaconda.com/download)   
1.2 [Jupyter Notebook](https://jupyter.org/install)     
1.3 [Datalad](https://handbook.datalad.org/en/latest/intro/installation.html)    
1.4 [GIN client](https://gin.g-node.org/G-Node/Info/wiki/GIN+CLI+Setup)   
1.5 [Docker](https://docs.docker.com/get-docker/)   

2. MRI tools   
2.1 [ITK-SNAP](http://www.itksnap.org/pmwiki/pmwiki.php)   
2.2 [Brkraw](https://brkraw.github.io/docs/gs_inst.html)   
2.3 Clone latest AIDAmri (Docker) version from https://github.com/Aswendt-Lab/AIDAmri   
2.2 RABIES installation (Docker) pull from Docker hub 
https://hub.docker.com/r/gabdesgreg/rabies selecting tag number 0.4.8
</details>

<details>
<summary>Participating to the RABIES hands-on demo</summary>

There will be a hands-on demonstration of the RABIES software broadcasted during the workshop. It will be possible to follow along from your computer if you install the prerequesites. The following will be required:
* [Jupyter Notebook](https://jupyter.org/install) (to open notebooks)
* [Docker](https://docs.docker.com/get-docker/), and pulling RABIES version 0.4.8 with `docker pull gabdesgreg/rabies:0.4.8` (make sure to have ~10Gb of free space)
* Download this github repository; the required notebooks and files are all include in the rabies/ folder. You can download the repo manually by clicking on "code -> download ZIP", or from a terminal using git with `git clone https://github.com/grandjeanlab/INCF_preclinical`.

</details>

## **Schedule:**   
*Welcome:* Markus/Joanes

*SEMINAR 1 (20 min):*  Markus/Aref -- How to set up a FAIR workflow for multimodal rodent imaging data in a no-code environment of a translational stroke lab. [Slides](https://github.com/grandjeanlab/INCF_preclinical/blob/main/presentations/INCF_Workshop_2023_v2_Seminar1_GitHub.pdf)

*SEMINAR 2 (25 min):*  Michał -- An introduction to version control, Git, DataLad  

*SEMINAR 3 (15 min):* Joanes -- Working with robust data structure (BIDS) and containers (Docker / Apptainer)  

*HANDS-ON 1 (1 h):* Michał (Aref, Markus) -- Data Management for Neuroimaging with DataLad   
 
*HANDS-ON 2 (2 hrs):* Two breakout rooms:    
Breakout room (carpet) 1: Markus/Aref -- Application of image post-processing pipeline AIDAmri. [Slides](https://github.com/grandjeanlab/INCF_preclinical/blob/main/presentations/INCF_Workshop_2023_v2_Handson2_GitHub.pdf) 
([**Link to GitHub AIDAmri**](https://github.com/Aswendt-Lab/AIDAmri/blob/workshop/AIDAmri_workshop.ipynb))   
Breakout room (carpet) 2: Gabriel/Joanes -- Rodent functional MRI preprocessing with RABIES. ([**Link to GitHub RABIES**](https://github.com/CoBrALab/RABIES))


