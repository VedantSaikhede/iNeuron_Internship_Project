
# Heart Disease Diagnostic Analysis

- Developed and implemented a business intelligence and machine learning model of a heart disease prediction project, resulting in improved accuracy and scalability of the system.
- Utilized Python for data cleaning and transformation, enabling faster and more accurate analysis.
- Generated detailed report on project findings, providing key insights to management.

## Documentation
- [Architecture Design](https://github.com/VedantSaikhede/Internship_Project/blob/main/Documentation/Architecture_Design.pdf)
- [Wireframe Design](https://github.com/VedantSaikhede/Internship_Project/blob/main/Documentation/Wireframe_Document.pdf)
- [High Level Design](https://github.com/VedantSaikhede/Internship_Project/blob/main/Documentation/High_Level_Design.pdf)
- [Low Level Design](https://github.com/VedantSaikhede/Internship_Project/blob/main/Documentation/Low_Level_Design.pdf)
- [Project Report](https://github.com/VedantSaikhede/iNeuron_Internship_Project/blob/main/Documentation/Projet_Report.pdf)
- [College_Internship_Report](https://github.com/VedantSaikhede/iNeuron_Internship_Project/blob/main/Documentation/Vedant_Internship_Report.pdf)
- [Experience Letter](https://github.com/VedantSaikhede/Internship_Project/blob/main/Documentation/Letter/iNeuron_internship_Experience_Letter.pdf)
- [Dataset](https://github.com/VedantSaikhede/Internship_Project/blob/main/Code/Dataset/heart_disease_dataset.csv)
## Code
[iNeuron Internship Vedant Saikhede.ipynb](https://github.com/VedantSaikhede/iNeuron_Internship_Project/blob/main/Code/iNeuron%20Internship%20Vedant%20Saikhede.ipynb)

Platform : JupyterLab
```python
#Importing Libraries
import numpy as np
import matplotlib.pyplot as plt 
import pandas as pd 
import seaborn as sns 
sns.set_style('whitegrid')

#Extracting CSV Dataset From System using Pandas Library
data=pd.read_csv('heart_disease_dataset.csv')
data

#Checking NULL Values
data.isnull().sum()
num=data.groupby('num').size()
num

#Converting Numerical Data into Categorical Data
def heart_disease(row):
    if row==0:
        return 'Absence'
    elif row==1:
        return 'Presence'

#Pie Chart Creation of Heart Disease Population % using MatplotLib
plt.figure(figsize=(10,7))
plt.pie(hd, labels=['Absence','Presence'], autopct='%0.0f%%')
plt.title('Heart Disease Population %', fontsize=20)
plt.show()
```
## Conclusion of Anaysis 
`45.87%` of People suffer from heart disease.

`Elderly Aged Men` are more `(50 to 60 Years)` and `Females are more in 55 to 65 Years` Category

`Males` are more prone to heart disease.

`Elderly Aged People` are more prone to heart disease.

`People having asymptomatic chest pain` have a higher chance of heart disease.

`High cholesterol levels` in people having heart disease.

`Blood Pressure increases` between the age of 50 to 60 and somehow continues till 70.

`Cholesterol and maximum heart rate` Increased in the `age group of 50-60.`

`ST depression` mostly increases between the `age group of 30-40`.


## Screenshots
![App Screenshot](https://github.com/VedantSaikhede/Internship_Project/blob/main/Screenshot/Screenshot%20(661).png)
![App Screenshot](https://github.com/VedantSaikhede/Internship_Project/blob/main/Screenshot/Screenshot%20(662).png)
![App Screenshot](https://github.com/VedantSaikhede/Internship_Project/blob/main/Screenshot/Screenshot%20(663).png)
![App Screenshot](https://github.com/VedantSaikhede/Internship_Project/blob/main/Screenshot/Screenshot%20(664).png)
![App Screenshot](https://github.com/VedantSaikhede/Internship_Project/blob/main/Screenshot/Screenshot%20(665).png)
![App Screenshot](https://github.com/VedantSaikhede/Internship_Project/blob/main/Screenshot/Screenshot%20(666).png)
![App Screenshot](https://github.com/VedantSaikhede/Internship_Project/blob/main/Screenshot/Screenshot%20(667).png)
![App Screenshot](https://github.com/VedantSaikhede/Internship_Project/blob/main/Screenshot/Screenshot%20(668).png)
![App Screenshot](https://github.com/VedantSaikhede/Internship_Project/blob/main/Screenshot/Screenshot%20(669).png)
![App Screenshot](https://github.com/VedantSaikhede/Internship_Project/blob/main/Screenshot/Screenshot%20(670).png)
![App Screenshot](https://github.com/VedantSaikhede/Internship_Project/blob/main/Screenshot/Screenshot%20(671).png)
![App Screenshot](https://github.com/VedantSaikhede/Internship_Project/blob/main/Screenshot/Screenshot%20(672).png)
![App Screenshot](https://github.com/VedantSaikhede/Internship_Project/blob/main/Screenshot/Screenshot%20(673).png)
![App Screenshot](https://github.com/VedantSaikhede/Internship_Project/blob/main/Screenshot/Screenshot%20(674).png)
![App Screenshot](https://github.com/VedantSaikhede/Internship_Project/blob/main/Screenshot/Screenshot%20(675).png)
![App Screenshot](https://github.com/VedantSaikhede/Internship_Project/blob/main/Screenshot/Screenshot%20(676).png)
