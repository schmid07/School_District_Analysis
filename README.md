# School_District_Analysis
The School Board has identified evidence of academic dishonesty, specifically the reading and math scores for ninth graders at Thomas High School (THS).  They have asked us to replace the math and reading scores for THS w with NaNs while keeping the rest of the data intacts.  Once removed, they have also asked us to repeat the school district analysis and write up a report to describe how these changes affected the overall analysis.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code

## Summary
The analysis of the school district data (n = 15 total schools) shows that the district was affected in the following ways:
- With a cutoff of 70%, 74.98% and 85.81% of students passed math and reading, respectively, before removing 9th graders from THS.  After removal, the numbers declined slightly to 74.8% and 85.7%% for math and reading respectively.  The overall passing rate declined from 65.2% to 64.9%.
- After removal of ninth graders at THS, the percentage of students passing math declined from 93.27% to 93.19% and the percentage of students passing reading declined from 97.31% to 97.02%.  Overall passing rates declined from 90.95% to 90.63%.
- Removing the scores doesn't move the needle much.  THS remains a top five school based on overall passing rates.
- As we only replaced ninth grade scores at one school, THS, there is no impact on math and reading scores for other grades and only a slight impact on ninth grade scores.
- There is minimal impact to scores by school spending, school size, and school type.  
- There is a negative correlation between school spending and overall passing rates.  For schools that spents $584/yr per student the overall passing rate was 90% versus 54% for schools that spent between $645 and $675.
- There is a negative correlation between overall passing rates and school size.  As school size gets bigger, scores decline.
- Charter schools (90% passing rate) significantly outperformed district schools (54% passing rate).
- The avreage reading, average math, and overall passing rates at THS declined slightly.  Ninth grade scores across the district declined very sligthly as a result of removing THS ninth grade scores.  



