# CME538-DEADLY-COLLISION-PROJECT

**OVERVIEW**

This repository contains the python coding that looks into exploring the potential intersection factors that increase the likelihood of a deadly or seriously injuring collision and use said research to find trends in such causes, as well explore potential models that can map out the probability of said collisions based on input feature characteristics. 

The project contains aspects of pulling, building and cleaning the data, performing visual and data analysis on it, and finally machine learning to explore the potential concept of ML providing the safety of an intersection based on its characteristics.

**CONTENTS**

This readme details the work of the team and serves as a guide on how to navigate through the repository. The repository’s contents are as follows:

  1. Motor Collisions and Traffic Volumes Data Pipeline.ipynb: This details the process form pulling the data to creating the master               dataframe that has every single detail on every collision that occurred in Toronto from 2011 to 2022. Features of this data include           characteristics of the crash, the intersection, and the traffic of the intersection at the time of the crash.
  2. Finding r for intersections: This details how the r value for each intersection was calculated. The r value is a statistical value that       labels the safety of an intersection from collisions, with 0.1 being a low risk and 0.9 being high. 1.6 and above labels the                  intersection as dangerous.
  3. Raw Data Files: This directory contains 3 files that can be downloaded and explored. These were used to create some visuals. The files         are as follows:
    3.1. locations.csv: details intersection, name, and location.
    3.2. toronto_districts.jpg: image file of the different districts of Toronto.
    3.3. toronto_wards_25.png: image file of different wards of Toronto.
  4. Output_csvs: This directory contains 3 files that are produced from the code, such as the data pipeline and finding r for intersections.      They are as follows:
    4.1. master_gdf.csv: This contains the CSV output that combines collision data with traffic data.
    4.2. master_att_gdf.csv: like master_gdf but with intersection attributes appended to it.
    4.3. intersection_r.csv: output of calculating r for each intersection.
  5. Machine Learning: Details the machine learning done for this project. This contains two files as follows:
    5.1. Machine Learning on Collisions.ipnyb: Details the notebook on how the ML was built and used to explore different sets of                      features, providing both CV results and train-test results.
    5.2. Machine Learning on Collisions.html: The html version of the notebook. It can be opened in a browser to view without a notebook.
  6. Data Analysis: Details the EDA work done on this project, which contains visuals and other data analysis performed on various aspects of      problem, as detailed below:

  6.1. Intersection Characteristics Analysis of master_gdf.ipnyb: This explores the characteristics of each intersection that had a                  collision occur, and how it could have potentially impacted the collision, such as traffic control.
      
  6.2. Intersection Characteristics Analysis of master_gdf.html: The html version of the notebook, capable of being viewed in any web                browser.
    
    
  6.3. Spatial Analysis of master_gdf.ipnyb: Explores the spatial characteristics of each intersection that had a collision, and how it              may have impacted the collision itself. This takes into consideration more geometric attributes.
    
    
  6.4. Spatial Analysis of master_gdf.html: The html version of the notebook, capable of being viewed in any web browser.
    
    
  6.5. Temporal Analysis of master_gdf.ipnyb: Explores the temporal characteristics of each intersection that had a collision, and how it            may have impacted the collision itself. This takes into consideration more datetime attributes and elements impacting collisions              that are subject to time, like weather conditions and seasonality.
    
    
  6.6. Temporal Analysis of master_gdf.html: The html version of the notebook, capable of being viewed in any web browser.
