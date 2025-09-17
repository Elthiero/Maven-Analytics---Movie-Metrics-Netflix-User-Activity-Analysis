# Movie Metrics – Netflix User Activity Analysis

This project analyzes **Netflix user activity** using the [Maven Analytics dataset](https://maven-datasets.s3.us-east-1.amazonaws.com/Data+Drills/user_activity.zip).  
The goal is to **engineer meaningful insights** about user behavior, including:

- Date and name of the **first movie** a user finished
- Date and name of the **last movie** a user finished
- Total number of movies **started**
- Total number of movies **finished**

---

## 📂 Project Structure

- `main.ipynb` — Jupyter Notebook containing the full analysis and feature engineering
- `activity.csv` — User activity dataset (movies watched, dates, completion status)
- `users.csv` — User metadata (account info, creation date)

---

## ⚙️ Installation & Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/movie-metrics.git
   cd movie-metrics
