 📝 Feedback & Reviews App (Django Web Application)

[ 🇬🇧 English Version ](#english) | [ 🇦🇲 Հայերեն Տարբերակ ](#armenian)

---

<span id="english"></span>
## 🇬🇧 English

> A dynamic, full-featured web application built with Python and the Django framework. This project demonstrates advanced form processing (Django Forms & ModelForms), Class-Based Views (CBVs), session management, and media file uploads.

### 📌 About the Project

The **Feedback** project is designed to handle user submissions efficiently and securely. It showcases best practices in capturing user input, running server-side validations, persisting feedback data into the database, and managing interactive user sessions (such as "favorite" reviews) without requiring instant database writes.

### ✨ Key Features

- **Django Forms & ModelForms:** Server-side validation, clean error rendering, automated CSRF protection, and direct model-binding.
- **Class-Based Views (CBVs):** Modular architecture utilizing generic views (`CreateView`, `ListView`, `DetailView`, `TemplateView`, `FormView`) for clean OOP-driven workflows.
- **Session & Cookie Management:** Interactive features like saving user preferences and "favorite" reviews stored temporarily in browser sessions.
- **File & Media Handling:** Support for user file and image uploads using Django's media storage pipeline.
- **Modular Templates:** Built on the Django Template Language (DTL) with template inheritance and custom CSS styling.

### 🛠 Tech Stack

- **Backend:** Python 3.x, Django
- **Database:** SQLite3 (Django ORM)
- **Frontend:** HTML5, CSS3, Django Templates
- **Storage:** Django File Storage / Media pipeline

### 📂 Project Structure

```text
feedback/
│
├── reviews/                # Core application (Forms, Views, Models)
│   ├── forms.py            # Custom Forms and ModelForms
│   ├── models.py           # Review & Feedback data schemas
│   ├── views.py            # Class-Based and Function-Based views
│   └── urls.py             # Route definitions
│
├── profiles/               # User Profile & File upload module (if present)
├── templates/              # HTML templates (base.html, review lists, detail)
├── static/                 # Static assets (CSS styles, scripts)
├── manage.py               # Django execution script
├── requirements.txt        # Project dependencies
└── .gitignore              # Ignored files list

```

🚀 Installation & Setup
Clone the repository:
```
git clone https://github.com/MarkosyanShooshan/feedback.git
cd feedback
```

Create and activate a virtual environment:
Windows:
```
python -m venv venv
venv\Scripts\activate
```

macOS / Linux:
```
python3 -m venv venv
source venv/bin/activate
```

Install dependencies:
```
pip install -r requirements.txt
```

Apply database migrations:
```
python manage.py migrate
```

Run the development server:
```
python manage.py runserver
```

Open http://127.0.0.1:8000/ in your browser.


<span id="armenian"></span>
## 🇦🇲 Հայերեն


Դինամիկ վեբ-հավելված՝ ստեղծված Python-ով և Django ֆրեյմվորքով։ Նախագիծը ցուցադրում է տվյալների հավաքագրման և ձևաթղթերի մշակման (Django Forms & ModelForms), դասերի վրա հիմնված տեսարանների (Class-Based Views), սեսիաների (Sessions) և մեդիա ֆայլերի ներբեռնման հնարավորությունները։

📌 Նախագծի մասին

Feedback նախագծի հիմնական նպատակն է սովորել և կիրառել օգտատերերի կարծիքների ու հետադարձ կապի անվտանգ ընդունումն ու մշակումը։ Հավելվածն ընդգրկում է ձևաթղթերի վալիդացիա (validation), տվյալների պահպանում բազայում, ինչպես նաև սեսիաների միջոցով օգտատիրոջ գործողությունների (օր.՝ «նախընտրած կարծիք» ընտրելու) կառավարում։

✨ Հիմնական հնարավորությունները

Django Forms և ModelForms — Տվյալների անվտանգ մշակում, սերվերային ստուգումներ (validations), սխալների արտածում և CSRF պաշտպանություն։
Class-Based Views (CBVs) — Օբյեկտային մոտեցմամբ տեսարանների կիրառում (CreateView, ListView, DetailView, TemplateView)՝ կոդի կրկնությունից խուսափելու համար։
Սեսիաներ և Քուքիներ (Sessions & Cookies) — Օգտատիրոջ ընտրած «նախընտրելի» կարծիքների պահպանում բրաուզերի սեսիայում՝ առանց բազան ծանրաբեռնելու։
Ֆայլերի և Նկարների Ներբեռնում — Մեդիա ֆայլերի (օր.՝ պրոֆիլի նկարների) ընդունման և պահպանման կառավարում։
Մոդուլային Շաբլոններ — Բազային HTML կառուցվածք և CSS ոճավորում։

👤 Հեղինակ (Author)

- **Shooshan Markosyan** — [GitHub Profile](https://github.com/MarkosyanShooshan)