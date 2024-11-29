# GOVERNMENT-GRANT-ANALYSIS
Analyze data and get informed decision on the grants allocated to businesses by govenrment


![](govt_grant.jpg)

## INTRODUCTION 
Money and business go hand in hand as money is the only way business can be developed. So that’s where government grants come into the picture for early stage companies, consultants, universities, utilities and consultants comes into play.
Government grants are a critical tool in fostering business growth, innovation, and stability. These grants help businesses progress from inception to sustainability, often providing the initial support required to bridge the gap between ideas and actionable results. In this dataset, we explore how the U.S. government allocated grants to businesses, focusing on how, who, and where the funds were distributed. Below is a detailed breakdown of the objectives for the grant. 
#### N/B This dataset spans from 1991-2024, providing a comprehensive view of the grant given by government over three(3) decades. However for the purpose of this summary, we will focus on the most recent years, 2023-2024.

## PROJECT OBJECTIVES
How the Grant Was Allocated
The grants were strategically distributed across multiple categories based on business needs and project focus. Key areas include:
1.	Demonstration Projects - Focused on practical implementation of business concepts, receiving the largest share of the funds.
2.	Research and Development (R&D) - Aimed at fostering innovation and technological advancements.
3.	Ecosystem Building - Investments in interconnected systems to support industries collectively.
4.	Technology Feasibility - Assessing the practicality of emerging solutions before scaling.
Allocation reflects a balanced approach, emphasizing both immediate impact and long-term innovation.
________________________________________
Who the Grant Was Allocated To
The recipients of the grants were diverse, ranging from small startups to large institutions. Key groups include:
1.	Early-Stage Companies - Businesses in their nascent stages were prioritized to ensure a strong foundation for growth.
2.	Universities and Research Centers - Academic institutions received significant funding to drive innovation and experimental projects.
3.	Utilities - Focused on infrastructure and essential services, receiving the largest share of the grants.
4.	Corporates and Trade Associations - Supported for their role in scaling projects and promoting industry standards.
5.	Consultants - Engaged to provide expertise and guidance on specific projects.
This distribution highlights the government's intent to empower a wide range of stakeholders, fostering collaboration across industries and sectors.
________________________________________
Where the Grant Was Allocated
Grants were allocated geographically to ensure equitable development across various regions. The funds targeted:
1.	Urban Areas - Investments in technology hubs and metropolitan business centers to accelerate innovation.
2.	Rural Regions - Support for small businesses and initiatives to boost local economies.
3.	Strategic Sectors - Specific industries critical to national growth, such as renewable energy, healthcare, and technology.
These geographic spread underscores the government's focus on inclusive growth, ensuring no region or sector is left behind.
The U.S. government's grants to businesses have proven instrumental in stabilizing and growing enterprises across the country. By addressing how, who, and where, these grants foster innovation, build resilience, and create opportunities in diverse sectors. The insights from this dataset provide a clear picture of the government's strategic allocation, highlighting its role in supporting a thriving business ecosystem.

## TOOLS  USED 
Power bi - cleaning, analyzing and visualization of the dataset

   ![](POWER_BI.jpg)

## Data Source and Cleaning Process
#### Data Source
The dataset used in this analysis was sourced from the Data.gov platform. It contains information on government grants awarded to businesses, providing critical insights into the allocation of funds. The dataset consists of a single table with the following 11 columns:
1.	Application ID (Unique Identifier)
2.	Award Amount (Numerical)
3.	Contractor City (Categorical)
4.	Contractor State (Categorical)
5.	Contractor Street (Categorical)
6.	Contractor Type (Categorical)
7.	Primary Contractor Name (Categorical)
8.	Award Date (Date)
9.	Current Date (Date)
10.	Project Title (Categorical)
11.	Project Type (Categorical)
#### Data Types
The dataset includes multiple data types:

•	Categorical Data: Contractor city, contractor state, contractor street, contractor type, primary contractor name, project title, and project type.

•	Numerical Data: Award amount.

•	Date Data: Award date and current date.

•	Unique Identifier: Application ID.

### Data Cleaning Process
To ensure the dataset was suitable for analysis and visualization, it underwent a comprehensive cleaning process using Power BI Power Query:
1.	Removing Duplicates: Ensured data integrity by eliminating duplicate entries.
2.	Data Type Validation: Corrected and assigned appropriate data types (e.g., numerical, date, and categorical) for all columns.
3.	Handling Missing Data: Addressed missing values by either filtering out incomplete rows or filling down values where applicable, depending on the context and impact on analysis.
4.	Final Validation: Reviewed the cleaned dataset to ensure accuracy and consistency before proceeding with any visualization or further analysis.
This cleaning process established a robust foundation for meaningful insights and reliable visualizations.

## GENERAL ANALYSIS
The total grant amount disbursed by the U.S. government to businesses in this dataset is $1,251,653,786. This substantial funding reflects the government's commitment to supporting diverse sectors and addressing varied business needs.

The average award amount is $430. 417, 395.5k

#### Top five contractor cities 

Madrid-----     $2,796,600

Maine------     $3,000,000

New Jersey----- $11,418,038

NM--------      $6,353,834

Washington---   $1,500,000

   ![](top_cities.png)


#### Bottom 5 Contractor cities
AK----- $48,497

IN----- $20,000

LA----- $22,500

MO----- $50,000

MS----- $50,000


![](bottom_cities.png)


## ANALYSIS FOR 2023
This document outlines the fluctuations in the award money disbursed throughout the year 2023, along with the final distribution across various application categories. The data covers the award amounts for each month and provides insight into how the funds were allocated across different areas of focus.

#### Monthly Award Money Breakdown
The award money fluctuated significantly throughout the year. Below is a summary of the monthly disbursements:
Month	                  Award Money (USD)

January	                $1,256,403

February	              $1,321,998

March	                  $973,753 (Decrease of $348,245 from February)

April	                  $400,000

May	                    $50,000 (Lowest amount of the year)

June	                  $10,800,000

July	                  $1,032,000

August	                $3,191,783

September	              $500,000

October	                $0 (No award disbursed)

November	              $757,407

December	              $308,225

#### Total Award Money Disbursed in 2023:
###### $31.26 million
The total award money disbursed in 2023 was $31.26 million, with notable fluctuations across the months:
1.	Highest Award Month: June ($10.8 million) - The award money in June represented 34.55% of the total disbursement, significantly surpassing all other months.
2.	Lowest Award Month: May ($50,000) - May’s disbursement was only 0.16% of the total, highlighting a sharp contrast compared to June.
3.	No Disbursement in October - October saw no award disbursement, suggesting a pause in fund allocation during this period.
4.	Significant Drop in March and April:
o	March saw a $348,245 decrease from February.
o	April’s disbursement dropped further to $400,000, which is a reduction of 58.93% compared to March.
5.	Irregular Disbursement Pattern - The award money distribution lacked uniformity, with large sums disbursed in some months (e.g., June and August) and minimal or no disbursements in others.
#### Award Money Allocation by Contractor’s type
Venture development – $8,500,000

Early-stage company - $7,912,539

Others - $4,579,71

Corporate _ $4,388,336

Laboratory/Research centre - $3,405,496

Industry - $1,000,000

University - $975,968

Consult- $400,00

Municipality and government agency - $95,623

The allocation across contractor types showed a diverse spread:
•	Venture Development ($8.5 million) received the highest funding, accounting for 27.19% of the total disbursement.

•	Early-stage companies ($7,912,539) were the second-largest recipient, making up 25.30% of the total.

•	Other categories included:

o	Others: $4,579,710 (14.65%)

o	Corporate: $4,388,336 (14.04%)

o	Laboratory/Research Centers: $3,405,496 (10.89%)

o	Industry: $1,000,000 (3.20%)

o	University: $975,968 (3.12%)

o	Consultants: $400,000 (1.28%)

o	Municipality and Government Agencies: $95,623 (0.31%)


#### Award Money Allocation by Category

Throughout the year, the total award money was allocated across several key application categories. Below is the distribution based on percentages:
Category	Percentage of Total Award Money
Demonstration	34.48%

Research Study	34.48%

Product Development	20.69%

Technology	6.90%

Ecosystem	3.45%

The allocation by category revealed a focus on Demonstration and Research Studies, each receiving 34.48% of the total funds. The distribution in percentages is as follows:
•	Demonstration: 34.48%

•	Research Study: 34.48%

•	Product Development: 20.69%

•	Technology: 6.90%

•	Ecosystem: 3.45%

This indicates that more than two-thirds (68.96%) of the funds were directed toward Demonstration and Research Studies, highlighting their critical importance in the overall funding strategy.
________________________________________
Conclusions
1.	Fluctuating Disbursement Trends: The monthly award money exhibited significant variation, with some months like June receiving disproportionately higher amounts while others (e.g., May and October) received little or no funding. This irregular pattern might reflect specific funding cycles, priorities, or project timelines.
2.	Focus on Key Contractor Types: Venture development and early-stage companies collectively received over 52% of the total funds, emphasizing a commitment to fostering innovation and scaling nascent projects.
3.	Category Prioritization: Demonstration and Research Studies dominated the allocation, collectively receiving 68.96% of the total funds, indicating a strong emphasis on applied and experimental approaches.
4.	Diverse Stakeholder Involvement: A wide range of entities, including universities, laboratories, corporations, and municipalities, participated in the funding, although the contribution to government-related projects was minimal (0.31%).
5.	Strategic Investments in Product Development: Despite receiving only 20.69%, the allocation to product development indicates a balanced focus on advancing technologies for market readiness.

![](Screenshot_B.png)




   

  ## Award Money Disbursement Overview for 2024
The award money disbursed in 2024 totaled $22,408,811, distributed across various months, contractor types, and project categories. This document outlines the breakdown and provides insights into trends and allocation priorities.
________________________________________
Monthly Award Money Disbursement
The total award money was disbursed as follows:
Month	                     Award Money (USD)	        Percentage of Total (%)

January	                    $1,106,578          	  4.94%

February	                    $961,158	              4.29%

March	                       $6,806,000	          30.37%

April	                       $1,916,316	          8.56%

May	                       $800,000	             3.57%

June	                       $800,000            	 3.57%

July	                       $1,989,019	          8.87%

August	                    $1,529,740	          6.83%

Key Observations:
1.	March received the highest allocation of $6,806,000, constituting 30.37% of the total award money.
2.	July ($1,989,019) and April ($1,916,316) were the next largest recipients, contributing 8.87% and 8.56%, respectively.
3.	Combined, March, July, and April accounted for $10,711,335, which is nearly half (47.8%) of the total disbursement. This amount alone is comparable to the total award money distributed in 2023, indicating a significant increase in funding allocation.
4.	Other months, such as May and June, received only 3.57% each, suggesting a more targeted approach during certain periods.
________________________________________
Award Money Allocation by Contractor Type
Contractor Type	          Award Money (USD)	      Percentage of Total (%)

Utility	                    $8,000,000	              35.71%

University	                 $5,746,227	              25.65%

Early-stage Company	        $5,369,818	              23.96%

Laboratory/Research Center	  $2,889,108	              12.89%

Consultant	                 $400,000	                 1.79%

Industry Trade Association	  $399,928	                 1.79%

Corporate	                 $103,730	                 0.46%

Key Observations:
1.	Utilities received the highest allocation ($8 million), making up 35.71% of the total. This reflects a significant focus on infrastructure and utility-based projects.
2.	Universities and early-stage companies were the next largest recipients, collectively accounting for 49.61% of the total disbursement. This highlights a strong emphasis on academic and entrepreneurial innovation.
3.	Laboratory and research centers were allocated 12.89%, showcasing continued investment in scientific and experimental pursuits.
4.	Smaller contributions were made to consultants, industry trade associations, and corporate entities, collectively accounting for just 4.04%, signifying a focus on larger-scale projects.
________________________________________
Award Money Allocation by Project Type
Project Type	           Award Money (USD)	             Percentage of Total (%)

Demonstration	             $11,498,838	                  51.31%

Ecosystem	                $4,500,000	                     20.08%

Product Development	       $2,933,556	                     13.09%

Research Study	             $1,999,839	                      8.93%

Technology Feasibility	    $1,496,578	                      6.68%

Key Observations:

1.	Demonstration projects dominated the allocation, receiving 51.31% of the total award money. This reflects a strong emphasis on practical applications and large-scale implementations.
2.	Ecosystem development followed with 20.08%, highlighting efforts to build interconnected systems and frameworks.
3.	Product development accounted for 13.09%, demonstrating continued support for advancing technology into market-ready solutions.
4.	Research studies and technology feasibility assessments received 8.93% and 6.68%, respectively, indicating sustained investment in exploratory and preparatory projects.
________________________________________
Conclusion

1.	Increased Funding in 2024: The total award money for 2024 ($22.4 million) reflects a notable increase compared to 2023. The concentration of funds in March, July, and April indicates a strategic emphasis on key periods of activity.
2.	Contractor Type Priorities: Utilities, universities, and early-stage companies received the bulk of the funds, aligning with priorities in innovation, infrastructure, and academia. Smaller allocations to consultants and corporates suggest a selective approach to smaller-scale engagements.
3.	Project Type Focus: Demonstration projects received over half of the total funds, emphasizing practical implementation. Significant investment in ecosystem development and product innovation further demonstrates a focus on large-scale and interconnected solutions.
4.	Targeted Disbursement Strategy: The data suggests a strategic approach to funding, with a clear prioritization of impactful and scalable projects. This aligns with broader goals to drive innovation, research, and development across key sectors.

![](Screenshot_A.png)

for a more in-depth analysis and to explore the entire dataset from 1991  to 2024, click on the link below to access the full dashboard
https://app.powerbi.com/view?r=eyJrIjoiMTZjZTU2ODctYzgzYi00ODUwLWJmNGYtYWYzNTFkNTAzM2ZjIiwidCI6ImRkNDg0OTZkLWE3ZDEtNDhmOS05ZGRiLTA4MTJiY2Q1ZTlkNCIsImMiOjZ9
