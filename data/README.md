# Data
-   **[Dataset]**: U.S. Department of Education College Scorecard (2022–2023). This dataset includes institution-level data on tuition, student demographics, financial aid, and post-graduation outcomes. The data are publicly available from the U.S. Department of Education at collegescorecard.ed.gov. This dataset is extremely large, so in order to import it to Github, I separated the file into collections of 8-10 states per csv, then uploaded and combined the data in Github. In order to make the dataset more managble, I did extensive data cleaning which is described below. Since there are still over 1,000 columns in the dataframe, I will detail the more important columns which I plan to use for data analysis and update this if I use columns that are not listed here.
.

# Codebook for [chosen] Dataset

## Variable Names and Descriptions:

-   **INSTNM**: Institution name
-   **STABBR**: 2-letter state abbreviation
-   **HIGHDEG**: Highest degree awarded:
        0 Non-degree-granting
        1 Certificate degree
        2 Associate degree
        3 Bachelor's degree
        4 Graduate degree
-   **PREDEG**: Predominant undergraduate degree awarded:
        0 Not classified
        1 Predominantly certificate-degree granting
        2 Predominantly associate's-degree granting
        3 Predominantly bachelor's-degree granting
        4 Entirely graduate-degree granting
-   **CONTROL**: Control of institution (IPEDS) (i.e. private, public)
-   **COSTT4_A**: Average cost of attendance (academic year institutions)
-   **TUITIONFEE_IN**: In-state tuition and fees
-   **TUITIONFEE_OUT**: Out-of-state tuition and fees
-   **TUITFTE**: Net tuition revenue per full-time equivalent student
-   **C150_4**: Completion rate for first-time, full-time students at four-year institutions (150% of expected time to completion)
-   **C150_4_POOLED**: Completion rate for first-time, full-time students at four-year institutions (150% of expected time to completion), pooled for two year rolling averages
-   **RET_FT4**: First-time, full-time student retention rate at four-year institutions
-   **COMP_ORIG_YR4_RT**: Percent completed within 4 years at original institution
-   **COMP_ORIG_YR6_RT**: Percent completed within 6 years at original institution
-   **RPY_1YR_RT**: Fraction of repayment cohort who are not in default, and with loan balances that have declined one year since entering repayment, excluding enrolled 
        and military deferment from calculation. (Rolling averages)
-   **DEP_INC_AVG**: Average family income of dependent students in real 2015 dollars.
-   **GRAD_DEBT_MDN**: The median debt for students who have completed
-   **COUNT_WNE_P10**: Number of students working and not enrolled 10 years after entry
-   **MD_EARN_WNE_P10**: Median earnings of students working and not enrolled 10 years after entry
-   **COUNT_WNE_INC1_P10**: Number of students working and not enrolled 10 years after entry in the lowest income tercile $0-$30,000
-   **COUNT_WNE_P6**: Mean earnings of students working and not enrolled 6 years after entry
-   **MD_EARN_WNE_P6**: Median earnings of students working and not enrolled 6 years after entry
-   **COUNT_WNE_INC1_P6**: Number of students working and not enrolled 6 years after entry in the lowest income tercile $0-$30,000

## Data Types:

-   **INSTNM**: string



