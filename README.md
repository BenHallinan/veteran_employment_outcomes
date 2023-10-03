# veteran_employment_outcomes
An analysis of enlisted veteran employment status and salary post-service based on their military occupation, pay grade, and AQFT test scores.

# Background
Transitioning from military life into the civilian workforce can be a daunting and challenging time for many. Veterans often struggle to find work post-service and often even when they do its in an industry where they aren't realizing their full potential. From 2000 to 2015 approximately 342,000 enlisted veterans where still unemployed a year after they had left service and approximately 169,000 were unemployed 5 years after their service.

The unique skills, experience, and knowledge that is learned by our soldiers and NCOs throughout each military occupation (and the positions held at different ranks) can serve a valuable purpose in civilian industries. However, in stressfull times such as the transition out of the military, it is likely that veterans often find themselves unsure of their potential or fraught with decision paralysis. Both things that could lead to unemployment or a unfulfilling (or high paying) job.

# Purpose

By analyzing concentrations of unemployment by occupation or rank, by finding clusters of industries where certain populations thrive post-service, by understanding the post-service outcomes of the AQFT terciles, we can better provide our military members with the key information needed to make the best decisions possible. Whether thats a specific industry to seek based on their service record or whether they should go for that promotion or training based on the increase in success post-service.

For that purpose, I will be looking at the variations in employment and median income between combat related military occupations and non-combat related occupations.

Additionally, looking at this data through another lense, could it allow senior leaders to better train and develop its enlisted ranks while they are in and better prepare their subordinates for life after service?

# Data
The dataset that I am using is an experimental tabulation of Enlisted Veteran Employment Outcomes by the US Census Bureau which was developed in partnership with the Longitudinal Employer-Household Dynamics (LEHD) program and the United States Army. You can find the link to the original tabulation of the data [here] (https://lehd.ces.census.gov/data/veo_experimental.html). 

The tabulation of data provides earning and employment data from veterans who left military service from 2000 - 2015. The dataset then sorts them in a variety of ways. The primary categorization and grouping of the enlisted veterans is done so by pay grade (E1 - E9) and military occupation (which I will refer to as MOS). The data is further sub-categorized by the civilian industry the veterans entered, their geographic region, age, race & ethnicity, education obtained, and by AFQT terciles.   







# Rough Drafts/Notes Follow:

#### The following are all the different data frames that have been sourced from the Veteran Employment Outcomes Data Tables from the US Census Bureau. 
##### These are the raw data sets and have not undergone any cleaning.

 - veo_by_occ_grade_df; A combined look at employment statistics from enlisted veterans by both military occupation and pay grade.
 - veo_by_occ_df; A look at employment statistics from enlisted veterans by military occupation
 - veo_by_grade_df; A look at employment statistics from enlisted veterans by pay grade
 - veo_by_AQFT_df; A look at employment statistics from enlisted veterans by AQFT Terciles
##### The source data file (veopu.xlsx), located in the data directory, allows to parse the employment statistics of enlisted veterans even further by categories such as geography, Industry they entered, age, sex, and Race/Ethnicity.

##### The Veteran Employment Outcomes is an experimental tabulation of data and, as such, leaves a lot of potential and opportunity to further analysis the data and to answer some really interesting questions. An analysis of this data would provide a significant amount of valuable information for senior military leaders to disseminate throughout the ranks in order to best guide and mentor enlisted soldiers and NCOs as they plan on transitioning out of the military. 

