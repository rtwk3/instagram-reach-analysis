# 📱 Instagram Reach Analysis (Kaggle Fork)

> An extended version of the [original Kaggle notebook](https://www.kaggle.com/code/muliasujiastuti/instagram-reach-analysis)  
> 🔍 Exploring what drives post reach and impressions on Instagram through ML-based modeling and feature analysis.

---

## 📌 Description

This notebook analyzes Instagram insight metrics such as likes, comments, shares, profile visits, and more, with the goal of:

- Understanding factors that influence **impressions**
- Measuring **engagement performance**
- Applying **regression models** to predict post reach
- Visualizing **correlations and conversion rates**

---

## 📊 Dataset Overview

Key features:

| Category            | Features                                                  |
|---------------------|-----------------------------------------------------------|
| Discovery Sources   | From Home, From Hashtags, From Explore, From Other        |
| Engagement Metrics  | Likes, Comments, Shares, Saves                            |
| Profile Insights    | Profile Visits, Follows                                   |
| Target Variable     | Impressions                                               |
| Textual             | Caption, Hashtags (not used in modeling)                 |

---

## 🧠 Models Evaluated

| Model                          | R² Score | MSE      |
|-------------------------------|----------|----------|
| Linear Regression             | 0.8778   | 4.7M     |
| Ridge Regression              | 0.8778   | 4.7M     |
| Polynomial Linear Regression  | 0.5548   | 17.3M    |
| **Polynomial Ridge Regression** | **0.9390** | **2.36M** ✅ Best

---

## 📈 Key Insights

- **Conversion Rate** = `(Follows / Profile Visits) × 100`
- Feature correlations visualized using heatmaps
- Regression plots comparing predicted vs actual impressions

---

## 💻 How to Use

1. Clone the repo  
2. Open the `.ipynb` file in Jupyter Notebook or Colab  
3. Run all cells sequentially to view results

---

## 🙋‍♂️ Contributor

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/rtwk3" target="_blank">
        <img src="https://github.com/rtwk3.png" width="80" height="80" style="border-radius: 50%; box-shadow: 0 0 10px rgba(0,0,0,0.15);" alt="Rtwk3"/>
      </a>
  </tr>
</table>

---

## 📚 Acknowledgment

Forked from the original [Instagram Reach Analysis by muliasujiastuti](https://www.kaggle.com/code/muliasujiastuti/instagram-reach-analysis) on Kaggle.  
Used for academic exploration and performance comparison of regression models.
