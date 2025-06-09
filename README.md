<h1 align="center">Bestseller Book Cover & Sales Analysis</h1>

<p align="center">
  <img src="https://github.com/user-attachments/assets/90910d60-6b16-4c44-b99b-5bc9b9a96387" alt="image" width="300"/>
</p>

<p align="center">
  Data-Driven Insights on Visual Design, Reviews, and Market Trends in Book Sales.
</p>

---

## 📌 Project Overview

With the rapid expansion of the book market and increasing genre diversity, it’s crucial to understand the factors behind **bestseller success**.  
This project uses data science to analyze **book cover visuals**, **ratings**, **genres**, **authors**, and **pricing trends** to uncover what drives a book’s popularity.

---

## 🎯 Objectives

We aimed to answer the following key questions:

-  Do bestseller books have distinct **visual cover patterns**?
-  Are **certain authors** more likely to have bestsellers?
-  What **genres** dominate bestseller lists?
-  How do **ratings and reviews** differ among bestsellers?
-  What is the **price range** for high-performing books?

---

##  Data Collection

| Source        | Description                              |
|---------------|------------------------------------------|
| **Amazon.sa** | Top 100–200 bestseller books             |
| **Jarir.com** | Top-selling books from Jarir bookstore   |

**Tools Used:**

- 🔎 Chrome Extensions: *Web Scraper*, *Instant Data Scraper*
- 🐍 Python Libraries: `requests`, `BeautifulSoup`, `Selenium`, `pandas`

**Collected Features:**
- Title, Author, Genre, Rating, Review Count, Price, Cover Image

---

## 🖼️ Cover Image Clustering

We extracted visual features from book covers to classify design trends.

** Feature Extraction:**
- Contrast  
- Edge Complexity  
- Color Saturation  
- Color Variance  

**📊 Algorithms:**
- K-Means Clustering (k=2) → **Silhouette Score: 0.25**  
- Spectral Clustering (k=2) → **Silhouette Score: 0.22**

**✅ Chosen Method:** K-Means for its simplicity and interpretability.

### 🔍 Key Cover Style Clusters:
| Cluster Type         | Description                                     |
|----------------------|-------------------------------------------------|
| Bold & Vibrant       | High contrast, vivid colors (~50%)             |
| Subtle & Muted       | Low saturation, minimalist look (~50%)         |

> 🎯 **Insight:** Covers with vivid colors and bold contrast are more attractive and associated with success.

---

## 📈 Statistical Insights

### ⭐ Bestseller Patterns

| Metric                    | Observation                                  |
|---------------------------|----------------------------------------------|
| 🔁 Reviews                | Bestsellers typically have **more reviews** |
| ⭐ Rating Distribution     | Top books score **above 4.2** consistently  |
| 💰 Price Range            | Most bestsellers fall between **30–80 SAR** |
| 📚 Genre Trends           | Self-help, children’s books, and fiction dominate |
| 🖊️ Author Success         | Recurring bestselling authors were identified |

---

## 🧠 Conclusion

Bestseller success isn’t defined by a **single factor** — it's a **combination** of:

- Author popularity
- Eye-catching, bold cover design
- High rating and review volume
- Competitive pricing
- Genre relevance

🎯 **Takeaway:** Authors and publishers can use these insights to **optimize their marketing, design, and pricing strategies** for greater success.

---

## 👥 Team & Supervision

- Remas Al-Subaie  
- Mona Alnajjar  
- Jana Alruzuq  
- Rima Alsonbul  
- Razan Aldosari  

**Supervised by:** Dr. Mashael Aldayel

