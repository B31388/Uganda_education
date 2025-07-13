# QUESTION 4: Visualizing education gaps for resource allocation and policy targeting

## Author
- **Name**: Mugimba Kakure Jude
- **Access No.**: B31388
- **Reg. No.**: J25M19/034
- **Submission Date**: July, 2025

## Project Overview
This repository contains deliverables addressing Question 4: visualizing geographic disparities in education access across Uganda using geospatial data. The project dashboard with a Z-pattern layout, revealing that areas like Bushenyi (380% pressure, 36% completion, correlation -0.6351) show low completion despite economic/infrastructure strengths, indicating strain on enrollment. Many pupils are enrolled but along the way some pupils drop out most probably to engage in the available economic activites; the percentage of those that complete primary education is small compared to  low enrollment presssure areas like kaabong. In Kaabong, the data shows that a lower presurre is on enrollment, but the percentage of those that complete is more indicating a deliberate effort to education for those who choose to join education.

### Policy implications
There is need for policies to encourage enrollment of pupils into primary school in the north eastern region of uganda as it has been the case in the rest of the regions. Additionally, there is need for a policy to ensure that enrolled pupils complete their primary education successfuly. 

### areas of highest need
Areas of highest need include Amudat, Kotido and Yumbe and generally the Karamojja region. Effort should be made to encourage primary education enrollment inthe mentioned areas. Completion of primary education should be emphasised accross te country. 

### Deliverables
- `education_status-dashboard.py`: Z-pattern dashboard with dual choropleth maps.
- `education_data_long.csv`: Dataset with education metrics.
- `uganda_districts.json`: GeoJSON file for district maps.
- `Question_4_Report.tex`: LaTeX source for design documentation.

## Setup Instructions
1. **Prerequisites**: Indicated in requirements.txt
2. **Installation**:
   ```bash
   git clone https://github.com/mugimbajude/primary-education.git
   cd primary-education
   pip install dash dash-bootstrap-components plotly pandas