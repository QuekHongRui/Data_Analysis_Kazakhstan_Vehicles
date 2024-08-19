# Kazakhstan Vehicles Data Analysis in Python

This ad-hoc analysis project investigates vehicles in Kazakhstan. It uses a data set of **10,885** vehicles which contains information like the vehicle driver's particulars, vehicle details, insurance period and premium as well as road accident details, if any. This project aims to answer specific questions related to the data through data manipulation *(eg filtering, aggregation, sorting operations)*, so as to synthesise findings that might be of interest to business stakeholders. 

This project uses the **pandas** and **NumPy** libraries for data manipulation; and **Matplotlib Pyplot** and **Seaborn** for some data visualization.

## Data Source

This project was inspired by a [Kaggle project](https://www.kaggle.com/datasets/nenriki/kz-insurance-company/data) on the same topic. The business questions used in the Kaggle project have also been recycled and adapted for this project. 

The original data set `Dataset_pandas_assign.xlsx` *(attached in the aforementioned Kaggle project)* is in Russian, so an external [online document translator](https://www.onlinedoctranslator.com/en/) was used to translate the data set to English. The translated data set `Dataset_pandas_assign_translated.xlsx`, which is enclosed in the folder storing this Jupyter Notebook, will be used for this analysis.

## Post-Project Insights

- The average age of female drivers is smaller than that of male drivers. A higher percentage of female drivers are involved in road accidents. Also, the average driving experience and Bonus-Malus Class for female drivers tends to be lower than male drivers.
- The year with highest number of vehicles manufactured is 2007.
- Toyota appears to be a rather popular vehicle brand.
- This data set contains more dark-colored vehicles than light-colored ones.
- Almaty has the highest frequency of road accidents.
- There was a driver involved in more than 1 accident in a year.
- High Bonus-Malus Classes seem to be associated with higher frequencies of road accidents than low Bonus-Malus Classes. 
