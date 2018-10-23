# Women in OMSCS Analysis - README

## Installation
The code contained in this repository was written entirely in R (R Markdown) and requires the following libraries: plyr, tools, ggplot2 and psych.

## Project Overview
In this project, I conducted research into the general phenomenon of the lack of women in computer science, through investigating the more specific phenomenon of the lack of women in Georgia Tech’s Online Master of Science in Computer Science (OMSCS) program. 

To do this, I conducted analysis to investigate the differences that exist between female OMSCS students and their male counterparts, with the expectation that, through gaining a greater understanding of the gender differences that exist among OMSCS students, it would be possible to gain insight into any factors that may be discouraging women from entering/completing the program and to propose several initiatives that could potentially be used to increase female participation in the OMSCS.

In performing this analysis, I set out to answer the following research questions:
1. What demographic differences exist between male and female OMSCS students?
2. How do male and female OMSCS students differ with regard to academic performance and behavior within the OMSCS (e.g. course selection, hours spent studying, etc)?
3. Is there a significant difference between male and female OMSCS students with regard to their sense of belonging in the OMSCS program and computer culture in general?
4. What differences exist between the pre-OMSCS computing experiences of male and female OMSCS students?
5. Does a confidence gap exist between male and female OMSCS students?

## File Descriptions
All analysis is contained in the following R Markdown files saved in the Analysis folder:
- **combined_analysis.RMD**: combined analysis of all course survey data;
- **kbai_analysis.RMD**: analysis of KBAI course survey and grade data alone;
- **edutech_analysis.RMD**: analysis of EduTech course survey and grade data alone;
- **hci_analysis.RMD**: analysis of HCI course survey and grade data alone; and
- **survey_analysis.RMD**: analysis of supplementary survey data.

For confidentiality reasons, the data required to run these files has not been included in this repository. However, the output generated from running these files has been included in the form of pdf files (also in the Analysis folder) with the same file names as those listed above.

A complete list of all questions asked as part of the supplementary survey is contained in **Survey Questions.pdf**.

## Results
The main findings of this analysis are summarised briefly in a blog post available [here](https://medium.com/@gkhayes/where-are-the-women-in-georgia-techs-omscs-53f16153dfc5), and in greater detail in a paper included in this repository in **OMSCS Gender Gap.pdf** ([here](https://github.com/gkhayes/women_in_omscs/blob/master/OMSCS%20Gender%20Gap.pdf)).

## Licensing, Authors, Acknowledgements
This analysis was completed as my final project for the Spring 2017 offering of [CS6460 Educational Technology](http://omscs6460.gatech.edu/), as part of the OMSCS program. The grade and course survey data used in this analysis was collected by Dr David Joyner between Summer 2015 and Fall 2016, while the supplementary survey data was collected by me via a survey of self-selected, past and present OMSCS students, conducted online between March 23, 2017 and April 14, 2017.

The code contained in this repository may be used freely with acknowledgement.
