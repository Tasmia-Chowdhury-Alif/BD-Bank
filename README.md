# BD-Bank 🏦💸
[![Django](https://img.shields.io/badge/Django-5.2-092E20?style=for-the-badge&logo=django)](https://www.djangoproject.com/) 
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Render-336791?style=for-the-badge&logo=postgresql)](https://www.postgresql.org/) 
[![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-v3-38B2AC?style=for-the-badge&logo=tailwind-css)](https://tailwindcss.com/) 

## 📋 Overview
BD-Bank is a full-stack Django application designed for efficient banking management with a secure interface. Built with Django and styled using Tailwind CSS, it offers a seamless user experience for managing accounts, transactions, and loans. Deployed on **Render**, it showcases robust backend logic and modern frontend design.

## 🚀 Live Demo
🔗 **BD-Bank:** [https://bd-bank-gqzo.onrender.com](https://bd-bank-gqzo.onrender.com)

## 🛠 Technologies Used
- **Backend**: Django 5.2.1 (Routing, authentication, and transaction logic)
- **Frontend**: HTML5, Tailwind CSS (Modern UI)
- **Database**: PostgreSQL (Hosted on Render for reliable data management)
- **Extras**: SMTP Email Integration (Gmail), Django Humanize (Formatting)
- **Deployment**: Hosted on Render.com

## 🌟 Key Features
- **🔒 User Management**: Register, log in, update profiles, and change passwords securely. 
- **💳 Account Operations**: Create savings or current accounts with unique account numbers. 
- **💸 Transactions**: Perform deposits, withdrawals, money transfers, and loan requests with real-time balance updates. 
- **📋 Loan System**: Request and pay loans, with admin approval via Django admin panel. 
- **📧 Email Notifications**: Receive HTML-based email alerts for transactions and password changes. 
- **📊 Transaction Reports**: Filter and view transaction history by date range. 
- **🚫 Bank Status**: Restricts withdrawals during bankruptcy for secure operations. 

## ⚙️ Installation & Setup
1. **Clone the Repository**:
```bash
git clone https://github.com/Tasmia-Chowdhury-Alif/BD-Bank.git
cd bd-bank
```
2. **Create & Activate Virtual Environment**:
```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate  # Windows
```
3. **Install Dependencies**:
```bash
pip install -r requirements.txt
```
4. **Configure Environment Variables (.env)**:
```env
SECRET_KEY=your_django_secret_key
DJANGO_DEBUG=True
EXTERNAL_DB_URL=your_postgresql_db_url
EMAIL_HOST_USER=your_email@gmail.com
EMAIL_HOST_PASSWORD=your_email_app_password
```
5. **Run Migrations**:
```bash
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
```
6. **Run the Server**:
```bash
python manage.py runserver
```
🎉 **Success!** Visit [http://127.0.0.1:8000/](http://127.0.0.1:8000/) to explore.

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author
**Tasmia Chowdhury Alif**
- GitHub: [@Tasmia-Chowdhury-Alif](https://github.com/Tasmia-Chowdhury-Alif)
- Email: tasmiachowdhuryalif222@gmail.com  

---
<div align="center">

### ⭐ If this project helped you, please give it a star!

**Built with ❤️ by Tasmia Chowdhury Alif**

[Report Bug](https://github.com/Tasmia-Chowdhury-Alif/DocEra_Health_Care/issues) • [Request Feature](https://github.com/Tasmia-Chowdhury-Alif/DocEra_Health_Care/issues)

</div>
