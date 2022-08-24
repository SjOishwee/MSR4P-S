# MSR4P-S
Dataset: An Exploratory Study on the Relationship of Smells and Design Issues with Software Vulnerabilities
To ESEC/FSE 2022 Reviewers

This is a temporary location for the replication package. The final destination for these will be a GitHub account. Due to the double blind reviews, we couldn’t use the GitHub account and had to copy the files over here.

Thank you.
The Authors.



1.	Definition.pdf: It contains the definition of all studied smells and design issues.  
2.	Extracted_vulnerabilities: This folder contains extracted vulnerabilities of nine systems. Each CSV file contains the name of the vulnerability (e.g, Information Exposure, Timing Attack), CVE-ID, affected and fixed version range, affected classes, and GitHub link for fixing the vulnerabilities. 
3.	GetSmells_dataset: 
a.	chi_square_getsmelss.ipnb: This Python code for the Chi-square test includes the script for data processing of GetSmells’s data till Chi-square and Cramer’s V calculation of that data. 
b.	Apache System’s_name: These folders include the collected smells’ frequency for each version of each system. For example, Apache batik —> 1.0_smells-classes-metrics-all.csv —-> All the smell’s from the GetSmells tool for all the classes and methods of Apache batik version 1.0.
i.	all_chi : This folder contains the calculated frequency of each smell in the vulnerable (vuls_chi.csv) and non-vulnerable (non_vuls_chi.csv) classes in each version of the system. 
4.	PMD_dataset:
a.	Chi_square_getsmelss.ipnb: This Python code for the Chi-square test includes the script for data processing of PMD’s data till Chi-square and Cramer’s V calculation of that data. 
b.	System’s_name: This folder contains: 
i.	shell_script_system_name.py: The script for collecting code smells and design issues from the PMD tool. 
ii.	all_chi : This folder contains the calculated frequency of each code smell and design issues in the vulnerable and non-vulnerable classes in each version of the system.  
      5.  MSR4P&S2022_result: 
a.	Chi_sqare_test: It contains the result for the chi-square test of smells and design issues.
b.	Cramer’s V:  It contains the result for the Cramer’s V of smells and design issues.

