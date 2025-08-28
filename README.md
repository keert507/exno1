# Exno:1
Data Cleaning Process

# AIM
To read the given data and perform data cleaning and save the cleaned data to a file.

# Explanation
Data cleaning is the process of preparing data for analysis by removing or modifying data that is incorrect ,incompleted , irrelevant , duplicated or improperly formatted. Data cleaning is not simply about erasing data ,but rather finding a way to maximize datasets accuracy without necessarily deleting the information.

# Algorithm
STEP 1: Read the given Data

STEP 2: Get the information about the data

STEP 3: Remove the null values from the data

STEP 4: Save the Clean data to the file

STEP 5: Remove outliers using IQR

STEP 6: Use zscore of to remove outliers

# Coding and Output

# 1. Import Required Libraries

<img width="1383" height="142" alt="image" src="https://github.com/user-attachments/assets/11e1f210-31e4-4be3-ac16-9f188ab4cba6" />

# 2. Load Dataset

<img width="1385" height="150" alt="image" src="https://github.com/user-attachments/assets/7bf9f0ef-63bd-4bb4-8ee9-1f209821c3f6" />

# 3. Data Cleaning

# Check for null values

<img width="1389" height="318" alt="image" src="https://github.com/user-attachments/assets/cd72d5db-545a-4754-b9e7-a27ae4757ac4" />

# Handle missing values

<img width="1386" height="159" alt="image" src="https://github.com/user-attachments/assets/239d5b86-7aa5-4b6e-a32d-fbc9634b7c11" />

# Remove duplicates

<img width="1174" height="54" alt="image" src="https://github.com/user-attachments/assets/c1375bc8-8c44-41d6-a347-1996191040f3" />

# Check data types

<img width="1389" height="332" alt="image" src="https://github.com/user-attachments/assets/2511f8e1-1b25-44cd-8c31-71d16d03f268" />

# Convert if needed (example: ensuring numerical)

<img width="1133" height="95" alt="image" src="https://github.com/user-attachments/assets/fad1bf9b-7f32-4391-925d-a0296cfa54c4" />

# 4. Outlier Detection

<img width="1389" height="75" alt="image" src="https://github.com/user-attachments/assets/e9ba0af7-6092-42ab-ab67-f04aab61577d" />

# (a) IQR Method

<img width="1392" height="330" alt="image" src="https://github.com/user-attachments/assets/e9cc49df-ec73-45fd-aec8-c431a8f2a0e7" />

# (b) Z-Score Method

<img width="929" height="277" alt="image" src="https://github.com/user-attachments/assets/a4eaaaa8-2eb8-49f3-9622-a0e2d0c06722" />

# 5. Outlier Removal (using IQR method here)

<img width="1373" height="145" alt="image" src="https://github.com/user-attachments/assets/04209ac6-079c-4580-9e86-a7deab86bfc6" />

# 6. Visualization (Boxplot)

<img width="1359" height="536" alt="image" src="https://github.com/user-attachments/assets/1905312e-8e33-4eec-9111-f92c21f80a7f" />


<img width="1391" height="206" alt="image" src="https://github.com/user-attachments/assets/7e3de2d2-dfdc-48b1-98b1-529779fea44d" />



# Result

Thus, we have read the given data and performed data cleaning and saved the cleaned data to a file successfully.
