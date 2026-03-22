# 🚀 TextMorph – Secure AI Workspace

## 📌 Overview

**TextMorph** is a secure AI-powered workspace built using **Streamlit**.
It combines authentication, password security, OTP-based recovery, and text analysis tools into a single interactive platform.

---

## ✨ Features

### 🔐 Authentication System

* User Signup & Login
* JWT-based session management
* Password hashing using bcrypt
* Account lock after multiple failed attempts

### 🔑 Password Recovery

* OTP-based reset via Email
* Security Question-based reset
* OTP expiry & validation
* Password reuse prevention

### 👨‍💼 Admin Dashboard

* View all users
* Delete users (except admin)
* Auto-created admin account

### 💬 AI Chat (Mock)

* Interactive chat interface
* Session-based conversation history

### 📖 Readability Analyzer

* Analyze text readability using:

  * Flesch Reading Ease
  * Flesch-Kincaid Grade
  * SMOG Index
  * Gunning Fog Index
  * Coleman-Liau Index
* Upload **TXT or PDF files**
* Visual dashboards with Plotly gauges

---

## 🛠️ Tech Stack

* **Frontend:** Streamlit
* **Backend:** Python
* **Database:** SQLite
* **Authentication:** JWT
* **Security:** bcrypt, OTP (HMAC-based)
* **Visualization:** Plotly
* **File Handling:** PyPDF2

---

## 📂 Project Structure

```
TextMorph/
│
├── app.py        # Main Streamlit application
├── db.py         # Database & authentication logic
├── users.db      # SQLite database (auto-created)
├── .streamlit/
│   └── config.toml
└── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/TextMorph.git
cd TextMorph
```

### 2️⃣ Install Dependencies

```bash
pip install streamlit pyjwt bcrypt python-dotenv pyngrok nltk \
streamlit-option-menu plotly textstat PyPDF2
```

---

## 🔑 Environment Variables

Create a `.env` file:

```
EMAIL_PASSWORD=your_gmail_app_password
JWT_SECRET=your_secret_key
```

---

## ▶️ Run the App

```bash
streamlit run app.py
```

---

## 🌐 Run with Ngrok (Optional)

```bash
pip install pyngrok
```

```python
from pyngrok import ngrok
public_url = ngrok.connect(8501)
print(public_url)
```

---

## 👤 Default Admin Account

```
Email: admin@llm.com
Password: Admin@123Secure!
```

---

## 🔒 Security Features

* Password hashing (bcrypt)
* Login rate limiting
* OTP expiration
* JWT authentication
* Password history tracking

---

## 📊 Readability Metrics Explained

| Metric              | Description                 |
| ------------------- | --------------------------- |
| Flesch Reading Ease | Higher = easier to read     |
| FK Grade            | U.S. school grade level     |
| SMOG                | Focuses on complex words    |
| Gunning Fog         | Sentence + word complexity  |
| Coleman-Liau        | Character-based readability |

---

## 🎯 Future Enhancements

* Real AI integration (OpenAI / LLMs)
* User activity analytics
* Role-based access control
* Cloud database support
* File export (PDF reports)

---

## 🤝 Contribution

Feel free to fork this repo and contribute!
Pull requests are welcome.

---

## 📜 License

This project is open-source and available under the MIT License.

---

## 💡 Author

Developed by **Sameena Shaik**

---

