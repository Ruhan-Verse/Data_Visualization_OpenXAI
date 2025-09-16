# Titanic Dataset Analysis

## 📂 Dataset
Link: https://www.kaggle.com/datasets/yasserh/titanic-dataset
This dataset is the Kaggle “Titanic” dataset. It contains passenger information (age, gender, class, fare, embarked port, etc.) and whether they survived or not.  

## 📊 Visualizations
Here are some of the plots produced:

- Survival by Sex  

![alt text](image.png)
- Survival by Pclass  

![alt text](image.png)
- Age distribution: Survived vs Not  

![alt text](image-1.png)
- Fare paid: Survived vs Not  

![alt text](image-2.png)
- Violin plot: Age by Pclass & Survival  

![alt text](image-3.png)
- FacetGrid: Age distribution by Sex & Pclass  

![alt text](image-4.png)

## 🔎 Insights
- Female passengers had much higher survival rates.  
- Passenger class strongly influenced survival: 1st class >> 2nd class >> 3rd class.  
- Younger passengers tend to survive more.  
- Higher fare correlates (though not perfectly) with higher survival (but may be confounded by class).  
- Some combinations (female + 1st class) had highest survival probabilities.

## 🧰 Project Files
- `titanic_analysis.ipynb` (notebook with code) or `titanic_analysis.py`  
- `titanic.csv` (dataset)  
- `README.md`  
- `screenshots/` (folder with images of graphs)  
