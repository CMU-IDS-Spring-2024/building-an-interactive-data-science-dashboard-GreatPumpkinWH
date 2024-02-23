# hw3-template

In this assignment, you will adopt the persona of being a data scientist for Allegheny County’s Health Department.  Your goal is to build data science tools to make it easier for the health department to understand trends of an ongoing health crisis:  fatal accidental overdoses from a variety of drugs in the county.  The Western Pennsylvania Regional Data Center publishes a monthly dataset that describes fatal accidental overdose incidents in Allegheny County, denoting age, gender, race, drugs present, zip code of incident and zip code of residence.

This data, downloaded as of September 22, 2023, is located in [data/overdose_data_092223.csv](data/overdose_data_092223.csv)

Through a series of assignments, you will build out a dashboard to support the interactive exploration and analysis of the dataset.  You will use this same repository for Assignments 3a, 3b, and 3c.  

- [ ] For Assignment 3a, Update the provided Streamlit python file, `pages/1_👥_Demographics.py`
- [ ] For Assignment 3b, Update the provided Streamlit python file, `pages/2_📈_Trends.py`
- [ ] For Assignment 3c, Update the provided Streamlit python file, `pages/3_🌍_Map.py`
- [ ] In addition, submit your Github repository URL on Canvas for each of the three assignments.

## Running the Streamlit app

You can execute the Streamlit app by running `streamlit run County_Dashboard.py`

## Questions of part a

### 1.Did you notice any interesting patterns or trends in the dataset?
When we choose primary drug as Alcohol, at earlier years there is a noticeable upward trend, particularly from around 2010 to 2017 where there is a significant rise.The year 2017 appears to have the highest count of records, which stands out as a peak in overdoses. After 2017, there is an apparent decline in the number of overdoses. Maybe some form of intervention or change in circumstances that affected these numbers.

### 2.Was it possible to understand how the dataset was different in the earlier years versus the more recent years? 

#### 1.If so, what were some differences?  

#### 2。If not, how would you suggest changing the dashboard to make differences easier to find?
Yes, it was. For example, we compare the age distribution of 2007-2010 with the age distribution of 2020-2023, we can found that although both histograms show a similar distribution with a peak in the middle age ranges, the peak age of 2020-2023 is smaller than the peak age of 2007-2010.And the number of overdose records for the Black race has increased when comparing earlier years to more recent years.

### 3.Did you discover any filters that demonstrated big differences from the overall dataset among the demographics (such as age, race, or gender)?

Doxepin. The age distribution of overall dataset is that the number of male  involved in fatal accidental overdoses in Allegheny County is much higher than the number of female. But when we select primary drug as Doxepin, we can see that the number of female is higher than the number of male.

### 4.Are there any other features you wish were present in your dashboard to either make discovery easier or to explore alternative aspects of the dataset?

Yes. We can add incident zip code to integrate a map to visualize geographic patterns which could reveal regional trends or hotspots. And I think adding the total number of people by gender, race, and age for different years can indeed provide a more comprehensive view of the dataset. 
