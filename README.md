# 🥗 Local Food Wastage Management System


## 📌 Project Overview
Food wastage is a significant global issue — many households and restaurants discard surplus food while millions face hunger.  

The **Local Food Wastage Management System** connects **surplus food providers** (restaurants, households) with **receivers** (NGOs, individuals in need) to minimize waste and improve food distribution.

This project uses **SQLite** for database management, **SQL queries** for analysis, and a **Streamlit web application** for easy interaction.

---

## 🎯 Features
- **Provider & Receiver Management** – Add and view details.
- **Food Listings** – Browse, filter, and view available food items.
- **Claims Management** – Record and track food claims.
- **Analytics Dashboard** – View insights such as:
  - Providers per city
  - Most common food types
  - Claim success rate by city
  - Items nearing expiry
- **Interactive Filters** – Filter data by city, provider, food type, and meal type.

---
## 🗂️ Project Structure

📁 local-food-wastage-management
│── app.py # Streamlit application
│── food_waste.db # SQLite database file
│── providers_data.csv # Providers dataset
│── receivers_data.csv # Receivers dataset
│── food_listings_data.csv # Food listings dataset
│── claims_data.csv # Claims dataset
│── schema.sql # Database schema
│── queries.sql # Analytical SQL queries
│── requirements.txt # Python dependencies

---


---

## 🚀 Live Demo
Access the live web application here:  
**🔗 [Streamlit App](https://sid-local-food-wastage-management.streamlit.app/)**

---

## 🛠️ Tech Stack
- **Python 3**
- **SQLite**
- **Pandas**
- **Streamlit**
- **SQL**

---

## 📊 SQL Queries
The project includes **15 analytical queries** to gain insights, such as:
1. Providers per city
2. Receivers per city
3. Top provider type by quantity
4. Receivers who claimed the most
5. Most common food types
6. Claim success rate by city
...and more.

---

## 💻 Running Locally
1. **Clone the repository**  
   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
   cd <your-repo>
  ---

2. Install dependencies
```bash
pip install -r requirements.txt
```
---
3. Run the app
```bash
streamlit run app.py

```
---
4. Open in browser
Streamlit will provide a local URL, usually http://localhost:8501.

📧 Contact

For questions or suggestions:

Name: Siddhartha Ram Konasani
Mail: siddharthakonasani.77@gmail.com
LinkedIn: https://www.linkedin.com/in/siddhartha-ram-konasani/
