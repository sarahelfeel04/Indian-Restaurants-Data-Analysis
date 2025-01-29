# 🍽️ Indian Restaurant Data Analysis - EDA & Insights  

This **Jupyter Notebook project** explores **51,717 restaurants in India** using the **Zomato dataset**. The analysis focuses on **customer ratings, restaurant types, pricing, and geographic trends** to uncover key insights about the restaurant industry.  

## Summary
- Conducted exploratory data analysis (EDA) on 51,717 Indian restaurants using the Zomato dataset.
- Investigated restaurant success factors by analyzing ratings, votes, online ordering, table booking, and cuisine trends.
- Applied data cleaning and preprocessing, handling missing values, normalizing costs, and standardizing restaurant locations.
- Used data visualization (heatmaps, bar charts, radar charts) to uncover cost-rating relationships, restaurant types, and geographical patterns.
- Identified key insights, such as how high-cost restaurants tend to have higher ratings, and how drinks & nightlife spots consistently outperform others in customer feedback.

---

## Key Insights  
### 1. What factors contribute to high restaurant ratings?  
- Restaurants with **higher costs** tend to receive **higher ratings**.  
- **Drinks & nightlife spots** consistently score **higher than casual dining**.  
- **Table booking availability correlates with higher ratings**, but online ordering does not.  

### 2. How does location affect restaurant success?  
- **Bengaluru** has the highest number of restaurants, but some **smaller cities** have **higher ratings**.  
- Restaurants in **wealthier areas** tend to have **higher average costs and ratings**.  

### 3. How do restaurant types differ in pricing and ratings?  
- **Delivery restaurants** are the most common but have the lowest ratings.  
- **Fine dining and bars** have **fewer locations but higher ratings**.  
- **Buffet-style restaurants** are priced mid-range but have mixed ratings.

---

## Technologies Used  
- **Python** – Data analysis & preprocessing  
- **Pandas** – Data manipulation & cleaning  
- **Matplotlib & Seaborn** – Data visualization  
- **Geopandas & Folium** – Geographic analysis
  
---

## Sample Visualizations  

![Restaurant Costs vs. Ratings](https://github.com/user-attachments/assets/a3d96afe-743c-4c1d-803f-58ed738f3b87)

![Online Ordering in Bengaluru](https://github.com/user-attachments/assets/87fbeb98-bd96-4024-ae7d-d2c2134d6e7d)

![Top 5 rated cities vs restauarnt types](https://github.com/user-attachments/assets/d4e1b479-4dc7-4aaa-90f5-554e2eb6a1c3)

![Restaurant Ratings in Bengaluru](https://github.com/user-attachments/assets/c5aae360-aabb-4c7c-9e49-2421cd638db2)

---
## View the EDA

Check out this [link](https://drive.google.com/file/d/1Hr9OueIxN-GVoW6wQETwPDNK7jQzE05h/view?usp=sharing) to view the notebook with screenshots of the maps' output. 

---
## How to Run the Notebook  

1. Clone the repository:  
   ```bash
   git clone https://github.com/sarahelfeel04/Zomato-Restaurant-Analysis.git
   ```  
2. Install dependencies:  
   ```bash
   pip install pandas matplotlib seaborn geopandas folium  
   ```
3. Change file path:  
   change the file path for the dataset to match your intended path
   
5. Run the **Jupyter Notebook** to explore the analysis:  
   ```bash
   jupyter notebook Zomato_Analysis.ipynb  
   ```

or download the notebook and run on google collab. Link to the datasets are [here](https://drive.google.com/drive/folders/11qWtqnDOv8gC7Nqgh1GJZ8NmvVLAj_zf?usp=sharing)
