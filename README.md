# FIFA 21 Dataset Cleaning & Exploration

This project involves cleaning and exploring the FIFA 21 dataset, specifically focused on transforming messy raw data into a clean format. The tasks completed during the cleaning process include converting certain columns to numerical forms, stripping unnecessary characters, and ensuring the dataset is prepared for further analysis or machine learning.

## Dataset

- The dataset contains FIFA 21 players' information with several columns requiring transformation, cleaning, and correction for accurate use in analytics.

## Key Tasks Performed

### 1. Convert Height and Weight Columns
- The 'Height' column was originally in a string format (e.g., `5'8"`) and was converted into centimeters.
- The 'Weight' column, which was in pounds (e.g., `150lbs`), was converted into kilograms.

### 2. Remove Unnecessary Newline Characters
- Some columns contained unnecessary newline characters which were removed using string manipulation techniques.

### 3. Players in a Club for More than 10 Years
- Based on the 'Joined' column, players who have been playing at a club for more than 10 years were identified using date calculations.

### 4. Convert Value, Wage, and Release Clause Columns
- The 'Value', 'Wage', and 'Release Clause' columns contained string values such as "M" for millions or "K" for thousands. These were converted into numerical values by multiplying by 1,000,000 or 1,000 respectively.

### 5. Remove Stars from Certain Columns
- Some columns contained 'star' characters (e.g., 4★). These stars were stripped, and the values were converted into numerical representations.

## Requirements

- jupyter notebook
- Python
- Pandas
- NumPy

## Screenshots

![Screenshot (106)](https://github.com/user-attachments/assets/c6e50a38-7a6e-4216-b293-0d61b24625da)
![Screenshot (105)](https://github.com/user-attachments/assets/7c1fd6dd-ea97-4393-9eeb-42aa6815d7fa)
![Screenshot (104)](https://github.com/user-attachments/assets/1342bb21-6ee8-4d76-a4e7-f807bbe51f6c)
![Screenshot (103)](https://github.com/user-attachments/assets/9d9faa84-a409-429b-b225-ea2c1ba091c3)
![Screenshot (107)](https://github.com/user-attachments/assets/9f3dec71-080f-4fd7-99f9-29d74cc8c272)

## Contributing

Feel free to fork this repository and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

## Authors

- [@HaroonRasheed](https://github.com/Haroon1056)


