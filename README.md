# Basic Information- Introduction
1. Data File Name:   
  Opera-Company-IRS-990-Merge
2. Dataset Name: 
  N/A
3. Other Files Related to These Data (Other Files in Set, e.g.):
  * ["Exempt Organizations Business Master File Extract (EO BMF)"](https://www.irs.gov/charities-non-profits/exempt-organizations-business-master-file-extract-eo-bmf)
  * "Opera_List_2017" which can be found in this repository. 
4. Author(s) Names (or person responsible for collecting the data): 
  Emily Edwards
  Jonathan Cain 
5. Author(s) ORCID IDs: 
  N/A
6. Contact Information: 
  Emily Edwards
  Planning, Public Policy and Management Masters Candidate
  University of Oregon
  Email: 
    eedward3@uoregon.edu

  Jonathan Cain
  Research and Instructional Services
  University of Oregon
  Mail:
    1229 University of Oregon 
    Libraries, Eugene, OR 97403-1299
  Email: 
    jocain@uoregon.edu
7. Date(s) of Data Collection:
  01/2017-02/2017
8. Date File was Created:
  2/17/2017
9. Date(s) and Nature of Updates: 
  N/A

# Basic Information- Data Use
10. Citations of Publications Using These Data: 
  N/A
11. Digital Object Identifiers (DOIs) of Publications Using These Data: 
  N/A
12. Purpose of Collection:
  The purpose of this script is to merge a compiled list of all Opera Companies in the US with their IRS 990 data, if available. 

# Basic Information- Data Description
13. Key Words and Definitions:
  * IRS: Internal Revenue Service in the US
  * Form 990: The "Return of Organization Exempt From Income Tax", of Form 990 is a United States Internal Revenue Service form that provides the public with financial information about a nonprofit organization. It is often the only source of such information.
  * EIN: Employer Identification Number given to registered tax exempt nonprofit organizations
14. Example Data in Set:
|EIN|NAME|ICO|STREET|STATE|ZIP|GROUP|SUBSECTION|AFFILIATION|CLASSIFICATION|ETC.|
|---|---|---|---|---|---|---|---|---|---|---|
|231352001|ACADEMY OF VOCAL ARTS| |1920 SPRUCE ST|PHILADELPHIA|PA|19103-6613|0|3|3|1000| |
15. Lineage of Dataset: 
  N/A
16. Geographic Information: 
  N/A

# Methodological Information
17. Method description, links or references to publications or other documentation containing experimental design or protocols used in data collection:
  * This data relies on the published IRS 990 data which is provided at ["Exempt Organizations Business Master File Extract (EO BMF)"](https://www.irs.gov/charities-non-profits/exempt-organizations-business-master-file-extract-eo-bmf)
18. Any instrument-specific information needed to understand or interpret the data: 
  N/A
19. Standards and calibration information, if appropriate: 
  N/A
20. Describe any quality-assurance procedures performed on the data: 
  N/A
21. Definitions of codes or symbols used to note or characterize low quality/questionable/outliers that people should be aware of: 
  N/A
22. People involved with sample collection, processing, analysis and/or submission: 
  N/A

# Data-Specific Information
23. Full names and definitions (spell out abbreviated words) of column headings for tabular data
  * EIN: Employer Identification Number through the Internal Revenue Service
  * NAME.x: Name of the company as listed in the Opera Company dataset
  * NAME.y:	Name of the company as provided by IRS data
  * ICO:	In care of name; to who any correspondence should be directed towards
  * STREET:	Street address
  * CITY:	City
  * STATE:	State
  * ZIP:	Zip code
  * GROUP:	Group Extension Number
  * SUBSECTION:	Subsection Code
  * AFFILIATION:	Affiliation Code
  * CLASSIFICATION:	Classification Code(s)
  * RULING:	Ruling date
  * DEDUCTIBILITY:	Deductibility Code
  * FOUNDATION:	Foundation Code
  * ACTIVITY:	Activity Code(s)
  * ORGANIZATION:	Organization Code
  * STATUS:	Exempt Organization Status Code
  * TAX_PERIOD:	Tax period
  * ASSET_CD:	Asset Code
  * INCOME_CD:	Income Code
  * FILING_REQ_CD:	Filing Requirement Code
  * PF_FILING_REQ_CD:	PF Filing Requirement Code
  * ACCT_PD:	Accounting period
  * ASSET_AMT:	Asset amount
  * INCOME_AMT:	Income amount
  * REVENUE_AMT:	Form 990 revenue amount
  * NTEE_CD:	National Taxonomy of Exempt Entities (NTEE) Code
  * SORT_NAME:	Sort name
24. Units of measurement: 
  N/A
25. Definitions for codes or symbols used to record missing data:
  * NO EIN: An EIN was not available for that Opera Company, however they *are* a nonprofit organization
  * N/A: There was no data available to merge with that Opera Company
26. Specialized formats or abbreviations used: 
  N/A

# Sharing/Access Information
27.	Licenses or restrictions placed on the data: 
  MIT License
28.	Links to publications that cite or use the data: 
  N/A
29.	Links to other publicly accessible locations of the data: 
  N/A
30.	Recommended citation for the data:

31.	Information about funding sources that supported the collection of the data: 
  N/A
