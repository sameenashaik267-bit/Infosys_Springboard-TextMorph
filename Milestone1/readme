📌 ***TEXTMORPH – MILESTONE 1***
🚀 **PROJECT OVERVIEW**

TextMorph is a secure AI-powered web application built using Streamlit.
This milestone focuses on implementing a complete user authentication system with a modern UI and secure backend.
✨ ***FEATURES IMPLEMENTED***
🔐 **AUTHENTICATION SYSTEM**

User signup with validation

Secure login system

JWT-based session management

Logout functionality

🔑** PASSWORD SECURITY**

Password hashing using bcrypt

Strong password validation (minimum 8 characters, alphanumeric)

🔄 **FORGOT PASSWORD**

Email verification

Security question validation

Password reset functionality

🗄️ **DATABASE**

SQLite database (users.db)

Stores:

Username

Email (Primary Key)

Hashed Password

Security Question & Answer

🎨** USER INTERFACE**

Gradient animated background

Glassmorphism login/signup cards

Custom error & success messages

Responsive layout using Streamlit

💬** DASHBOARD**

Sidebar navigation:

Chat Now

New Chat

Logout

Chat interface (LLM placeholder response)

Session-based chat history

🌐 **DEPLOYMENT SUPPORT**

Integrated with ngrok for public access

🛠️ **TECHNOLOGIES USED**

Python

Streamlit

SQLite3

JWT (PyJWT)

bcrypt

ngrok

📂** PROJECT STRUCTURE**
TextMorph/
│
├── app.py              # Main Streamlit application
├── users.db            # SQLite database (auto-created)
└── README.md           # Project documentation
⚙️ **INSTALLATION & SETUP**
1️⃣ INSTALL DEPENDENCIES
pip install streamlit bcrypt pyjwt pyngrok
2️⃣ RUN THE APPLICATION
streamlit run app.py
3️⃣ (OPTIONAL) RUN WITH NGROK
from pyngrok import ngrok

ngrok.set_auth_token("YOUR_TOKEN")
public_url = ngrok.connect(8501)
print(public_url)
🔄 APPLICATION FLOW

User opens app → Login Page

New user → Signup

Existing user → Login

Forgot password → Reset via security question

After login → Dashboard

User can:

Start chat

Reset chat

Logout

🔒** SECURITY MEASURES**

Passwords stored in hashed format using bcrypt

JWT tokens used for session authentication

Input validation for email & password

Protection against invalid login attempts

📸 **SCREENSHOTS**
