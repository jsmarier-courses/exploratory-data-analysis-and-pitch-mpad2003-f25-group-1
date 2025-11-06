**November 2, 2025**<br>
**MPAD2003A Introductory Data Storytelling**<br>
**Mariia Bondar**<br>
**Taha Saffih**<br>
**Yusra Ghani**<br>
**Beracah Okere**<br>
**Presented to Jean-Sébastien Marier**<br>

# Exploratory Data Analysis (EDA) & Pitch


## Foreword

For this assignment, you must extract data from a dataset provided by the instructor. You must then clean and analyze the data, create exploratory charts/visualizations, and find a potential story idea. Your assignment must clearly detail your process. You are expected to write about 1500-2000 words, and to include several screen captures showing the different steps you went through. Your assignment must be written with the Markdown format and submitted on GitHub Classroom.

I have been assigning different versions of this project to my digital journalism and data storytelling students for a few years now. Its structure was inspired by the main sections/chapters of [*The Data Journalism Handbook*](https://datajournalism.com/read/handbook/one/). This version was further inspired by the [Key Capabilities in Data Science](https://extendedlearning.ubc.ca/programs/key-capabilities-data-science) program offered by the University of British Columbia (UBC).

**Here are some useful resources for this assignment:**

* [GitHub's *Basic writing and formatting syntax* page](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
* [The template repository for this assignment in case you delete something by mistake](https://github.com/jsmarier/jou4100_jou4500_mpad2003_project2_template)


## 1. Introduction

In this document, we are going to complete our Exploratory Data Analysis and Pitch assignment based on the 2021 Long Form Census - Ward Data dataset collected by Statistics Canada and published on the City of Ottawa’s open data portal on November 28, 2023. We will be analyzing demographic data of 25% of households in Ottawa.  

The 2021 long-form Census questionnaire was distributed to 25% of all households in Ottawa. The data was collected by Statistics Canada. The dataset covers all 24 electoral districts (wards) within Ottawa and the City of Ottawa. It includes various categories such as marital status, religion, place of birth, among others, along with their totals. The dataset contains 2,602 rows. It uses discrete variables (Statistics: Power from Data!, Section 4.2). 

[*The original dataset on Open Ottawa*](https://open.ottawa.ca/datasets/ottawa::2021-long-form-census-ward-data/explore). 

[*CSV version from the GitHub portal*](https://raw.githubusercontent.com/jsmarier/files-for-course-assignments/refs/heads/main/2021_Long_Form_Census_-_Ward_Data.csv). 

The main sections of this assignment are importing, analyzing, and cleaning data; conducting an exploratory data analysis; finding a potential story; and researching other sources to tell it better. 

## 2. Getting Data

To import data into Google Sheets, we copied the URL of the dataset. Then, we selected an empty cell at the beginning of the spreadsheet (e.g., cell A1) and entered the formula =IMPORTDATA("URL"). We replaced "URL" with the copied URL, including the quotation marks. Finally, we pressed Enter to import the dataset.   

![](importdata_screenshot.png)<br>
*Figure 1: The "Import file" prompt on Google Sheets.*

[*Public link to our Google Sheets*](https://docs.google.com/spreadsheets/d/1lZDdngeOup1NO11wTbPw5DKi6v85-Oq4eJjfzvdI-5g/edit?usp=sharing). 
 

General observations regarding the dataset: 

* 26 columns 
* 2,602 rows 
* Discrete variables 
* Demographic characteristics 

General observations regarding the dataset: 

26 columns (including characteristics)  

2,602 rows  

Discrete variables 

Demographic characteristics 

The dataset appears to be somewhat unclean. It includes the City of Ottawa, represented by the mayor, as well as 24 wards represented by their respective councillors. This suggests that the values for the City of Ottawa are regarded as the sum of its individual wards' values. We have created a separate column using the formula = SUM(C3:Z3) to calculate the total for the wards' values in the "Total - Age Groups of the Population - 25% Sample Data." According to this calculation, the City of Ottawa should have 1,000,940 people in that category ; however, our sum shows 1,000,930, leading to a discrepancy of 10 people. This difference appears in several of the initial columns, ranging from 5 to 15. Clarification is needed as to why there is a discrepancy, considering that the City of Ottawa is composed of 24 wards. 

  

Column B (City of Ottawa) displays either total or average figures derived from the 24 wards across all other columns. These are discrete data points representing the number of people in specific categories, such as the First Nations population within the City of Ottawa. 

  

Column C (Ward 1) indicates the number or average number of individuals in each category for residents of Orléans East-Cumberland – Ward 1. It is a discrete data.  

  

Similarly, Column Z (Ward 24) shows the number or average number of individuals in each category for residents of Barrhaven East – Ward 24. It is a discrete data.  

 



## 3. Understanding Data

### 3.1. VIMO Analysis

Use three hashtag symbols (`###`) to create a level 3 heading like this one. Please follow this template when it comes to level 1 and level 2 headings. However, you can use level 3 headings as you see fit.

Insert text here.

Support your claims by citing relevant sources. Please follow [APA guidelines for in-text citations](https://apastyle.apa.org/style-grammar-guidelines/citations).

**For example:**

As Cairo (2016) argues, a data visualization should be truthful...

### 3.2. Cleaning Data

Insert text here.

### 3.3. Exploratory Data Analysis (EDA)

Insert text here.

**This section should include a screen capture of your pivot table, like so:**

![](pivot-table-screen-capture.png)<br>
*Figure 2: This pivot table shows...*

**This section should also include a screen capture of your exploratory chart, like so:**

![](chart-screen-capture.png)<br>
*Figure 3: This exploratory chart shows...*

## 4. Potential Story

Insert text here.

## 5. Conclusion

Insert text here.

## 6. References

Include a list of your references here. Please follow [APA guidelines for references](https://apastyle.apa.org/style-grammar-guidelines/references). Hanging paragraphs aren't required though.

**Here's an example:**

Bounegru, L., & Gray, J. (Eds.). (2021). *The Data Journalism Handbook 2: Towards A Critical Data Practice*. Amsterdam University Press. [https://ocul-crl.primo.exlibrisgroup.com/permalink/01OCUL_CRL/hgdufh/alma991022890087305153](https://ocul-crl.primo.exlibrisgroup.com/permalink/01OCUL_CRL/hgdufh/alma991022890087305153)
