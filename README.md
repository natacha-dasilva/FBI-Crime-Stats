# FBI  - Project Overview

## The Project
For the FBI it is important to identify key patterns of criminal behaviour including: who is at a higher risk of being targeted, what areas are seeing a rise in crime as well as which time of year crimes spike. This dashboard was created to allow the Director, Deputy Director, Associate Deputy Director, Executive Assistant Directors and Assistant Directors to have a look into crimes of this current year and identify the reoccurring types of crimes committed against certain groups of people.

## Dataset
This dataset leverages crime data made publicly available on data.gov. These resources originate from the Federal Bureau of Investigation's (FBI) Uniform Crime Reporting (UCR) Program. The UCR Program collects data from participating law enforcement agencies across the United States, providing a comprehensive and representative picture of criminal activity nationwide. The datasets were consolidated from 2020 onwards and uploaded to Kaggle with one table, which included information about victim descent, crime code, premises type and weapons used. To add to that I created 7 dim tables as they were needed to write out further details of codes written in the main table, this allows anyone who has access to the dashboard to see the name of the crime type, premises type etc. instead of having to look up the reference for what each code stands for - these all have a one to many relationship with the main table. I also created a dim date table, a measures table and an employees table which allowed me to create a personalised dashboard depending on which employee was logged in.
![dataset](https://github.com/natacha-dasilva/FBI-Crime-Stats/blob/main/Assets/FBI%20Table%20Relationships.png)

## Dashboard
https://github.com/user-attachments/assets/80a6df7a-1d4f-4f9f-800d-da492b01ff5c

## Business Use
By using this dashboard, those at the assistant director level and above can:

1. **Take a look at the overall picture:**
A quick glance at how many arrests have been made so far this year for adults and juveniles, as well as what number of crimes are still currently under investigation. They can also see what the top 5 locations, crimes and weapons are as well as which age group has the most victims and the difference between crimes that are considered serious and less serious.

2. **Identify victim groups at risk:**
Filtering by gender, descent and severity of the crime they can compare the number of victims and recognise what hour, day, month and age group sees the highest crimes reported. They can also see if there are trends when it comes to top committed crimes against the groups. 

3. **Holiday pattern recognition:**
Tracking crimes reported during holiday periods with victim groups, locations and premises allows the FBI to see if there is repeated behaviour compared to what they saw last year and discuss with local enforcement teams what measures can be taken to prevent this from happening again.

4. **Premises analysis:**
Taking a look at what premises type has the highest crimes reported, and if this is a country-wide issue or an issue specific to different states, will allow teams to know where efforts need to be concentrated.

## Beyond the Dashboard
Using this main dashboard as a springboard, the FBI can identify what extra reports need to be created throughout the year that look deeper into results found such as the targeting of specific groups of people, typical crime types on upcoming holidays, year on year comparisons. This dashboard will also allow them to create safety/awareness campaigns to keep vulnerable people safe, or work with local enforcement teams to increase the number of staff members in certain locations where crime is growing.
