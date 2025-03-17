# Noise Enhanced Students - Alpine Climate Data Challenge for TELT 2025

## Overview

Welcome to the repository of **Noise Enhanced Students**, 
the team that reached the **second place** of the **Alpine Climate Data Challenge**, 
with more than 140 students participating from around the world.
This repository contains the solution to the challenge. 


### Team Members: 
- **[Alessandro Catalano](https://www.linkedin.com/in/alessandro-catalano98/)**
- **[Gabriele Lo Cascio](https://www.linkedin.com/in/gabriele-locascio)**
- **[Gabriele La Milia](https://www.linkedin.com/in/gabrielelm/)** 

## Challenge Description

The challenge has a very specific goal: predict the climate 
impact on the territory of the Susa and Maurienne Valley. 
Specifically, the development of a custom Climate Model for predictions up to 2050.
The hybrid nature of this challenge allowed a multidisciplinary team, such as ours, 
to approach this task from different perspectives, from Physics (climate as a complex system) 
to Statistics and Data Science.

## Quick PDF Presentation
[Click to open](./resources/Alpine-Data-Challenge-Report-NES.pdf)

## Our Pitch At The Event

[Picth](https://www.linkedin.com/events/alpineclimatedatachallengeaward7305171727611838466/comments/) Jump to **2:38:34** for the key segment.


### Our Contributions

* A multidisciplinary team of physicist and engineers allowed for an exchange of expertise.
* We built a dataset considering the European area and historical period (1980-2024) consistent with the scientific literature about the Alpine climate change. 
* Alpine climate has been considered as a complex system. In this sense, much attention was paid to the spatial and temporal heterogeneity of the available data, in order to obtain accurate and representative estimatesand predictionsof the area. 
* Data analysis shows an increase in average monthly temperature from 1980 to 2024 in all regions (S, NW, NE). 
* An increasing maximum temperature trend in summer and minimum temperature trend in winter (in addition different altitudes have a significant impact on them). 
* A reduction in average monthly relative humidity and a shift in wind direction in the southern region from 1980 to 2024. 
* Our setup let us to choose latitude and longitude of Susa and Maurienne Valleys to make predictions, but also of any other given point in the map up to 2050, solving the task of the hackathon. 
* We built an interactive app to display the predictions made and to raise awareness of climate change among young people for educational and playful purposes


## Project Structure
- `dataset/`
  - `for-analysis-and-train`: clean and imputed csv files used for analysis and training.
  - `predictions`: csv files one for each Region/Location.
- `images/`: All of our plots
- `notebook/`
  - `NES.ipynb`: Contains the Jupyter Notebooks used during the competition.
  - `iowa_API.py`: Python code used to download data from IOWA State University.
- `references/`: Scientific papers used to gain knowledge.
- `resources/`: PDF Report (technical) and PDF Presentation (showcase)


