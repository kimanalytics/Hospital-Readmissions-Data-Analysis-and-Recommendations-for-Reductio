# Hospital Readmissions Data Analysis and Recommendations for Reduction

### Background
In October 2012, the US government's Center for Medicare and Medicaid Services (CMS) began reducing Medicare payments for Inpatient Prospective Payment System hospitals with excess readmissions. Excess readmissions are measured by a ratio, by dividing a hospital’s number of “predicted” 30-day readmissions for heart attack, heart failure, and pneumonia by the number that would be “expected,” based on an average hospital with similar patients. A ratio greater than 1 indicates excess readmissions.

### Exercise Directions
In this exercise, I will:
+ critique a preliminary analysis of readmissions data and recommendations (provided below) for reducing the readmissions rate
+ construct a statistically sound analysis and make recommendations of your own

### Resources
+ Data source: https://data.medicare.gov/Hospital-Compare/Hospital-Readmission-Reduction/9n3s-kdb3
+ More information: http://www.cms.gov/Medicare/medicare-fee-for-service-payment/acuteinpatientPPS/readmissions-reduction-program.html
+ Markdown syntax: http://nestacms.com/docs/creating-content/markdown-cheat-sheet

## Preliminary Report
### A. Initial observations based on the plot above
Overall, rate of readmissions is trending down with increasing number of discharges
With lower number of discharges, there is a greater incidence of excess rate of readmissions (area shaded red)
With higher number of discharges, there is a greater incidence of lower rates of readmissions (area shaded green)
### B. Statistics
In hospitals/facilities with number of discharges < 100, mean excess readmission rate is 1.023 and 63% have excess readmission rate greater than 1
In hospitals/facilities with number of discharges > 1000, mean excess readmission rate is 0.978 and 44% have excess readmission rate greater than 1
### C. Conclusions
There is a significant correlation between hospital capacity (number of discharges) and readmission rates.
Smaller hospitals/facilities may be lacking necessary resources to ensure quality care and prevent complications that lead to readmissions.
### D. Regulatory policy recommendations
Hospitals/facilties with small capacity (< 300) should be required to demonstrate upgraded resource allocation for quality care to continue operation.
Directives and incentives should be provided for consolidation of hospitals and facilities to have a smaller number of them with higher capacity and number of discharges.

## New Hypothesis Testing
Our new hypothesis is going to be: There is a significant difference between excess readmission rates for different states.

## Conclusion
There is a significant difference between excess readmission rates for different states. (99% confidence)

## Discussion
Excess readmission could be problematic for hospitals dependent of patients using Medicare payments. The first observation suggested that amount of discharges was related to excess readmission rate. After testing, it was true. However, there could be many uncontrolled variables that leads to low or even high discharges. The quick soultion to this was to combine smaller hospitals to make it have higher dispatch rates. This isn't an optimal solution since it requires even more funding to make this occur. The cost may be even more than trying to keep Medicare patients.
The second hypothesis that I made, suggesting that different states having different excess readmission rate looks at this problem in a different angle. It combines all of the hostpitals in each state regardless of dispatches or size. It looks at the average of excess readmission. This method focuses on which states are the best or worst at low excess readmission rates. My assumption is that the better states have better regulatory practices that ensures lower excess readmission rates. We should look at the top states with low excess readmission rates such as South Dakota to see what different practices they have compared to states like the district of Columbia.
