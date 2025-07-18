# Police-report---Dataset
## Table of Contents

- [Data Description](#dataset-description)
- [Content](#content)
- [Data Sources](#data-sources)
- [Tools](#tools)
- [Data Cleaning](#data-cleaning)
- [Inference Analysis](#inference-analysis)
- [Findings](#findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)
- [Conclusion](#conclusion)

### Dataset Description(Overview)
The Police report dataset is a US record of Police activity in the US police divisions from the year 2021 -2024, an analysis is been carry-out by me a Data Analyst using an excel pivotal and dashboard to extract insights, overview the ongoing activities and to predict the future for security measures.

### Content
 The dataset comprises 18775 rows, observations across 14 variables, each illuminating different facets of activities in the US Police division:

- **ID Reference Number**: subject Identification number.
- **Subject's race**: This column display the subject race.
- **Subject's gender**: The column display the genders.
- **Subject's age**: The age of the subject.
- **Ethnicity**: subject Ethnicity.
- **District of occurrence**:  subject Numbers of occurrence.
- **Adjacent to school**: Close or far to school content
- **Assigned Division**: The police divisions
- **Assigned Bureau**:  Different Unit 
- **Order date:** Periodical Time Track Record

### Data Sources 

•	The data source for the analysis is an Excel file from Kaggle named " Police_report.xlsx"
### Tools:
 * Excel
 * Pivot Table for proper analysis.
 * Excel Dashboard for interactive visualizations

### Data Cleaning
* 1. Null/empty value check to ensure no missing data.
* 2.  Police arrest “Adjacent to school” column was edited for proper analysis as “Yes or No” against “1&0”.
* 3. Duplicate value check: no duplicates found.
* 4. The "Date of purchase" column is been split into Days, Month, and Year of purchase for proper analysis.
* 5. Adjacent to School column was rename to “YES” and “NO” for proper illustration

### Inference Analysis
  The analysis uses several techniques:
* 1. 3-D Column: Analyzes the “Total number of subject by race”.
* 2. Pie of Pie: Analyzes “Gender with the highest arrest”.
* 3. Dough not: Shows “Ethnicity with the highest arrest”.
* 4. 3-D Stacked Column Chart: Review the “Year and month with the highest and lowest arrest”.
* 5. Line chart: Analyzed the “Time with the highest arrest”.
* 6. 3-D Column: Analyzed “Ethnicity division breakdown arrest”.
* 7. Clustered bar: Shows the “Age with the highest arrest”.
* 8. 3-D Column: Shows “bureau race breakdown arrest”.

### Findings
* The total number of arrest is N18,775
* “Black African/American” has the highest number of arrest 9,622 followed by the “white” with a number of 8,552 followed by “Asian”512 and the “unknown” is 56, the American India/ALSK NATV is 26 and lastly is the “Hawaiian/Pacific Islander” with a figure of 6
* In Ethnicity the Non Hispanic has the highest number of subject at 13,529 while the Hispanic is 5,246 
* subject based on “Adjacent school” is 17262 NO(far) and 1513 YES(near)
* 3D has the highest count in the top 5 Assigned Division count which is (4,309), 4D(3894), 5D(3491), 2D(1848), 6D(1760)
* PSB has the highest number of count in “Assigned Bureau” (16,233) followed by FSB(1405) next to ISB(655) and MSB(482)
* 2023 has the highest numbers of “Subject Race” while 2024 has the lowest.
* Number “3” is the mode among the District of occurrence.

### Recommendations
1. **Hotspot Policing**:Concentrating police presence in areas with high crime rates like District”3” majorly on the “Non Hispanic” to deter potential offenders.
2. **Increased Patrols**: Increased visible police presence can deter crime through increased risk of apprehension.
3. **Transparency and Accountability**: Implementing measures to increase public confidence in the police, including oversight mechanisms and investigating misconduct, building trust through community outreach and holding officers accountable for misconduct.
4. **Public Education**: Educating the public about crime prevention strategies, reporting procedures, and the role of law enforcement.
5. **Cultural Sensitivity Training**: Equipping officers with the knowledge and skills to interact effectively with diverse communities.

### Limitations
1. **Information Gaps: Important details might be overlooked or omitted due to the limitations of human observation and recall.

### Conclusion
- The police department can implement strategies focused on prevention, intervention and community engagement. This includes targeted policing in high crime area like (District 3) and also the Non Hispanic in other to reduce the insecurity.
- By combining these strategies, the police departments can create a more effective and sustainable approach to stabilizing criminal activity and improving public safety.
