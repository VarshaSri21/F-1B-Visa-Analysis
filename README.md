## Tableau Project - H-1B Visa Analysis

__Overview__

<p align="justify">The H-1B visa is a temporary employment visa that enables American employers to hire foreign workers with specialized skills in fields such as science, engineering, and information technology. This project conducts an analysis of H-1B visa patterns, encompassing a historical overview, policy modifications, and the latest data on visa applications and approvals. It explores the economic influence of the H-1B program on the US labor market, considering its advantages and criticisms. The analysis provides valuable insights into the ongoing discussions surrounding the H-1B program and its impact on US immigration policies and the economy.</p>

__Project Background__

<p align="justify">This project focuses on analyzing H-1B visa patterns, encompassing a historical overview, policy modifications, and the latest data on visa applications and approvals. By visualizing the data using Tableau, we aim to provide a comprehensive understanding of Top & Bottom analysis across different dimensions such as companies, job role and state where there the H-1B is at its rate. The project will assist H-1B visa applicant, Government Officials, Human Resources Professionals, Business leaders, Researchers and Analysts.</p>

__Data Source__

The dataset used for this project is derived from the company's sales database. It contains the following key fields:  

CASE_NUMBER: A unique case number is assigned by the (USCIS) to each H-1B visa application that is submitted by an employer on behalf of a foreign worker.
CASE_STATUS: Analyze the current status of the H-1B visa application, where the values can be
    certified, denied, withdrawn, or pending.
    RECEIVED_DATE: H-1B visa application received date by USCIS.
    DECISION_DATE: The decision date for the H1-B visa application.
    JOB_TITLE: The title of the job offered by the U.S. employer to the foreign worker.
    SOC_TITLE: Standard Occupational Code (SOC) is the occupational title given by foreign workers to the employees.
    BEGIN_DATE: Requested start date of the employment period.
    END_DATE: Requested end date of the employment period.
    EMPLOYER_NAME: Organizational name of the employer who submits the application.
    EMPLOYER_STATE: State where the employer is located.
    WAGE_RATE_OF_PAY: Wage provided by the employer to the foreign workers.
    PREVAILING_WAGE: The average wage paid to workers in similar occupations in the same geographical area.
    
__Project Structure__

The project is structured as follows:
- `2020 - 2022`: This folder contains the raw dataset used for analysis.
- `Path`: This folder contains the dataset which is used for the Hexmaps visualization.
-  `H-1B_Visa_Analysis using Tableau.twbx`: The Tableau workbook file containing all the data, visualizations, and resources for interactive dashboards.
- `H-1B Visa Analysis Report.pdf`: This filr contains the documentation of the tableau project.
- `H-1B Visa Analysis.pptx`: This powerpoint contains the presentation for this project.
    
__Key Findings__

- The total number of H-1B visa applications, the number of employees associated with the visas, and the count of states involved.
- Check the case status by filtering the employer's name.
- Aggregate wages based on the employer's name and job title.
- Analyze the details of the top 5 employers, including their presence in the job market and the states they operate in.
    ![[Pasted image 20230527181142.png]]
    ![[Pasted image 20230527181151.png]]
- Explore the details of the bottom 5 employers, including their presence in the job market and the states they operate in.

__Project Outputs__

The Tableau workbook (H-1B_Visa_Analysis using Tableau.twbx) includes the following key visualizations and dashboards:
- H-1B Visa Statistics Dashboard: Provides an overview of the number of employers, states, and applications received.
- Case Status Dashboard: Visualizes the case status of the visa year-wise using text charts, bar charts, and allows filtering by the employer's name.
- Employer and Job Details Dashboard: Provides aggregated information on wages and the number of applications for each company, categorized by job role.
- Top Results Dashboard: Displays the top 5 employers' names, job markets, and states with the highest H-1B Visa numbers.
- Bottom Results Dashboard: Visualizes the bottom 5 employers' names, job markets, and states with the lowest H-1B Visa numbers.

__Technical Requirements__

To view and interact with the Tableau workbook, you will need the following:
Tableau Desktop or Tableau Reader (version 2021.2.0 or later)
    Minimum system requirements:
- Operating System: Windows 10 or macOS Mojave (or later)
- Processor: Intel Core i3 or equivalent
- RAM: 8 GB or higher
- Disk Space: 1.5 GB or higher

## __Getting Started__

1) Download and install Tableau Desktop or Tableau Reader from the official Tableau website.
2) Clone or download this repository to your local machine.
3) Open Tableau Desktop or Tableau Reader and navigate to the location where you saved the sales_analysis.twb file.
4) Open the workbook and start exploring the dashboards and visualizations.

__Conclusion__

<p align="justify">This Tableau project offers the analysis of H-1B visa data provides an opportunity to uncover significant patterns and trends within the program. By examining information on visa applications and approvals, one can gain insights into the geographic and industry distribution of H-1B sponsors. Moreover, it allows for a comprehensive assessment of the program's impact on the US job market and wages. The interactive nature of the dashboards and visualizations facilitates a user-friendly exploration of the data, resulting in more profound insights.</p>

__Contact Information__
For any questions or feedback regarding this project, please contact:

Name: Varsha Sri Madhusudhanan
    Email: varshasri.madhu@gmail.com
