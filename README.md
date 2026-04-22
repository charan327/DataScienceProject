#  Movie Recommendation System using Collaborative Filtering

##  Overview
This project implements a **Movie Recommendation System** using the **MovieLens dataset**. The system suggests movies to users based on their past preferences and similarities with other users.

The project explores **Collaborative Filtering techniques** to deliver personalized recommendations and evaluates their performance using standard metrics.

---

##  Objectives
- Understand user behaviour from rating data
- Implement recommendation techniques
- Build a personalized movie suggestion system
- Evaluate recommendation quality

---

##  Dataset
- **Source:** MovieLens Dataset (ml-latest-small)
- Contains:
  - User ratings
  - Movie IDs and titles
  - User–item interactions

---

##  Techniques Used
- Data Preprocessing (cleaning, filtering)
- Exploratory Data Analysis (EDA)
- Collaborative Filtering:
  - User-based filtering
  - Item-based filtering
- Similarity Measures:
  - Cosine Similarity
- Recommendation generation

---

##  Evaluation Metrics
- Precision@K
- Recall@K
- nDCG (Normalized Discounted Cumulative Gain)

---

##  Features
- Recommends movies based on user similarity
- Handles sparse data effectively
- Scalable approach for large datasets
- Visualization of rating distributions and patterns

---

##  Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn

---

##  Project Structure

---

## ▶️ How to Run the Project

### Option 1: Google Colab (Recommended)
1. Open the notebook in Google Colab
2. Upload the dataset (`ml-latest-small.zip`)
3. Run all cells

### Option 2: Local Machine
1. Clone the repository:
```bash
git clone https://github.com/charan327/DataScienceProject.git
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook
👉 GitHub Notebook:
https://github.com/charan327/DataScienceProject/blob/main/movielens_recommendation_system_2.ipynb
