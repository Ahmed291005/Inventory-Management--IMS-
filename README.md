# 🏷️ Inventory Management System (IMS)

![Python](https://img.shields.io/badge/Python-3776AB?logo=python\&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?logo=django\&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?logo=mysql\&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?logo=bootstrap\&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

---

A comprehensive **Inventory Management System** built to handle daily operations in a **studio environment**.
It manages **sales, purchases, customers, suppliers, and users**, ensuring accurate record-keeping and streamlined workflows.

The main goal of this system is to **save time** ⏱️ and **reduce errors** ❌ when recording purchases, sales, and services — making it easy to maintain an organized and efficient process.

---

## ✨ Features

- ✅ Manage **sales & purchase details**
- ✅ Track **customer & supplier records**
- ✅ User management & role-based access
- ✅ Prevents manual errors in inventory tracking
- ✅ Improves time efficiency & data accuracy
- ✅ User-friendly **dashboard & reports**

---

## 🗂️ How to Run Locally

1️⃣ **Clone the repository**

```bash
git clone https://github.com/Ahmed291005/Inventory-Management--IMS-.git
cd Inventory-Management-System
```

2️⃣ **Create & activate virtual environment**

```bash
# Windows
python -m venv env
env\Scripts\activate

# macOS/Linux
python3 -m venv env
source env/bin/activate
```

3️⃣ **Install dependencies**

```bash
pip install -r requirements.txt
```

4️⃣ **Configure database (MySQL)**
Update your `settings.py` with correct database credentials:

```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'ims_db',
        'USER': 'root',
        'PASSWORD': 'yourpassword',
        'HOST': '127.0.0.1',
        'PORT': '3306',
    }
}
```

5️⃣ **Apply migrations & create superuser**

```bash
python manage.py migrate
python manage.py createsuperuser
```

6️⃣ **Run the development server**

```bash
python manage.py runserver
```

Visit: `http://127.0.0.1:8000/`

---

## ⚙️ Tech Stack

* **Backend:** Python, Django
* **Database:** MySQL
* **Frontend:** HTML, CSS, Bootstrap
* **Authentication:** Django Auth System
* **Deployment:** Localhost / Custom server

---

## 📌 Future Improvements

- ✅ Add **JWT authentication** for API access
- ✅ Integrate **Redis caching** for faster performance
- ✅ Generate **exportable reports (CSV/PDF)**
- ✅ Multi-language support
- ✅ Docker setup for easy deployment

---

## 📝 License

This project is licensed under the **MIT License** — see the [LICENSE](./LICENSE) file for details.

---

## 🤝 Connect with Me

> Made with ❤️ by **Muhammad Ahmed**

🔗 [LinkedIn](https://www.linkedin.com/in/muhammad-ahmed-5b7850340/)
📬 Feel free to connect, fork, star ⭐, and build upon this project!

---