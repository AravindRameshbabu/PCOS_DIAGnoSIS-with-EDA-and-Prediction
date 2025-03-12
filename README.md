# PCOS_DIAGnoSIS-with-EDA-and-Prediction

PCOS DIAGNOSIS EXPLORATORY DATA ANALYSIS AND PREDICITION USING MACHINE LEARNING ALGORITHMS 

DATA: PCOS DIAGNOSIS 
SOURCE: KAGGLE 
DATA SHAPE: 1000,6
Features:
Age (years): The age of the patient, ranging from 18 to 45 years.
BMI (kg/m²): The Body Mass Index, which is a measure of body fat based on height and weight, ranging from 18 to 35.
Menstrual Irregularity (binary): A binary indicator showing whether the patient has irregular menstrual cycles (0 = No, 1 = Yes).
Testosterone Level (ng/dL): The level of testosterone in the patient's blood, an important hormonal indicator of PCOS, ranging from 20 to 100 ng/dL.
Antral Follicle Count: The number of antral follicles detected during an ultrasound, ranging from 5 to 30, which helps in assessing ovarian reserve and PCOS presence.
Target Variable:
PCOS Diagnosis (binary): A binary indicator of whether the patient has been diagnosed with PCOS (0 = No, 1 = Yes), based on a combination of risk factors such as high BMI, testosterone levels, menstrual irregularity, and antral follicle count.

Insights:
The data has shape of 1000 rows and 6 columns, moreover the data is clean and it has no outliers, while comparing the relationship between the age and BMI we often don't get the desired results so, with use of binning process we can expect the desired relationship plots.
Eg:
 

	 The age group of 31 - 40 have the high BMI values while comparing it with other bin values, and again the age group 31-40 have the high Menstrual Irregularity and testosterone levels.

	While comparing the BMI values and menstrual Irregularity, it clearly shows that the people with 21-30 BMI values have high count of menstrual irregularity.

	While comparing the age bins and testosterone levels we can see the medium levels of testosterone is getting spiked at all age bins and as again the age bin 31- 40 have high level of medium level of testosterone

	While comparing the menstrual Irregularity and testosterone levels we can see that people who have irregular menstruation are having the spike on the testosterone levels

	The suprising factor is the the age bins between 21 - 30 have high chances of having PCOS issues







