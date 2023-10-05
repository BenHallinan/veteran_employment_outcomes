# Veteran Employment Outcomes
An analysis of enlisted veteran employment status and salary post-service based on their type of military occupation and pay grade.

# Background
Transitioning from military life into the civilian workforce can be a daunting and challenging time for many. Veterans often struggle to find work post-service and often even when they do it's in an industry where they aren't realizing their full potential. From 2000 to 2015 approximately 342,000 enlisted veterans were still unemployed a year after they had left service and approximately 169,000 were unemployed 5 years after their service.

The unique skills, experience, and knowledge that is learned by our soldiers and NCOs throughout each military occupation (and the positions held at different ranks) can serve a valuable purpose in civilian industries. However, in stressful times such as the transition out of the military, it is likely that veterans often find themselves unsure of their potential or fraught with decision paralysis. Both could lead to unemployment or an unfulfilling (or high paying) job. Is that struggle universal for veterans? Or it is concentrated on DOD occupations that may contain less transferable skills?

# Purpose

By analyzing concentrations of unemployment by occupation type or rank, we can better provide our military members with the key information needed to make the best decisions possible. Whether that's a specific industry to seek based on their service record or whether they should go for that promotion or training based on the potential for that increase in success post-service.

For that purpose, I will be looking at the variations in employment and median income between combat related military occupations and non-combat related occupations.

Additionally, looking at this data through another lens, could it allow senior leaders to better train and develop its enlisted ranks while they are in and better prepare their subordinates for life after service?

# Data
The dataset that I am using is an experimental tabulation of Enlisted Veteran Employment Outcomes by the US Census Bureau which was developed in partnership with the Longitudinal Employer-Household Dynamics (LEHD) program and the United States Army. You can find the link to the original tabulation of the data [here](https://lehd.ces.census.gov/data/veo_experimental.html). 

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

First, keeping with analysis of employment outcomes, let's take a look at the combat MOS's versus the non-combat at 1, 5, and 10 years post-service. Right away we can see that there is an interesting trend in the employment outcomes over time between the two groups. Within the first year post-service, the success rate in finding employment is fairly similar (approx. 48% success). However, as time progresses to the 5 and 10 year marks, the success rates for veterans of non-combat MOS have increased at a rate noticeably  higher than that of combat MOS veterans. As to an inference as to why, the most likely cause of this is the longer-term marketability of skills and qualification learned in non-combat occupations over that of the combat related occupations.  
![](/visuals/MOS_employment_status_byyear_V2.png)
 
The next step in the analysis of the employment outcomes between combat and non-combat veterans is the comparison  of their median outcomes at the 50th and 75th percentiles. Here we see that the trend in favor of higher average annual incomes remains consistently in favor of the non-combat veterans. The primary inference to be drawn from that is the more technical or specialized nature of many of the non-combat occupations throughout the military lend those veterans to getting civilian jobs in equivalently specialized industries.
![](/visuals/MOS_income_byyear.png)

# Results & Conclusion
Throughout the Exploratory Data Analysis of the Veterans Employment Outcomes dataset, I sought to answer the question of: Is there a significant difference in the post-service employment success of enlisted veterans based on whether they served in a combat or non-combat related occupation? The analysis of the first year post-service tells us that while the success rates in finding employment is equivalent  between the two groups, non-combat veterans tend to make $5,000 to $10,000 dollars more per year on average. So, in terms of looking at employment outcomes by employment status alone, there does not appear to be any significant difference in veteran ability to find employment within the first year post-service. However, when we start to look at the long-term employment success over the longer horizons of the 5 and 10 year marks post-service, the trends begin to show a higher degree of success in both aspects for veterans with non-combat MOS backgrounds. In these aspects, non-combat MOS veterans maintained a higher rate of employment and a higher average annual salary than their counterparts. 

As I mentioned in the analysis of the MOS graphs, the primary inference that I am making is that the overall marketability and applicability of military experiences such as mechanical engineering, communications/cyberspace, or military intelligence is more durable than experiences of combat MOS occupations. However, I believe that any further insights require additional considerations and more specific approaches to this data.

# Considerations for Future Analysis

With the understanding that this dataset is in its prototype/experimental phase, I would say that the first big consideration I would bring to the table is an overall expansion of the dataset in two key regards: An inclusion of the military office population and a more comprehensive construct and inclusion of the amount of DOD occupations (MOS) that is in our Armed Forces. Improving the dataset in these two key ways would significantly increase the accuracy of any analysis conducted and allow for much more in-depth questions to be asked. 

As for my considerations for future analysis, I would like to analysis the specific civilian industries that veterans enter and see what relationships may be present between that and their DOD occupation. Do certain MOS's tend to cluster into specific civilian industries? Do they find more success in those than the outliners of their MOS? Additionally, I believe that looking at the clustered relationship between highest education level obtained and rank could provide some significant insights into the effectiveness of DOD education programs.