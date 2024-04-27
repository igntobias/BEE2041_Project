# BEE2041_Project
End of Term Empirical Project



#About the Project

This project is a data processing assignment where webscraping will be used to obtain data from the internet. At this stage, I will try to gather information of interest and play around with the data. The structure of the repository is simple, a readme file, any potential datafiles/zip files that (may) be used or downloaded for this project, as well as the ipynb/jupyter notebook file. The end product is a published blog.

The topic of this project is to scrape data about the video game, Genshin Impact. This repository records all the codes used to scrape data about the game and its analysis. The idea is to investigate whether character upgrades become powerful over time, if newer characters are much stronger than older ones. Genshin Impact is a "gacha game," meaning characters are obtained through a loot crate (random luck) system. Multiple copies of the character will unlock upgrades that make the character stronger and a maximum of 6 extra copies of a character are obtainable. Copies are called "constellations" and may provide the character with new buffs, abilities, or in-game stats. 

Thus, The aim of this research is to try and scrape data from public fan sites and analyse the descriptions. The code will be scraping from a total of two websites, one to obtain release dates and one to obtain the character names, IDs, and constellation descriptions. To the best of my knowledge, these two sites do not have any ToS that prohibits web scraping. If this changes, then these sites have updated their terms of service or other changes have occurred since the creation of this project.



#Disclaimers
This readme is for the BEE2041_Project repository (open to the public on GitHub) and explains the structure of the repo. Another readme is provided for any zip files for any submission of the work (refer to the STUDENTNUMBER zip file submission).

As of the creation of this code, there are 85 playable characters in the game. Should any errors occur in the web scraping, then it is likely that a new character has been released with statistics (names, dates, or otherwise) that does not fit in properly with the web scraper. It is also likely that any of the sites used for the scrape may have changed elements in the source code or the site no longer exists. For that reason, please read the instructions section carefully to fully access the analyses done on this source code.



#Repository Contents

Submission Format:
	The output for the project is a published blog, so please open "blogs.txt" and open the appropriate link to the Wordpress site.
	Please notify if any of the links/contents is inaccessible for any reason.

Source Code and Main Working Directory:
	The source code for all web scraping, data processing, and graphing is located in the "BEE_2041_Project_File_Main" ipynb file. 
	This file is a simple Jupyter Notebook file.

About troubleshooting and version control:
	There are various branches for the project, but the completed work is available on the main branch. Feel free to inspect any previous versions from any of the initial three branches.
	An alternative to opening branches or previous versions would be opening either the ".ipynb_checkpoints" or "Test_files" directory 

Stored data and content:
	All important data files (df1.csv) is contained inside the "Data_files" directory.
	This directory is also where any of the visuals would be saved by default.




#Instructions (IMPORTANT)

For any Users or Examiners to run the source code:
	It is important that any of the web scraping code should not be run continuously or used to attack any of the sites.
	Some sites used in this project may prefer to limit web scraping content due to high web-scraping loads or performance issues.
	Thus, please utilise the already made csv files contained within the "Data_files" directory.
	The source code has already provided instructions within comments to show which steps to take to skip the web scraping.
	Should you skip the web scraping, you can treat the data processing as a simple analysis of a csv/dataframe.

Ensure that all functions/lines involving downloading data have been adjusted to read or download into the desired path/directories: 
	This is mostly the case for the visuals and reading the appropriate csv files.

In the case of errors in the web scraping:
	This may happen if the source code of the sites have changed since the creation of this repository.
	Troubleshooting will need to be done in order to download and extract the appropriate data.
	However, any scraping errors should not result in any problems with the analysis itself.
	Use data from the already-made snapshot of the web scrape data (df1.csv in Data_files).

Another potential error may appear is in the "Scraping Names and Dates from g8" section of "Data Scraping and Pre-Processing." Any errors appearing here is likely due to the built-in pandas data frame web scraper picking up the incorrect data frame, thus leading to format or Type errors. In order to resolve this, please follow the steps in the markdown/comments of the source code.
	If the aim is to replicate the results from the blog, please use the "df1.csv" in the Data_files directory.
