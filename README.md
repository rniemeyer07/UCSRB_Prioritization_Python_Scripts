# UCSRB_Prioritization_Python_Scripts

<img src="https://storage.googleapis.com/ff-storage-p01/festivals/logos/000/051/750/large/logo.jpg?1575572027" width="200">

## Overview
Scripts and data tables within this repository are for Step 2 of the [UCSRB Habitat Prioritization process](https://www.ucsrb.org/prioritization/). I will endeavor to update the data available on this page, however the most up-to-date results for Step 2 can be found on the [Prioritization Products Page](https://www.ucsrb.org/prioritization-products/).

## Reach and Action Prioritization
The RTT decided to use three pathways to develop prioritized reaches and actions: Habitat Quality pathway, Limiting Factors pathway, and fish passage pathway.  This python tool deals primarily with the Habitat Quality and Limiting Factors pathway.  The filters and criteria for filters (as of October 14th, 2020) are overviewd in this [google slides presentation](https://docs.google.com/presentation/d/1dEJ-A_LlW1HkxfIjOfLmjRxS1DRR_nWGOsBlZj5khss/edit?usp=sharing). 

## Python Scripts
This python code is written with jupyter ipython notebooks, which make the code easier to understand and track.  For an overview how to install python and Anaconda (required for jupyter noteboks), [this page](https://www.codecademy.com/articles/how-to-use-ipython) overviews the process. Currently, you will need to download the [Prioritization Tool Excel spreadsheet](https://www.ucsrb.org/?mdocs-file=6877%20) to run the python script. In the future, I plan to upload these data to this repository, so one person merely needs to download the ipython notebooks and the data will be pulled from this GitHub repository when the ipython notebooks are executed.

## Final Note
Note - some of the data or scripts in this repository are draft versions. As of October 14th, 2020, the three scripts used to generate the priority Action Categories are the [Habitat Quality Prioritization Output script](https://github.com/rniemeyer07/UCSRB_Prioritization_Python_Scripts/blob/master/Habitat_Quality_Prioritization_Output.ipynb) for the Habitat Quality Pathway, the [Limiting Factors Output script](https://github.com/rniemeyer07/UCSRB_Prioritization_Python_Scripts/blob/master/Limiting_Factors_Output.ipynb) for the Limiting Factors Pathway, and finally the [Habitat Attribute and Reach Assessment Projects Croswalk script](https://github.com/rniemeyer07/UCSRB_Prioritization_Python_Scripts/blob/master/Habitat_Attribute_and_Reach_Assessment_Projects_Crosswalk.ipynb) that generate priority action categories based on the priority reaches output from the Habitat Quality and Limiting Factor pathway output. If you have any questions, please feel to reach out to me at ryan.niemeyer@ucsrb.org.
