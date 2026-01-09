# Udemy Course Recommendation App

An interactive **course recommendation system** built with **Streamlit** that suggests Udemy courses similar to the one you search for, using **content-based filtering** (cosine similarity on course titles).

![App Screenshot](https://drive.google.com/file/d/1ZrxW1GljXDIDKIM-3pVTif58Yy_rY5sF/view?usp=sharing)  

## ✨ Live Demo

Try the app right now:  
👉 **[https://courserecommendationapp.streamlit.app/](https://courserecommendationapp.streamlit.app/)**

## 📸 Screenshots

### Home Page
![Home Page](https://drive.google.com/file/d/1ZrxW1GljXDIDKIM-3pVTif58Yy_rY5sF/view?usp=sharing)

### Recommendation Results
![Recommendation Results](https://drive.google.com/file/d/1DJ-ub-qRalNWzo2SNCmCxPsec4ed2KKp/view?usp=sharing)


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
