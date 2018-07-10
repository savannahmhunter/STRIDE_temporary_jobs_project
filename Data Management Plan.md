## Data Management Plan
   
### How will data be collected?
The data will be retreived from the UC Davis HR department either via email or electronic link or via a physical harddrive in an excel or .csv file. Temporary, contract, and limited positions posted to the [career opportunities](https://www.employment.ucdavis.edu/applicants/jsp/shared/search/Search_css.jsp) website will be pulled by the HR Department for years 2016-2018.
    
### Where will raw data be stored?
The raw data will be stored on google drive under my UC Davis account. The folder naming system will match what appears on github. A link to the raw and analyzed data will be available on github. I will also keep a copy of the raw data on my PC.
    
### How will the raw data be named?
The raw data will be named: YYYYMMDD_tjp_ucddata1618_tcl_raw
    
I chose this naming convention as there is a possibility that I may be able to obtain more data from the UC Davis HR department so the current date when the data was received is listed first. Following that I abbreviate temporary jobs project to tjp. Then I title it "ucddata1618" to note where the data originated and the years contained (2016-2018). Then I have tcl which stands for temporary, contract, and limited to note which positions are contained in the data. Finally I end with the word raw to denote that this is raw data.
    
### How will data be analyzed?
The data will be analyzed in R using text mining techniques such as word frequency analysis and topic modeling and potentially other NLP models depending on amount of data available. A sample of 10 current job postings shows that posts range from around 550 words to 1200 words. The amount of words could be cut down by dropping certain fields not relevant to the project for example what files applicants need to attach with their application.

### How will analyzed data be named?
The analyzed data will have the same naming convention above but raw will be dropped and replaced with analyzed. For example: 20180709_tjp_ucddata1618_tcl_analyzed. Beginning the file name with the current date also gives me flexibility to change that if need be as I update the data. However, my hope is to only have two datasets. One, raw file and one that pulls from the raw file runs the code and then saves the data as the analyzed file.
    
### How will the analysis be recorded?
The analysis will be recorded with an R script. In the script I will type detailed notes regarding what the code does and any decisions made.
    
### Where will the analyzed data be stored?
The analyzed data will also be stored on google drive. Links available in the appropriate raw and analyzed data folders on github.
    
### How will the data be shared? Are there any considerations and restrictions for sharing your data?
Potential repositories include UC Davis Dash or ICPSR (Inter-university Consortium for Political and Social Research). The data was publicly available on the UC Davis website so there are no data restrictions. 
