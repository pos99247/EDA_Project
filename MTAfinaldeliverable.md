# How to efficiently promote the next Redbull

---

Brian Nam

## Abstract

---

Coca-Cola wanted to promote their new energy drink. Stations with the highest traffic were chosen to be a camp for their advertising campaign. We were able to find that weekdays were busier than weekends. We are also able to find that on any given day on average 12:00 to 18:00 was the busiest and 06:00 to 12:00 was the second busiest. Some stations were located very close to universities which provided an incentive for Coca-Cola to spend more resources than other stations. Utilizing the data we concluded that Coca-Cola should prioritize the stations in the order of 34 ST-PENN ST, GRD CNTRL-42 ST, 34 ST-Herald SQ, 23 St, TIMES SQ-42, 42ST-PORT AUTH, 14 ST-UNION SQ, FULTON ST, 125 ST, and CANAL ST. However, GRD CNTRL-42 ST, 14 ST-UNION SQ and 125 ST will come before other stations due to their unique location of being close to a college or university.


## Design

---

The goal of this project was to use the MTA turnstile data to find when where would be the most appropriate place to promote the new energy drink by Coca-Cola. Coca-Cola wanted to first advertise the drink in manhattan and their target audience is students. We chose to use the data provided by the MTA to calculate the traffic of stations in order to send out promoters to the busiest stations in manhattan. So that Coca-Cola would receive the most exposure in a limited time frame.

## Data

---

The data set selected is the MTA turnstile data from 2018-05-26 to 2018-08-24. The data was chosen from a pre-covid time so that we could accurately calculate traffic in the subway when things were normal. The data was chosen during summer when the city is the hottest. The dataset contains unique turnstiles, stations, dates, and hours.

## Algorithms

---

**Exploratory Data Analysis**
- Turnstile entries were culmulative values -> Each entry was substracted from the previous entry to calculate actual entry
- Null values created in the process was eliminated.
- Reversed data was corrected.
- Negative entries were corrected.

## Tools

---

- SQL for data extraction, storage
- Windows Powershell for combining data
- Numpy and Pandas for data manipulation
- Matplotlib and Seaborn for visualization and plotting

## Communication

---

Slides have been attached for the presentation.