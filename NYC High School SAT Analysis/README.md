# NYC Public Schools SAT Performance Analysis


## Project Overview

This project is part of Associate Data Scienctist Track by Datacamp. In this project, I analyzed SAT performance data from New York City public schools to uncover key insights about educational achievement across the five boroughs. Using Python and pandas, I explored which schools excel in mathematics, identified top-performing institutions, and examined variability in test scores across different regions.

## Dataset

For my analysis, I used `schools.csv`, which contains SAT performance data for NYC public schools with the following features:

- **school_name**: Name of the high school
- **borough**: NYC borough (Manhattan, Brooklyn, Queens, Bronx, Staten Island)
- **building_code**: Unique building identifier
- **average_math**: Average SAT math score (max 800)
- **average_reading**: Average SAT reading score (max 800)
- **average_writing**: Average SAT writing score (max 800)
- **percent_tested**: Percentage of students tested

## Research Questions

### 1. Which NYC schools have the best math results?

**Criteria**: I identified schools with average math scores of at least 640 (80% of maximum 800 points)

**Key Findings**:
- **Stuyvesant High School** leads with an exceptional math score of **754**
- **Bronx High School of Science** and **Staten Island Technical High School** follow with scores of 714 and 711 respectively
- I found 10 schools that met the criteria, demonstrating excellence in mathematics education

### 2. What are the top 10 performing schools based on combined SAT scores?

**Methodology**: I created a `total_SAT` metric by summing math, reading, and writing scores

**Top 3 Schools**:
1. **Stuyvesant High School** - 2,144 points
2. **Bronx High School of Science** - 2,041 points
3. **Staten Island Technical High School** - 2,041 points

**Insight**: I discovered that specialized science and technology high schools dominate the top rankings, highlighting the strength of NYC's specialized school system.

### 3. Which borough has the largest standard deviation in combined SAT scores?

**Answer**: **Manhattan**

**Statistics**:
- **Number of Schools**: 89
- **Average SAT Score**: 1,340.13
- **Standard Deviation**: 230.29

**Interpretation**: I found that Manhattan shows the highest variability in SAT performance, indicating a wider range of educational outcomes. This could reflect the diverse socioeconomic landscape and the presence of both highly selective specialized schools and schools serving disadvantaged communities.
