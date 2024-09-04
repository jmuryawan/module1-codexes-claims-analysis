### steps taken in anaylsis:
1. printed out the table and columns seperately
2. calculated frequency for each selected column
3. looked for missing data in the table as a whole and individual columns
4. handled missing data by replacing the data (with mean, NULL, 0)or dropping them

### purpose of each part of code:
comments can be found throughout the code explaining each line of code

### key findings from analysis (patterns and anomalies)
there is a lot of missing enrollment information and healthcare claims
the most common codes found were HCPCS, DRG, and ICD for inpatient data

### challenges:
main challenge was figuring our how to deal with the missing data. zoomed and consulted with prof. williams who gave some pointers.
did a "technical" google search on how to deal with missing data on python using pandas. used information from
Stack Overflow and GeeksforGeeks to utilize .isnull, .isnull().sum , .fillna, and .dropna

### implications of findings for healthcare providers and policy makers
sample could be biased because it doesn't adequately represent the population
missing data may negatively impact conclusions 
healthcare workers should more carefully input information
