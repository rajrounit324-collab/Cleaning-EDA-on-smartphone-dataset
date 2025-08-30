# Objective:
Paying meticulous attention to detail, I performed a thorough cleaning and standardization of a smartphone dataset. From ensuring consistency, refining formatting, handling missing values to rectifying inaccuracies in various specifications. Furthermore, I meticulously optimized the dataset's structure by addressing tidiness issues, ensuring it not only adheres to high accuracy standards but also elevates clarity and usability for analysis. Further did an EDA and prepared a report highlighting the valuable insights around the cleaned dataset.

# About Uncleaned Dataset 
This uncleaned dataset contains 1020 rows × 11 columns

![Screenshot 2024-03-10 162810](https://github.com/arun-iiests/Cleaning_-_EDA_on_Smartphone_Dataset/assets/124171557/abe129ad-db0a-4112-998c-c6213dc8d850)

#  Data Cleaning and Transformation
In the process of cleaning a smartphone dataset, I tackled various issues to ensure the data is accurate and easy to understand. 
1. I fixed inconsistencies in the brand names, standardized the price format, and filled in missing ratings. 
2. I corrected errors in processor details for certain Samsung phones, identified and adjusted an iPod entry, 
3. Fixed problems in memory, battery, and display information across multiple rows. 
4. I consolidated information on foldable phones for clarity and refined the camera data to represent counts accurately.
5. I also sorted out problems in the card and operating system columns, addressing missing values.
6. Additionally, I made sure that the price and rating columns had the correct data type for consistency.
7. To make things tidier, I split the 'sim' column into separate columns for 5G, NFC, and IR Blaster.
8. I also divided the 'ram' column into 'RAM' and 'ROM' and parsed the 'processor' column into 'processor name', 'cores', and 'cpu speed'.
9. The 'battery' column was separated into 'battery capacity' and 'fast charging availability'
10. display was broken down into 'size', 'resolution_width', 'resolution_height', and 'frequency'.
11. Lastly, I divided the 'camera' column into 'front' and 'rear' cameras and the 'card' column into 'supported' and 'extended_upto'.
    
These changes not only improved the data quality but also made the overall dataset more organized and user-friendly.

## Cleaned Dataset
After cleaning and transforming  uncleaned dataset we got this informative and meaningful dataset having 980 rows and 25 columns

![Screenshot 2024-03-10 165102](https://github.com/arun-iiests/Cleaning_-_EDA_on_Smartphone_Dataset/assets/124171557/c7e5ceb8-6103-4e4c-9d3d-e2522214e88e)
![Screenshot 2024-03-10 165143](https://github.com/arun-iiests/Cleaning_-_EDA_on_Smartphone_Dataset/assets/124171557/4dd0a074-b1fe-4fe1-b6a2-57a2e0d35008)

## EXploratory Data Analysis(EDA)
[Click Me](https://jovian.com/arun1151kumar/smartphone-eda-unleashed) for Complete EDA Report

# Conclusion:

This project contributes significantly to the data analysis and data science learning process by providing hands-on experience in real-world data cleaning and exploratory data analysis (EDA). It covers a diverse range of tasks, including handling inconsistencies in data entries, resolving missing values, correcting data types, and organizing the dataset for improved clarity. By working on these aspects, I developed essential skills in data preprocessing, cleaning, and visualization, gaining practical insights into the challenges and solutions encountered in data science projects. Additionally, the project emphasizes tidiness and structure, fostering an understanding of best practices for organizing datasets. Overall, engaging in this project enhanced both technical and problem-solving skills, preparing for real-world applications in the field of data science and data analysis.

