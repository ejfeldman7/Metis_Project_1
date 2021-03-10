# Metis Project 1: Exploratory Data Analysis of MTA turnstyle data
### Project completed by Tawney Lott, Rhys Carter, Alla Raykhman, and Ethan Feldman

Guide for contents of the repository:

1. Jupyter Notebooks Folder(.ipnyb)  
  mta_ridership_EF = Cleaning notebook for MTA data. Cleaning, sorting, visuals   
  mta_ridership_EF_TL = Cleaning notebook for MTA using new method for importing  
  census_data_cleaning_demogs = Notebook for cleaning, aggregating, and visualizing census data  
  visualizing_notebook = Notebook intended for creating visuals  
 
2. SVG Folder  
3. Archived Stuff Folder  
  Files we probably don't need but haven't decided to delete for sure yet  
4. Slide Deck  
  MTA_Project 1_Team 2_2021008.pdf

## Overview

In this project, our team analyzed MTA turnstile data on behalf of the fictional company WomenTechWomenYes to provide recommendations for placement of street teams in New York City that would improve awareness of their company, drive donations, and increase attendence to their upcoming Gala. 

## Data

Along with the turnstile data made publicly available by the MTA, we incorportated US Census Bureau data from the American Community Survey for demographic information. Both sets of data were loaded from their CSV format into pandas to be clean, sorted, and analyzed. Our team focused on the metric of overall flow, which we defined as the total number of people entering and exiting turnstiles at a particular station in a four hour period, to consider which stations might be the busiest. 

## Analysis

In the MTA train system, the top 50 or so stations make up about half of the overall traffic. That means that there are a large number of stations to consider as sufficiently busy but also many stations, about 300, which will be markedly less busy and are best avoided. Overall, we found that stations generally fell into one of three main categories that we encourage thinking of in a Goldilocks methodology. There are stations which are too busy, too slow, and just right. The too busy stations were not just identified as outliers, but far beyond the other outliers in the dataset. These stations, we posit, will be so busy that it will be challenging to connect with people passing by and a team will be easily lost in passing traffic. Similarly, those 300 or so slower stations will not likely have enough foot traffic to provide the needed population for our teams to generate support. 

Amongst the "just right" set of stations, our goal was to then further filter our recommendations down along a few metrics. To increase awareness broadly in New York, we wanted to idenfity stations from Manhattan, Brooklyn, Queens, and the Bronx. Furthermore, we wanted to cross reference these busy stations with demographics about income (for donations) and information technology employment (for interest and awareness). In Manhattan and Brooklyn, our stations are higher on both metrics, so we believe these stations will find people more likely to donate and more aware of the struggle of representation in technology for women. In Queens and The Bronx, our stations are lower on both metrics, which we believe will help spread awareness to women who may not have been considering a career in technlogy previously. In this multifaceted approach, we believe WTWY can achieve excellent attendance, increase donations, and reach out to the women that they hope to support and inspire.
