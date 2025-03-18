# *Midterm Lab Task 2: Data Cleaning and Transform Using Power Query Editor*💜

## Dataset Before Cleaning and Transformation 

![image](https://github.com/user-attachments/assets/8557355b-cd85-485a-b485-0b602906c021)

## 🗃️*Data Cleaning Steps:*
1. Download and Load Data:

- Download Uncleaned_DS_jobs.csv and open it in Excel using Data → New Query → Open File.

2. Duplicate Data:
- Duplicate the raw data in Power Query.

3. Data Cleaning:

- Salary Estimate: Extract values before parentheses.
- Min/Max Salary: Create columns for Min and Max salary from Salary Estimate.
- Role Type: Create a new column to categorize job titles.
- Location: Split and fix special location cases (e.g., "New Jersey" → "NJ").
- Company Size: Split the size column into Min and Max company sizes.
- Negative Values: Remove negative numbers from relevant columns.
- Clean Names: Remove extra text (e.g., "Rates") from company names.
- Remove Descriptions: Delete the descriptions column.

4. Copy Steps:

- Copy the applied steps for your portfolio.
## ⭐*Reshape and Group Data:*

1. Duplicate for Role Type:

- Duplicate the raw data and select Role Type, Min Sal, and Max Sal.
- Multiply Min and Max Sal by 1000 and group by Role Type to find averages.

2.Reference for Size:

- Create a reference, select Size, Min Sal, and Max Sal, then group by Size to find averages.

3. State Mapping:

- Merge State Mapping with the raw data by State Abbreviation and rename the column to State Full Name.
4. Reference for State:
  
- Create a reference, select State Full Name, Min Sal, and Max Sal, and group by State Full Name to find averages.

## Final Output 
![image](https://github.com/user-attachments/assets/3796abd6-1825-4330-a0dc-308dad13cc43)
![image](https://github.com/user-attachments/assets/79887d67-4a5d-4917-97a8-a9cd9d28fa80)
![image](https://github.com/user-attachments/assets/a3bc1fbd-2b4a-4b25-b34d-b5df5ed3ad0d)
![image](https://github.com/user-attachments/assets/a25f4c55-7f9c-4c1e-bfec-feb617f5eaee)

##   Query Dependencies
![image](https://github.com/user-attachments/assets/2ed779b7-a495-4cd3-960f-86c6bf8dbe1b)
