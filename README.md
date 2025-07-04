# PyAutoMail
# 📬 PyAutoMail – Automated Email Reporting System

![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-Working%20Perfectly-brightgreen)

PyAutoMail is a lightweight Python script that **automates the emailing of daily CSV reports** to a list of recipients. It's built for people who regularly send spreadsheets or sales reports via email and want to save time by removing the manual work.

---

## 🚀 Features

- 📎 Attaches and sends CSV files via Gmail SMTP
- 🔁 Fully automated (schedule it using cron or Task Scheduler)
- 🧠 Configurable with `mail_config.json` for credentials and recipients
- 🛡️ Uses secure Gmail App Passwords
- 📄 Logs every email sent (or failed) in `log.txt`

---

## 🧰 Technologies Used

- **Python 3.10+**
- `smtplib` and `email.message`
- `json`, `csv`, `datetime`
- Gmail SMTP (with App Passwords)
- Git & GitHub

---

## 📂 Project Structure


---

## 📂 Project Structure

...your file structure here...

---

## ⚙️ How to Use

### 1. Clone the Repo
```bash
git clone https://github.com/Anagha2dixit/PyAutoMail.git
cd PyAutoMail
2. Create mail_config.json
... your setup instructions ...

3. Add your daily report as daily_report.csv
4. Run the Script
bash
Copy
Edit
python3 main.py


