# 📰 Full-Stack Fake News Detection System | Python Django + MySQL | Machine Learning Project

Fake News Detection System developed using **Python, Django 5, MySQL, and Machine Learning (Logistic Regression + NLP)**.  
This project detects whether news is **Real** or **Fake** with a complete **web application**.  
It is ideal for **Final Year Computer Science Students (B.Tech, MCA, M.Tech, BCA)** who want hands-on experience with **AI, Machine Learning, and Web Development**.

---

## 📺 Project Demo
▶️ **YouTube Video**: [Watch Here](https://www.youtube.com/watch?v=45eFdG_KFLg)  
![fake_news_YT](https://user-images.githubusercontent.com/28294942/233419123-cecece7b-4775-4481-abb0-f4ebae8a3d5c.png)

---

## 📖 Abstract
With the rise of social media, news consumption has shifted from traditional print to digital platforms.  
While this provides convenience and accessibility, it has also led to the rapid spread of **Fake News**.  
This project addresses the challenge of misinformation by applying **Machine Learning and Natural Language Processing (NLP)** to classify news as *Real* or *Fake*.  

The system uses:
- **Text Preprocessing** (stopword removal, lemmatization, punctuation handling)  
- **TF-IDF Vectorization**  
- **Logistic Regression Model** for classification  

It provides a complete **Django-based Web Application** with **MySQL integration**, making it both a powerful ML model and a practical full-stack solution.  

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, Bootstrap  
- **Backend**: Python Django 5  
- **Database**: MySQL  
- **Machine Learning**: Scikit-learn, TF-IDF, Logistic Regression, NLP (NLTK)  
- **Development**: Jupyter Notebook + Django Web Application  

---

## 🚀 Features

- 🔹 **Fake News Detection**: Classify news as Real or Fake  
- 🔹 **Admin Login System**: Secure login with MySQL database validation  
- 🔹 **Detection History**: Track all past predictions  
- 🔹 **Dataset Viewer**: View top Fake and Real news samples  
- 🔹 **System Information Page**: Shows libraries and modules used  
- 🔹 **User-Friendly UI**: Built with Django templates, Bootstrap, and responsive design  

---

## 📂 Project Modules

- **Home Page** → Introduction to Fake News Detection System  
- **About Page** → Project overview and description  
- **Admin Login Page** → Authentication using MySQL  
- **Contact Us Page** → Project inquiry details  
- **System Information Page** → Libraries and modules used  
- **Fake News Detection Module** → Input news text and check authenticity  
- **Detection History** → List of past detection records  
- **Dataset Information** → Overview of dataset used (Fake & True news)  

---

## 📊 Dataset Information
The project uses the **Kaggle Fake and True News Dataset**:
- **Fake.csv** → Fake news articles  
- **True.csv** → Real news articles  

Each dataset includes fields like **title, text, subject, and date**.  
For demo purposes, the project shows **top 100 Fake & Real news records** in the dataset viewer.  

---
## 📞 Contact / Get in Touch  

If you are interested in this **Fake News Detection System Project** or need guidance for your **Final Year Project**, you can reach out to us easily.  
We provide **Source Code, Project Report, Synopsis, PPT, Documentation, and Video Demonstration** for students.  

📩 **Email:** [codeassists@gmail.com](mailto:codeassists@gmail.com)  
📱 **Phone / WhatsApp:** [+91-8470010001](https://wa.me/918470010001?text=Hello%20Team%2C%20I%20got%20your%20contact%20from%20GitHub%20and%20want%20to%20know%20about%20a%20project) 👉 [Chat Now](https://wa.me/918470010001?text=Hello%20Team%2C%20I%20got%20your%20contact%20from%20GitHub%20and%20want%20to%20know%20about%20a%20project)    
🌐 **Websites:**   [CodeAssists](http://codeassists.com/), [FreeProjectz](https://www.freeprojectz.com/)  
📌 **Project Link:** [Fake News Detection System – Source Code](https://www.freeprojectz.com/machine-learning-projects-python-projects-major-project/fake-news-detection-system-project-source)  

--
## ⚙️ Installation & Setup

### 🔹 Prerequisites
- Python 3.9+  
- Django 5+  
- MySQL Server  

### 🔹 Steps
```bash
# Clone repo
git clone https://github.com/your-username/fake-news-detection.git
cd fake-news-detection

# Create virtual environment
python -m venv venv
source venv/bin/activate   # (Linux/Mac)
venv\Scripts\activate      # (Windows)

# Install dependencies
pip install -r requirements.txt

# Setup MySQL Database
# Update settings.py with your DB credentials

# Apply migrations
python manage.py migrate

# Run server
python manage.py runserver
