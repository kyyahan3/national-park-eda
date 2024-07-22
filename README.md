# <b> File Structure <b>
1. 0_Research_Idea
* This folder contains our research topic approved by Dr. Dorff. It is an rmd and md file of our data topic. The rmd file contains some datasets we worked with for this topic. The data collection section of the research idea contains only a few of the datasets we originally started with. As we progressed our research we added more datasets that can be found in the 2_data/raw_data data folder. 

2. 1_preprocessing
* This folder conatins 3 subfolder: csv files, png files, and rmd files. Overall, this folder's goal is to get a basic understanding of all the datasets. 
   * RMD File: This folder contains annooatted rmd files in R code for exploring the datasets in 2_data/raw_data folder. The team did basic plots and aggregations to get a better understanding of the datasets we worked with.
   * PNG File: This folder contains images that were created based on the exploration in the rmd files that will be used in the final report.
   * CSV File: this folder contains subsets of the data that we needed and wanted to look at for this project. 

3. 2_data
 * This folder contains 2 subfolders: clean and raw data.
    * Clean data: This folder contains many csv files that the group worked with and it includes only the desired parks and years for this project and sub-datasets used for graphics. One of the two final master datasets was too large for git so we used a dropbox link "https://www.dropbox.com/s/afzhasp96hvli1t/master_12_17.csv?dl=1" . This file contained all the data for the weather and visitation for the years 2012 to 2017. Our other master named final_weather_biodiversity contains weather, biodiversity, and parks information. Lastly, this file contains rmd files where we joined datasets to create the master files for our final project. 
    * Raw data: This folder contains all the raw data we used for our project. These datasets were not altered by the group. 

4. 3_main_findings
 * This folder contains 4 subfolder: Correlation, Map, PatternComparison, and TimeSeries. 
    * Correlation: This folder contains the rmd file for the work we did for correlation analysis we did and the output images used in the final report.
    * Map: This folder contains the rmd file for the work we did for the map analysis and the output images used in the final report.
    * PatternComparison: This folder contains the rmd file for the work we did for the comparison analysis (specifically looking at temperature and visit) and the output images used in the final report.
    * TimeSeries: This folder contains the rmd file for the work we did for the time series analysis and the output images used in the final report.

4. 4_deliverables
* This folder contains our final report and final presentation. Both were created in google and uploaded to git.

# Meeting Notes (meet every Friday at 3:30 @ DSI unless changed)

## 10/21
* Goals: 
  * Pick a data topic that includes weather.
  * Find datasets.
  * Write short summary on dataset and submit rough draft idea by 10/26.

- Overall decided to look at all national parks and seeing how weather impacts biodiveristy, visit rates, animal endangerment.

## 10/28
- Uploaded all the relevant datasets to Github.
- Team decided to only focus on the national parks in Florida, Colorado and California.
- Team decided to look at the weather, visitation rates, species and biodiversity for each state. 

## 11/3
- Finalized data sets; looking at: visitation rates, biodiversity, and species. 
- Team found a different dataset for visitation rates that was in csv format. 
- Team cleaned the datasets and only included national parks in Flordia, Colorado and California.
- Team split up datasets to do more data wrangling separately. 
  - Hunter: Park and Species
  - Sam: Visitation Rate
  - Ji: City Attribution, Temperature (Monthly), Humidity
  - Yahan: Temperature (Hourly), Weather Description, and Wind Speed

### 11/11
- Team discussed findings after cleaning data and doing basic aggregations. This work was put in preprocessing data.
- Each team memeber made visualizations with their clean data for preprocessing.
   
### 11/16
- Wrote introduction for final report and found a good info graphic, team will revise intro over break and add their preprocessing work.
- Team assigned work over break.

## 12/1
- Joined biodiversity dataset with weather.
- Fixed preprocessing visitation rmd file.
- Cleaned up repo.

## 12/2
- Cleaned up repo.
- Discussed analysis and color scheme for final report. Started working on time series, correlation, and map figures for report.
- Joined clean visitation and clean weather, so now all data is joined in either one of two master data sets.
 - First master contains weather and visitation for 2012-2017 data
 - Second master contains weather, biodiversity, and parks data
 
## 12/3
- Worked on main analysis graphs (timeseries, maps, and corrleation).
- Started writing final report.

## 12/8
- Continued writing up final report.
- Started final presentation.

## 12/10
- Finished presentation.
- Created final graphics for maps.

## 12/11
- Reviewed presentation.
- Made final changes to the report. 
- Cleaned/organized our git.
