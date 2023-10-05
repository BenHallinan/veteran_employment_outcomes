# Veteran Employment Outcomes
An analysis of enlisted veteran employment status and salary post-service based on their military occupation, pay grade, and AQFT test scores.

# Background
Transitioning from military life into the civilian workforce can be a daunting and challenging time for many. Veterans often struggle to find work post-service and often even when they do it's in an industry where they aren't realizing their full potential. From 2000 to 2015 approximately 342,000 enlisted veterans were still unemployed a year after they had left service and approximately 169,000 were unemployed 5 years after their service.

The unique skills, experience, and knowledge that is learned by our soldiers and NCOs throughout each military occupation (and the positions held at different ranks) can serve a valuable purpose in civilian industries. However, in stressful times such as the transition out of the military, it is likely that veterans often find themselves unsure of their potential or fraught with decision paralysis. Both could lead to unemployment or an unfulfilling (or high paying) job. Is that struggle universal for veterans? Or it is concentrated on DOD occupations that may contain less transferable skills?

# Purpose

By analyzing concentrations of unemployment by occupation type or rank, we can better provide our military members with the key information needed to make the best decisions possible. Whether that's a specific industry to seek based on their service record or whether they should go for that promotion or training based on the potential for that increase in success post-service.

For that purpose, I will be looking at the variations in employment and median income between combat related military occupations and non-combat related occupations.

Additionally, looking at this data through another lens, could it allow senior leaders to better train and develop its enlisted ranks while they are in and better prepare their subordinates for life after service?

# Data
The dataset that I am using is an experimental tabulation of Enlisted Veteran Employment Outcomes by the US Census Bureau which was developed in partnership with the Longitudinal Employer-Household Dynamics (LEHD) program and the United States Army. You can find the link to the original tabulation of the data [here] (https://lehd.ces.census.gov/data/veo_experimental.html). 

The tabulation of data provides earning and employment data from veterans who left military service from 2000 - 2015. The dataset then sorts them in a variety of ways. The primary categorization and grouping of the enlisted veterans is done so by pay grade (E1 - E9) and military occupation (which I will refer to as MOS). The data is further sub-categorized by the civilian industry the veterans entered, their geographic region, age, race & ethnicity, education obtained, and by AFQT terciles. For the purpose of this analysis, I am primarily going to be looking at the MOS and pay grade of the Veterans and what their DOD occupation was. 

# Exploratory Data Analysis

## Employment and Unemployment By Pay Grade
![](/visuals/employment_by_paygrade.png)
Looking at the employment outcomes by pay grade gives us a good general look at the overall success of enlisted veterans in finding a job based on what rank they obtained by the time they left service. Right away we can see that the group that consists of the senior NCOs of our enlisted veterans (E6-E9), overall fared better finding employment in the civilian markets then their junior NCO and soldier counterparts. In the first year post-service, the senior enlisted veterans made up 27% of those who found employment and only 16.5% of those still unemployed. By the 10 year mark, the senior enlisted veterans made up only 11% who took up until that point post-service to find employment and only 4.7% of those that were still unemployed.
![](/visuals/unemployment_by_paygrade.png)

These initial findings are not surprising given the time, experience, and qualifications required to obtain the higher pay grades in the US military. 

## Employment Outcome and Average Pay: Combat MOS vs Non-Combat MOS
One of the main questions that I asked for this dataset was whether there was a significant difference in employment outcomes based on whether the veteran was a combat arms related MOS or a non-combat arms MOS during their time in service. Below is a table outlining what MOS's were included in the data set and what group of the two I put them in. One note to make on the available set of professions is the limited and generalized nature of them. The categorization of the dataset includes both highly generalized as well as some niche/extremely specific occupations and therefore is not all encompassing or representative of the wide range of occupations and specializations across the entire armed forces.
![](/visuals/MOS_table.png)

First, keeping with analysis of employment outcomes, let's take a look at the combat MOS's versus the non-combat at 1, 5, and 10 years post-service.
![](/visuals/MOS_employment_status_byyear_V2.png)
Right away we can see that there is an interesting trend in the employment outcomes over time between the two groups. Within the first year post-service, the success rate in finding employment is fairly similar (approx. 48% success). However, as time progresses to the 5 and 10 year marks, the success rates for veterans of non-combat MOS have increased at a rate noticeably  higher than that of combat MOS veterans. As to an inference as to why, the most likely cause of this is the longer-term marketability of skills and qualification learned in non-combat occupations over that of the combat related occupations.  


The next step in the analysis of the employment outcomes between combat and non-combat veterans is the comparison  of their median outcomes at the 50th and 75th percentiles. Here we see that the trend in favor of higher average annual incomes remains consistently in favor of the non-combat veterans. The primary inference to be drawn from that is the more technical or specialized nature of many of the non-combat occupations throughout the military lend those veterans to getting civilian jobs in equivalently specialized industries.
![](/visuals/MOS_income_byyear.png)

# Results


# Considerations for Future Analysis












# Rough Drafts/Notes Follow:

#### The following are all the different data frames that have been sourced from the Veteran Employment Outcomes Data Tables from the US Census Bureau. 
##### These are the raw data sets and have not undergone any cleaning.

 - veo_by_occ_grade_df; A combined look at employment statistics from enlisted veterans by both military occupation and pay grade.
 - veo_by_occ_df; A look at employment statistics from enlisted veterans by military occupation
 - veo_by_grade_df; A look at employment statistics from enlisted veterans by pay grade
 - veo_by_AQFT_df; A look at employment statistics from enlisted veterans by AQFT Terciles
##### The source data file (veopu.xlsx), located in the data directory, allows to parse the employment statistics of enlisted veterans even further by categories such as geography, Industry they entered, age, sex, and Race/Ethnicity.

##### The Veteran Employment Outcomes is an experimental tabulation of data and, as such, leaves a lot of potential and opportunity to further analysis the data and to answer some really interesting questions. An analysis of this data would provide a significant amount of valuable information for senior military leaders to disseminate throughout the ranks in order to best guide and mentor enlisted soldiers and NCOs as they plan on transitioning out of the military. 

