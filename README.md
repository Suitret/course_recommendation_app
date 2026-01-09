# Udemy Course Recommendation App

An interactive **course recommendation system** built with **Streamlit** that suggests Udemy courses similar to the one you search for, using **content-based filtering** (cosine similarity on course titles).

![App Screenshot](https://i.imgur.com/EXAMPLE.png)  
*(Replace with your own screenshot later – see instructions below)*

## ✨ Live Demo

Try the app right now:  
👉 **[https://courserecommendationapp.streamlit.app/](https://courserecommendationapp.streamlit.app/)**

## 📸 Screenshots

### Home Page
![Home Page](https://i.imgur.com/EXAMPLE-home.png)

### Recommendation Results
![Recommendation Results](https://i.imgur.com/EXAMPLE-recommend.png)

*(Tip: Take clean screenshots of your running app and upload them to GitHub or Imgur, then replace the placeholder image links above.)*

## ✨ Features

- Search for any Udemy course by title  
- Get **top similar courses** based on title similarity  
- Adjustable number of recommendations (4–30)  
- Shows **similarity score**, **price**, **number of students**, and direct **course link**  
- Clean, mobile-friendly card-style results  
- Fallback search when exact match isn't found  
- Fast caching with `@st.cache`

## 🛠️ Tech Stack

- **Frontend / Framework**: [Streamlit](https://streamlit.io/)  
- **Data Processing**: [pandas](https://pandas.pydata.org/)  
- **Text Vectorization & Similarity**: [scikit-learn](https://scikit-learn.org/) (`CountVectorizer` + `cosine_similarity`)  
- **Deployment**: [Streamlit Community Cloud](https://streamlit.io/cloud)

## 📦 Requirements

```text
streamlit
pandas
scikit-learn
```
