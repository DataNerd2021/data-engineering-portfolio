# Data Engineering Project Portfolio

## Project History
- ### Spring 2023 (January 2023 - April 2023): **Spotify Playlist Song Recommendation Web App (Team Project)**

  **Description:** 
  
  This is an end-to-end Data Science Project that consisted of four primary disciplines: Data Science, Data Engineering, Software Engineering, and Data Analytics. The primary objective of this project is to build a web app that allows users to either import a playlist from Spotify's API, choose a pre-loaded playlist as stored in a back-end OLAP daatabase, or create a custom playlist using songs stored in the OLAP database. For this project, I led the Data Engineering team and was responsible for the following tasks:
  1. Create OLTP Database to Store the Raw Data Extracted from Spotify.
  2. Create a Data Mining Process to Gather Nearly 400,000 Playlists.
  3. Create an ETL Pipeline to Extract the Following Items (Figure 1 below):
  
            a. All Songs in Each Playlist
    
            b. Artists for Every Distinct Song
    
            c. Audio Features for Every Distinct Song (for use in recommendation model)
  5. Create an OLAP Data Model using dbt (Figure 2 below).
  6. Create Unit Tests to Verify Referential Integrity and Remove Duplicates.
  7. Develop Semantic Layer to Clearly Define Metrics (Figure 3 below)
 
 
 Figure 1:
 
 ![Figure 1](https://github.com/DataNerd2021/data-engineering-portfolio/blob/main/OLTP%20Pipeline.jpg)
 
 Figure 2:
 
 ![Figure 2](https://github.com/DataNerd2021/data-engineering-portfolio/blob/main/dbt%20Data%20Model.jpg)
 
 Figure 3:
 
 ![Figure 3](https://github.com/DataNerd2021/data-engineering-portfolio/blob/main/dbt%20Semantic%20Layer.jpg)
