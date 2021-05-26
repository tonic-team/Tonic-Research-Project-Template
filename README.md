# Project description

## Abstract:

## Contributions :
Instead of writing contributors here, You may use the datacite file (.json if using gitlab, .yml if using GIN), or use a Tenzing spreadsheet https://marton-balazs-kovacs.github.io/tenzing/).

## list of experiments :

## Directl links (inside or outside this repository) :

- todo list: URL
- data management plan: [01_project_management/05_data_management_plans](01_project_management/05_data_management_plans)
- Smartfigure tag: URL


## Other information

`This repository follows the Research repository template, v.2.2`

---

You may erase these information, when you have your repository ready for use.

# how to use this template

## Origin

This project provides a template structure for research projects within the CRC/TRR 135 according to the results of a joint work with CRC 1158 and CRC 1315 (see https://genr.eu/wp/towards-a-standardized-research-folder-structure/) for details.

Check https://github.com/tonic-team/Tonic-Research-Project-Template if you want to use your own.



## Easier Collatoration

- Make sure every collaborator got to understand what files to find where.
- This template was meant to be used in a git based workflow. This would allow you to collaborate using issues and pull request. 
- The use of git submodule technology may help you share and publish only part of this repository. 

Refer to XXX for further information.


## Cheatsheets about what goes where:

- Prior to data acquisition: 
    - save all documents related to research planning in the 01-Project_management folder, and update material and methods information as soon as possible. For instance, indicate all information about reagents at the time or purchase. And put any code or variable files created for data acquisition in the 02_material_methods folder.

- Data acquisition and analysis: 
    - Data is organised first following experiments, make sure to describe every experiment in a readme file and link to the adequate files saved in 02_material_methods.
    - All files coming directly from your hardware should go in the rawdata folder.
    - Any file that you want to archive or publish should go in the derivateddata folder. This includes results from manual analysis of the raw data.
    - Any file created automatically during the analysis and that is easy to recreate should be saved in the processed_data folder: it will not be included in the long term storage or publication of the data.
    - The 04_data_analysis folder should only include code and documentation of the analysis. If you are using excel to analyse the data, put the files in the processed_data and only add some text describing the analysis in the analysis folder. If you are using notebooks in python or R for analysis, their place is here.
    - The output of your analysis (figures, and reproducible reports -pdfs-) should be saved in the 05_figures or the 06_disseminations/01_report_conferences/01_textreports folders, to facilitates sharing with non-coders.

- Manuscript preparation
    - Put figures ready for publication in the 05_figures/shared_figures folder
    - Put the manuscript (or some important versions of it, if using an external tool for writing it) in the 06_disseminations/02_manuscripts folder. You may want to use full URL to embed figures in the manuscript if the repository is open.
    



# How to create a new study

`note: We have some forks of this repository made for specific communities with additional information.`

## Github

Creating a new study project according to the tonic template is really easy: Just use the button `Use this template`, specify the owner, name and privacy and select button `Create repository from template`. Here we go!

## GIN, GOGS

Click the create new repository button on GIN, choose import repository and use `https://github.com/tonic-team/Tonic-Research-Project-Template` as the clone address

## Tonic

Yet to come !

# Notes
  
We have some forks of this repository made for specific communities with additional information.