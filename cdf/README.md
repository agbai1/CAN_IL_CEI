# CEI_Project
The State of Illinois Commision on Equity and Inclusion (CEI) created the <a href = "[https://cei.illinois.gov/business-enterprise-program.html">Business Enterprise Program (BEP)</a> for businesses owned by minorities, women, and persons with disability to foster an inclusive, equitable and competitive business environment that will support underrepresented businesses increase their capacity, grow revenue, and enhance credentials. The state is engaging with private businesses for goods and services through public procurement, and historically, minority-owned businesses are underrepresented in the procurement processes. One of BEP's goal is to provide opportunities for minority-owned businesses to be eligible for public procurement. 

The state’s annual, aggregated aspirational goal is to spend at least 30% of its total non-construction and non professional services dollars with firms certified through BEP. This overall goal is allocated as follows:  
Minority Business Enterprise (MBE): 16%
Women Business Enterprise (WBE): 10%
Persons with Disability Business Enterprise (PBE): 4% 

The state’s annual, aggregated aspirational goal for construction and professional services contracts is to spend not less than 20% of total dollars with BEP firms. This overall goal is allocated as follows: 
Minority Business Enterprise (MBE): 11%
Women Business Enterprise (WBE): 7% 
Persons with Disability Business Enterprise (PBE): 2%

In the <a href = "https://cei.illinois.gov/content/dam/soi/en/web/cei/documents/bep-annual-reports/FY22%20Business%20Enterprise%20Program%20Annual%20Report.pdf">2022 Annual Reporty</a>, BEP set an ambitious goal of $14,130,167,167, which represents a substantial 185% increase from the $4,955,174,823 target in 2021. Although BEP achieved a higher overall dollar amount in 2022, reaching $1,156,587,597 compared to $885,489,466 in 2021, it became evident that attaining 20-30% of the new goal proved to be more challenging. Furthermore, the achievement rate for 2022 was recorded at 8.2%, which is notably lower than the achievement rate of 17.9% in 2021. This significant decline in the achievement percentage further emphasizes the increased difficulty in reaching the specified target during the mentioned year.

This project aims to help CEI to:
1. Explore BEP's current contracting with minority owned firms by mapping existing BEP-certified minority owned businesses database through geospatial analysis
2. Increase BEP participation through analyzing IL demographics (general and business-related) through geospatial analysis, to identify where to potentially expand CEI's efforts (eg. stakeholder outreach, professional consultation, capacity building, new partnerships)
3. Monitor goal by providing internal dashboard/tracker that will allow CEI to proactively see their goal achievement in a more frequent manner, and adjust their operational efforts throughout the fiscal year (work in progress)

CDF directly collaborates with Bruce Montgomery (Acting CEI Commissioner) during Spring and Summer 2023.

## Files in /data repository:
1. Directory_2023-06-20_241.csv: list of certified businesses in the State of Illinois downloaded from <a href = "https://ceibep.diversitysoftware.com/">public online directory</a> on 06/20/2023
2. Directory_2023-06-20_241_nodupl.csv: cleaner version of list of certified businesses -no duplicates per address
3. Dashboard_Raw_Data.xlsx: multi-fiscal year report including Budget, Exemptions, and Dollars Subject to Goal (DSG)

## Files in /codes repository
1. Visualization.R: R codes for creating different types static visualizations (e.g. heatmap, faceted line charts, spatial plots); continuously maintained and updated with codes for more plots.
2. nominatim_extractor.ipynb: codes for generating geocodes for each business
3. combining_jsons.ipynb: used to combine different sets of geocodes (broken down per certification type)
4. Mapping.ipynb: codes to map each certified business

