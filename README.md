# 📚 Library Management System - نظام إدارة مكتبة

##  بالعربية:

نظام بسيط وعملي لإدارة مكتبة، تم تطويره باستخدام إطار العمل Django. يتيح هذا المشروع للمستخدمين إمكانية إضافة الكتب وتصنيفها، ومعرفة حالتها (متاحة، مباعة، مستأجرة)، مع حساب الأرباح وعدد الكتب في كل حالة.

### ✅ الميزات:

- 🔍 البحث عن الكتب حسب العنوان، المؤلف، أو التصنيف  
- 📂 إدارة التصنيفات  
- 📘 عرض حالة الكتب (متاحة، مباعة، مستأجرة)  
- 📈 إحصائيات الأرباح وعدد الكتب  
- ➕ إضافة وتعديل وحذف الكتب والتصنيفات  
- 📊 رسوم بيانية تفاعلية باستخدام Chart.js  
- 🎨 تصميم احترافي باستخدام AdminLTE

---

## 🇬🇧 In English:

A simple and practical **Library Management System** built with Django. This project allows users to add and categorize books, manage their availability (Available, Sold, Rented), and track profits and stats.

### ✅ Features:

- 🔍 Search books by title, author, or category  
- 📂 Manage categories  
- 📘 Book statuses: Available, Sold, Rented  
- 📈 Statistics and profit calculation  
- ➕ Add / Edit / Delete books and categories  
- 📊 Charts powered by Chart.js  
- 🎨 Professional UI using AdminLTE

---

## 🚀 كيفية تشغيل المشروع - How to Run the Project

### المتطلبات - Requirements:

- Python 3.8 أو أعلى  
- Django 4.2 أو أعلى  
- مكتبة `pillow` للتعامل مع الصور  
- SQLite (قاعدة البيانات الافتراضية في Django)

---

### ⚙️ خطوات التشغيل - Steps to Run Locally:

1. **استنساخ المشروع / Clone the project**
   ```bash
   git clone https://github.com/theINVISIBEL/library-management-system-django.git
   ```

2. **إنشاء بيئة افتراضية / Create a virtual environment**
   ```bash
   python -m venv env
   source env/bin/activate      # على Linux / macOS
   env\Scripts\activate         # على Windows
   ```

3. **تثبيت الحزم المطلوبة / Install the dependencies**
   ```bash
   pip install -r requirements.txt
   ```

4. **تشغيل الهجرات / Run the migrations**
   ```bash
   python manage.py migrate
   ```

5. **تشغيل السيرفر المحلي / Start the development server**
   ```bash
   python manage.py runserver
   ```

6. افتح المتصفح على:
   ```
   http://127.0.0.1:8000/
   ```

---

## 👨‍💻 المطور / Developer

- **الاسم:** Abderrahmane Bahime  
- **الاسم البرمجي:** theINVISIBEL  
- **البريد:** abderrahmane3002brahime@gmail.com  
- **GitHub:** [github.com/theINVISIBEL](https://github.com/theINVISIBEL)  
- **الوظيفة:** Cybersecurity /pentertion tester 🛡️ | Python Developer 🐍/backend framework django  | OSCP Certified  

---

## 📝 الترخيص - License

هذا المشروع مرخص تحت رخصة [MIT License](LICENSE).  
You are free to use, modify, and distribute this code under the terms of the MIT license.
