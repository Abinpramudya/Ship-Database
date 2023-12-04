# Ship Database

This ship database project is a personal initiative born out of the frustration surrounding the difficulty in accessing a dependable centralized ship database. It aims to address the challenges faced by marine engineering students at the Faculty of Marine Technology of the Sepuluh Nopember Institute of Technology in Surabaya. By undertaking this pet project, my goal is to contribute, even if modestly, to the digitalization process within the Indonesian maritime industry.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Methods](#methods)
- [Progress](#progress)
- [Acknowledgements](#acknowledgements)

## About

This project comprises multiple steps focused on aggregating publicly available data on merchant ships and consolidating it in a centralized repository for ease of use. I predominantly employ Selenium to automate the extraction of essential data for the project. I envision this initiative as an initial stride towards leveraging machine learning and big data for the analysis of actively operating vessels. The ultimate goal is to facilitate comprehensive studies for students engaged in maritime science.


## Features

The key features i aim for this project are as follows:

- Centralized database
- Reliable database from reputable sources (ship classification society)
- Complete database

## methods

the methods i use are as follows:

1. **Data Collection from Vesselfinder:**
   - Collect IMO numbers for each vessel from https://www.vesselfinder.com/vessels.
   - Categorize the gathered IMO numbers based on ship types: general cargo, tanker, bulk carrier, container, and passenger vessels.

2. **Batch Processing of IMO Numbers:**
   - Divide the collected IMO numbers into multiple batches for separate processing.
   - Implement this batch approach to enhance efficiency, despite its heavier internet usage.

3. **Script Execution for IMO Search:**
   - Run distinct scripts to search for each IMO on various classification society websites.

4. **Data Extraction from Classification Society Websites:**
   - Identify matches between IMO numbers and vessels on classification society websites.
   - Extract necessary data, focusing initially on principal dimensions due to high demand.

5. **Organization of Ship Data:**
   - Systematically organize the accumulated ship data by type and class.
   - Store the organized data in folders for easy retrieval in subsequent stages.

6. **Database Refinement:**
   - Refine the early IMO database by cleaning out duplicates and ensuring accuracy.
   - Cross-reference the initial database with the already identified IMOs.

7. **Iterative Process:**
   - Repeat the entire process to gather additional data, refining and enhancing the ship database iteratively.


### Progress
### Project Status Update - October 2023

As of October 2023, this project has temporarily paused due to ongoing commitments on campus. However, I am committed to completing it before the next semester begins, recognizing its significance. One of the primary challenges encountered has been the creation of scripts for each class society. The diverse nature of their websites has added complexity to this task.

#### Completed:
- **CCS (China Classification Society)**
- **NK (Nippon Kaiji Kyokai)**
- **BV (Bureau Veritas)**

#### In Progress:
- **IRC (India)**
- **KR (Korea)**
- **LR (Lloyd Registry)**
- **DNV (Denmark)**

#### Halted:
- **ABS (Captcha issue)**
- **BKI (Database issue)**

The completed classes signify successful script development, while the ones in progress indicate ongoing efforts. Unfortunately, the ABS class faces a hurdle due to captcha-related issues, and BKI is currently on hold due to database-related challenges. I appreciate your understanding and am determined to overcome these obstacles for the successful continuation of the project.