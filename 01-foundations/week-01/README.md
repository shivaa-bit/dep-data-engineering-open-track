
# Is Your Job Plan Safe? A Job Seeker's Guide to PH Industries

## What is this project all about? 
Many Filipino students and job seekers pick a career based on guesswork or rumors. This project is an easy-to-use dashboard that helps job seekers answers two questions:

1. **Is the industry I am considering financially rewarding?**
2. **Will it offer long - term stability?**

## Who will use this tool and what do they need? 
1. **Incoming College Students:** Need reliable local market insights to confidently choose a major or specialization that aligns with their long-term goals.
2. **Fresh Graduates:** Need concrete salary benchmarks to evaluate job offers and understand where the entry-level opportunities are.
3. **Early-Career Professionals:** Need accurate data on market trends and industry health when planning a strategic career pivot or next step.

## How is the dashboard structured? 
When a user selects an industry, it progressively answers their natural questions from high-level metrics down to the specifics.

1. High - Level Information (KPI Cards)
- **Can I afford to live on this salary?** 
    - Shows the average daily pay for this year and whether it went up or down compared to last year.
    - Calculation: Mean daily basic pay of wage and salary workers + Year-over-Year (YoY) % change.
- **Is this salary reliable, or does it wildly change?** 
    - Measures how unstable the pay is. High pay doesn't mean much if it drops unexpectedly next month.
    - Calculation: Coefficient of Variation ($CV =\frac{\sigma}{\mu} * 100$), derived from the standard deviation ($\sigma$) and mean ($\mu$) of historical daily basic pay
- **Are there actual jobs available here?** 
    - Shows what percentage of Filipinos work in this field, and includes a toggle button to see if the jobs are mostly Full-Time or Part-Time.
    - Calculation: $(\frac{Total Industry Employment}{Total Employment in the Philippines} * 100$) 

2. Historical Trends (Side-by-Side Line Charts)
- **How has the pay changed over the years?** 
    - A line graph tracking how the industry's average daily pay has evolved over the years, showing how it responds to economic shifts (such as the COVID 19 (2020–2023) period).
- **Is the industry hiring or shrinking?** 
    - Placed right next to the pay graph so users can see the full story. An industry might pay well, but if it is losing workers every year, it will be very hard to get hired.

3. Total Monthly Compensation (Horizontal Bar Chart)
- **What about my monthly budget and allowances?** 
    - A chart that looks at typical monthly median pay and median allowances. This acts as a realistic "sanity check" to see if a typical worker can comfortably survive on this sector's compensation package over a full year.

4. Occupational Breakdown (Vertical Bar Chart)
- **What occupational categories within that industry pay the most?** 
    - It transitions the user from macro-industry analysis to practical job hunting by showing them exactly which target occupations yield the best financial returns.

## Data Source
1. **Metric 1 & 2, Chart 1**
- Data Source: Average Daily Basic Pay of Wage and Salary Workers by Major Industry Group, Philippines: 2016 to April 2026 (in Php)
- Link: https://openstat.psa.gov.ph/PXWeb/pxweb/en/DB/DB__1B__LFS/0191B3GADB2.px/table/tableViewLayout1/?rxid=227f6805-9732-41b6-981c-ac178832d6db

2. **Metric 3**
- Data Source: Employment by Major Industry Group and Total Hours Worked, Philippines: April 2025 - April 2026
- Link: https://psa.gov.ph/statistics/labor-force-survey

3. **Chart 2**
- Data Source: Number of Employed Persons by Major Industry Group (2009 PSIC Code): January 2012 to April 2026
- Link: https://openstat.psa.gov.ph/PXWeb/pxweb/en/DB/DB__1B__LFS/0101B3GEMP2.px/table/tableViewLayout1/?rxid=227f6805-9732-41b6-981c-ac178832d6db

4. **Chart 3**
- Data Source: Median Monthly Basic Pay and Allowance of Time-Rate Workers on Full-Time Basis by Industry, 2014 to 2022
- Link: https://openstat.psa.gov.ph/PXWeb/pxweb/en/DB/DB__1B__OWS/0041B3E1040.px/?rxid=2a24a72d-cbce-46c4-b4a7-0b11fa999dc5

5. **Chart 4:** 
- Data Source: Average Monthly Wage Rates of Benchmark Occupations by Industry: 2014 to 2022
- Link: https://openstat.psa.gov.ph/PXWeb/pxweb/en/DB/DB__1B__OWS/0031B3E1030.px/table/tableViewLayout1/?rxid=2a24a72d-cbce-46c4-b4a7-0b11fa999dc5






