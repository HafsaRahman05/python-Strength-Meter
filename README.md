# 🔐 Password Strength Meter

A simple and interactive **Password Strength Checker & Generator** built with **Python and Streamlit**.  
It evaluates password security, gives improvement suggestions, and generates strong passwords instantly.

🌐 Live Demo: https://python-strength-meter-8tajj9h5ehzea9eh5jnnht.streamlit.app/  
📂 GitHub Repo: https://github.com/HafsaRahman05/python-Strength-Meter  

---

## 🎯 Objective

To build a smart **Password Strength Meter** that:

- Analyzes password strength based on security rules  
- Assigns a strength score (Weak / Moderate / Strong)  
- Provides improvement suggestions  
- Generates secure random passwords  

---

## ✨ Features

- 🔐 Password strength checker  
- ⚠️ Real-time feedback & suggestions  
- ❌ Blocks common weak passwords (e.g. `123456`, `password123`)  
- 🔁 Strong password generator  
- 👁️ Hidden password input for security  
- 🧪 Score-based evaluation system (0–4)  
- 🌐 Simple web UI using Streamlit  

---

## 🧠 How It Works

The password is evaluated based on:

- Length (minimum 8 characters)
- Uppercase & lowercase letters
- Numbers (0–9)
- Special characters (!@#$%^&*)
- Blacklist check (common weak passwords)

Each condition increases the **strength score**.

---

## 💡 Password Strength Levels

- **0–1 → Weak ❌**
- **2–3 → Moderate ⚠️**
- **4 → Strong ✅**

---

## 🛠️ Technologies Used

- Python 🐍  
- Streamlit 🌐  
- Regex (re module)  
- Random module  

---

## 📁 Project Structure
```bash
python-Strength-Meter/
│
├── app.py # Main Streamlit application
├── requirements.txt # Dependencies
└── README.md # Project documentation
```


---

## ▶️ How to Run Locally

### 1. Clone repository
```bash
git clone https://github.com/HafsaRahman05/python-Strength-Meter.git
cd python-Strength-Meter
```

2. Install dependencies
```bash
pip install streamlit
```

3. Run the app
   ```bash
streamlit run app.py
```

## 🚀 Deployment

This project is deployed using **Streamlit Cloud**:

- Push code to GitHub  
- Connect repository to Streamlit Cloud  
- Deploy automatically  

---

## 👩‍💻 Author

**Hafsa Rahman**  
Software Engineering Student  
Interested in Data Science & Web Development  

---

## ⭐ Future Improvements

- Add password breach check (HaveIBeenPwned API)  
- Add password history checker  
- Add password encryption strength meter  
- Improve UI with animations  
- Add dark mode theme  
