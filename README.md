# Capstone Project - Brick - Market Expansion Research
### Introduction
For this project, I am assuming the role of data analyst, producing insights for the leadership team of Brick LLC to serve as the basis for a proposed marketing campaign directed at students. This repository examines the relationship between students' social media usage and their academic performance, mental health, and relationships to uncover how social media impacts various aspects of a student's life. Enriched with country population, GDP per capita and internet use data, the intended outcome is to identify potential target markets, what pain points to message, and where to pilot Brick’s solution.

### Google Colab
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/lschuler-dotcom/capstone_project/blob/main/notebooks/capstone_project.ipynb)

### Datasets
**Sources:**

[Social Media Kaggle](https://www.kaggle.com/datasets/mahdimashayekhi/social-media-vs-productivity) -- [Population World Bank Group](https://data.worldbank.org/indicator/SP.POP.TOTL) -- [GDP World Bank Group](https://data.worldbank.org/indicator/NY.GDP.PCAP.CD) -- [IT User World Bank Group](https://data.worldbank.org/indicator/IT.NET.USER.ZS)

<br>The `social_media_vs_productivity.csv` dataset contains:

| Variable                       | Type        | Description                                                 |
| ------------------------------ | ----------- | ----------------------------------------------------------- |
| `student_id`                   | Integer     | Unique respondent identifier                                |
| `age`                          | Integer     | Age in years                                                |
| `gender`                       | String      | “Male” or “Female”                                          |
| `academic_level`               | String      | High School / Undergraduate / Graduate                      |
| `country`                      | String      | Country of residence                                        |
| `avg_daily_usage_hours`        | Float       | Average hours per day spent on social media                 |
| `most_used_platform`           | String      | Instagram, Facebook, TikTok, etc.                           |
| `affects_academic_performance` | Boolean     | Self-reported impact on academics (Yes/No)                  |
| `sleep_hours_per_night`        | Float       | Average nightly sleep hours                                 |
| `mental_health_score`          | Integer     | Self-rated mental health (1 = poor to 10 = excellent)       |
| `relationship_status`          | String      | Single / In Relationship / Complicated                      |
| `conflicts_over_social_media`  | Integer     | Number of relationship conflicts attributed to social media |
| `addicted_score`               | Integer     | Social Media Addiction score (1 = low to 10 = high)         |

Note: For the following datasets, the "Years 1960 - 2024" column in the table is summarising the separate columns in the dataset from 1960 to 2024 - grouped for table simplicity.

<br>The `wbg_%tech_users.csv` dataset contains:
| Variable                       | Type        | Description                                                 |
| ------------------------------ | ----------- | ----------------------------------------------------------- |
| `Country Name`                 | String      | Name of country                                             |
| `Country Code`                 | String      | Unique country code                                         |
| `Indicator Name`               | String      | Data set name - variable being tracked                      |
| `Indicator Code`               | String      | Dataset identifiable code                                   |
| `Years 1960 - 2024`            | Percent     | Percent of population using the Internet                    |

Note: Data from 2024 is not complete

<br>The `wbg_gdp.csv` dataset contains:
| Variable                       | Type        | Description                                                 |
| ------------------------------ | ----------- | ----------------------------------------------------------- |
| `Country Name`                 | String      | Name of country                                             |
| `Country Code`                 | String      | Unique country code                                         |
| `Indicator Name`               | String      | Data set name - variable being tracked                      |
| `Indicator Code`               | String      | Dataset identifiable code                                   |
| `Years 1960 - 2024`            | Float       | GDP per capita in US$                                       |


<br>The `wbg_population.csv` dataset contains:
| Variable                       | Type        | Description                                                 |
| ------------------------------ | ----------- | ----------------------------------------------------------- |
| `Country Name`                 | String      | Name of country                                             |
| `Country Code`                 | String      | Unique country code                                         |
| `Indicator Name`               | String      | Data set name - variable being tracked                      |
| `Indicator Code`               | String      | Dataset identifiable code                                   |
| `Years 1960 - 2024`            | Integer     | Total population figure                                     |

