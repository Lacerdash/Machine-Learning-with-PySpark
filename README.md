# Alura Data Science Challenge II
<div align="center">
  <a href="https://www.linkedin.com/in/fernando-lacerda-/" target="_blank">
    <img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="https://github.com/Lacerdash">
    <img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white"></a>
</div>

In this Repository is my project developed during the participation in the second Data Science Challenge promoted by Alura. Alura is a Brazilian online platform for technology courses.

The purpose of these Challenges is to deepen students' knowledge in the area of ​​Data Science, through practical challenges. More specific in this case we will use PySpark to make all the ETL process, build a regression model to price real estate and create a real estate recommender.

| :placard: Vitrine.Dev |     |
| -------------  | --- |
| :sparkles: Project Name        | **Alura Data Science Challenge II**
| :label: Tecnologias | Python
| :rocket: Libraries         | PySpark, zipfile, Seaborn and pyplot
| :fire: Challenge     | https://www.alura.com.br/challenges/data-science-2/

---

## **About the Challenge**

**Objectivies:** Build a regression model to price real estate and create a real estate recommender.

**Data:** The data is avaible [here](https://github.com/Lacerdash/Alura-Data-Science-Challenge-II/blob/main/data/semana-1.zip) and the data dictionary [here](https://github.com/Lacerdash/Alura-Data-Science-Challenge-II/blob/main/data/README.md)

**Structure:** The challenge is divided in 3 parts: ETL (Extract, Transform and load), Creating Regression Models and 

---

## **1 - Extract, Transform and Load**

The first part of the project is dedicated to the ETL process of the data. Extracting the data in json format into python, for subsequent transformation/cleaning of the data, followed by loading the data into in csv and parquet file format. All of these activies were performed using the **PySpark** library.

At this stage, the translation of the data into English was also carried out.

[CSV file](https://github.com/Lacerdash/Alura-Data-Science-Challenge-II/blob/main/data/csv/part-00000-4340dfbc-acf6-4ad3-8cc2-6ec617ebd94a-c000.csv).
[Parquet file](https://github.com/Lacerdash/Alura-Data-Science-Challenge-II/blob/main/data/parquet/part-00000-8bc019cf-aa0b-4e9e-98c7-a3ac5f08fe01-c000.snappy.parquet).

All activities performed are documented in this [notebook](https://github.com/Lacerdash/Alura-Data-Science-Challenge-II/blob/main/1%20-%20Extract%2C%20Transform%20and%20Load.ipynb).

---

## **2 - Regression Models**

The second part of the project is dedicated to: 

- Process the data from the first notebook "1 - Extract, Transform and Load" to use Regression Models.
    - Treating null and NaN data;
    - Treating missing data in the zone columns
    - Transforming categorical columns into binary columns (0, 1)
    - Removing useless columns
    - Saving the DataFrame in a parquet file
- Creating Models
    - Vectorizing the data (Vector Assembler)
    - Creating 4 models (Linear Regression, Decision Tree Regressor, Random Forest Regressor and Gradient-boosted tree Regressor)
- Optimizing the best model
    - Cross Validation and Hyperparameters Testing

[Parquet file generated]().

All activities performed are documented in this [notebook](https://github.com/Lacerdash/Alura-Data-Science-Challenge-II/blob/main/2%20-%20Regression%20Models.ipynb).
---

## Semana 3

Working ...


![insignhtPlaces](https://user-images.githubusercontent.com/104234513/203103126-3dbe6892-5acb-46d0-bef5-e3c10b7c5a5a.png#vitrinedev)