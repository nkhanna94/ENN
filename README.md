# US Drug Overdose Deaths

## Data Visualization

**Team Members:**  
Niharika, Natalie, Eloise

Data visualization of drug overdoses in the United States based on different factors.

---

## Introduction

For our data visualization, we chose to visualize which demographics are most impacted by drug overdoses. This can help policymakers and healthcare workers assess which populations are the most vulnerable to give proper resources.

---

## Our Questions

1. **Are there any specific demographic groups (gender/sex/age) that are most affected by specific types of drug overdoses?**
2. **Were there any major public health policies or interventions introduced in the time period of the data?**

---

## The Dataset

- **Author:** The data is collected by the National Center for Health Statistics and available on the CDC website.
- **Dates:** This data ranges from 1999-2019.
- **Location:** Represents nationwide data in the United States.
- **Numbers:** Deaths are recorded from drug overdose based on a specific proportion of per 100,000 to see the proportion of different demographics.

---

## Data Cleaning

### Loading The Dataset
Loaded the dataset using pandas library, checked out the shape and basic info, and provided a description of the dataset.

### Checked for Null, Duplicate Values
We found that there were no duplicate values but some null values in two columns of the dataset.

### Handle Missing Data
Replaced missing values in `ESTIMATE` with the median. Dropped the column `FLAG` having 5000+ NAN values.

### Checked for Outliers
Checked if there were any outliers in the dataset using the IQR method but found none.

### Cleaned Data
Downloaded the cleaned data and began the visualization.

---

## Analysis and Findings

### Question 1: Are there any specific demographic groups (gender/sex/age) that are most affected by specific types of drug overdoses?

#### Demographic for Highest Death Rate of Substances
From this visualization, we determined that:
- Males aged 25-34 are responsible for the highest death rate.
- Opioids are responsible for the highest death rate compared to all other drugs.

#### Overdose Rates Male vs. Female based on Drug Type
From this visualization, we concluded that:
- Opioids make up the highest rate of drug overdose.
- Females generally tend to have lower rates of overdose.

#### Sex and Race vs. Overdose Deaths (per 2 million)
From this visualization, we concluded that:
- White males, Native American males, Black males, and Native American women have the highest rates of overdose in the United States per 2 million.

#### Sex and Race vs. Overdose Deaths (per 100,000)
From this visualization, we assessed the difference in estimates between white males and black males. The overdose distribution among the drugs is relatively similar.

#### American Indian vs. Overdose Deaths (per 100,000)
From this visualization, we found that compared to white males, there is a higher proportion of drug overdoses other than opioids among American Indian males. There is also a higher number of overdoses for methadone and heroin.

### Question 2: Are there any specific demographic groups (gender/sex/age) that are most affected by opioid overdoses?

#### Opioid Overdose Death Rates by Age Group
From this visualization, we determined that:
- Males aged 35-44 years have the highest death rate, with an average of 9.8 deaths per 100,000.

### Question 3: Were there any major public health policies or interventions introduced in the time period of the data?

#### Major Nationwide Health Policies
- **Ryan Haight Online Pharmacy Consumer Protection Act (2008):** Regulates online sale of controlled substances and prevents the illegal sale of prescription drugs over the internet.
- **Drug Addiction Treatment Act of 2000 (DATA) (2000):** Allows qualified physicians to prescribe certain medications for opioid dependence outside of traditional opioid treatment programs.
- **Comprehensive Addiction and Recovery Act (CARA) (2016):** Expands access to opioid addiction treatment and provides funding for opioid overdose reversal medication distribution programs.
- **21st Century Cures Act (2016):** Allocates funding for opioid addiction prevention and treatment initiatives, including grants for states to combat the opioid epidemic.
- **Opioid Crisis Response Act (2018):** Includes provisions to enhance prevention, treatment, and recovery efforts related to opioid addiction.

#### Death Rate of Overdose Overtime vs. Public Policies Enacted
Although there is an upward trend in the data, there is a slight reduction in the nationwide estimate after the 2008 Online Pharmacy Consumer Protection Act. Even with public health policies being enacted, more work needs to be done to reduce overdoses.

---

## Conclusion

### Question 1:
- Males aged 25-34 are responsible for the highest death rate.
- Opioids are responsible for the highest death rate compared to all other drugs.
- White males, Native American males, Black males, and Native American women have the highest rates of overdose.

### Question 2:
- Males aged 35-44 years have the highest death rate with an average of 9.8 deaths per 100,000.

### Question 3:
- There is a slight reduction in the nationwide estimate after the 2008 Online Pharmacy Consumer Protection Act.
- More work needs to be done to reduce overdoses despite public health policies being enacted.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Tableau

---

## Acknowledgments

- Data from [CDC](https://www.cdc.gov/nchs/data_access/VitalStatsOnline.html)
- Visualization tools used: Python, Pandas, Matplotlib
- Team Members: Niharika, Natalie Hinds, Eloise
