# EDA Project: Gynaecologist Data Analysis
## Overview
- This project involves exploratory data analysis (EDA) on a dataset containing information about gynaecologists in Hyderabad. The primary goal is to clean, analyze, and visualize the data to derive meaningful insights regarding the gynaecologists' experience, fees, availability, and education.

# Dataset
- The dataset includes the following columns:

- `Name:` Name of the gynaecologist
- `Specialization:` Area of specialization
- `Experience (in years):` Years of experience in the field
- `Education:` Educational qualifications
- `Fee at clinic:` Consultation fee at the clinic
- `Online Fee:` Consultation fee for online appointments
- `Clinic Name:` Name of the clinic
- `Area:` Location of the clinic
- `Available From:` Start time of availability
- `Available Till:` End time of availability
- `City:` City of practice
- `Total Fee:` Total fee calculated from clinic and online fees
- `Number of Hrs. Available:` Total hours available for consultation
Key Steps in the Analysis
- `Data Importing:` The dataset is imported using Pandas for analysis.
# Data Cleaning:
- Dropping unnecessary columns.
- Handling missing values by filling them with appropriate defaults (e.g., 'Not Mentioned', 'Unknown', or 0).
Converting data types for numerical analysis.
# Feature Engineering:
- Calculating the total fee by summing the clinic and online fees.
- Creating a new column for the number of hours available based on the available time.
# Data Visualization:
- Generating histograms, count plots, pie charts, and violin plots to visualize the distribution of experience, fees, and availability.
- Analyzing trends and patterns in the data to provide insights into the gynaecology sector in Hyderabad.
# Insights
- The analysis reveals trends in the experience levels of gynaecologists, with a notable concentration of practitioners having 20-30 years of experience.
- The fee structure is explored, highlighting the differences between clinic and online consultation fees.
- Availability patterns are examined to understand the typical working hours of gynaecologists.
# Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
# Conclusion
This EDA project provides a comprehensive overview of gynaecologists in Hyderabad, offering valuable insights into their experience, fees, and availability. The findings can be beneficial for patients seeking gynaecological services and for healthcare professionals looking to understand the market landscape.
