# 🏗 5-Day Django Bootcamp

## From Python Scripts to Production-Ready Web Apps

**Prerequisites:**

* Python fundamentals (variables, data structures, functions, modules, file I/O)
* React basics (components, state, props, events)
* HTML & CSS mastery
* Git workflow

**Learning Philosophy:**

* Django = **full-stack backend framework**
* Emphasize models, views, templates (MVT)
* Connect frontend to backend with RESTful principles
* Build maintainable and scalable apps

**Format:** ~8 hours/day

* 30% lecture/concept
* 55% guided coding
* 15% critique and refactor

---

# 🗓 OVERVIEW (Days 25–29)

| Day    | Theme                               | Focus                                                      |
| ------ | ----------------------------------- | ---------------------------------------------------------- |
| Day 25 | Django Fundamentals & Project Setup | Install, project structure, apps, dev server               |
| Day 26 | Models & Database                   | ORM, migrations, relationships, querying                   |
| Day 27 | Views & Templates                   | Function-based views, rendering templates, context         |
| Day 28 | Forms, Validation & CRUD            | Django forms, POST/GET, dynamic CRUD functionality         |
| Day 29 | Mini Project & Integration          | Full web app integrating models, views, templates, CSS, JS |

---

# 🧱 DAY 25 – Django Fundamentals & Project Setup

**Objectives:**

* Understand Django architecture
* Create project and apps
* Run development server

**Morning (9:00–12:00):**

* Django philosophy: MTV (Model-Template-View)
* Install Django, set up virtual environment
* Project structure: `manage.py`, `settings.py`, `urls.py`, `apps/`
* Run development server: `python manage.py runserver`

**Afternoon (1:00–5:00):**

* Create first app (`python manage.py startapp blog`)
* Register app in `settings.py`
* URL routing basics (`urls.py`)
* Guided Lab:

  * Create “Hello World” page
  * Map URL → view → template

**Homework:**

* Build a multi-page site with at least 2 apps and static HTML pages

---

# 🧱 DAY 26 – Models & Database

**Objectives:**

* Define data models
* Work with Django ORM
* Use migrations for database changes

**Morning:**

* Model definition: fields, types, optional/required
* Primary key, auto fields
* Relationships: OneToMany (ForeignKey), ManyToMany, OneToOne

**Afternoon:**

* Migrations: `makemigrations`, `migrate`
* Admin panel: register models, manage data
* Querying: `Model.objects.all()`, `filter`, `get`, `exclude`
* Guided Lab:

  * Build BlogPost model
  * Add test data in admin
  * Query and display posts in shell

**Homework:**

* Expand models with categories/tags, test querying relationships

---

# 🧱 DAY 27 – Views & Templates

**Objectives:**

* Connect models to views
* Render dynamic templates with context
* Use template tags and filters

**Morning:**

* Function-based views (FBVs)
* Rendering templates with `render()`
* URL routing with dynamic parameters (`path('<int:id>/')`)

**Afternoon:**

* Template language:

  * `{{ variable }}`
  * `{% for %}`, `{% if %}`
  * Filters (`|length`, `|date`)
* Guided Lab:

  * Render list of blog posts from model to template
  * Detail page for each post

**Homework:**

* Refactor templates with base layout and block inheritance

---

# 🧱 DAY 28 – Forms, Validation & CRUD

**Objectives:**

* Capture user input with forms
* Validate and save data
* Build full CRUD functionality

**Morning:**

* Django Forms: `forms.Form`, `forms.ModelForm`
* Handling POST requests
* Validating input, showing errors

**Afternoon:**

* Guided Lab:

  * Add comment form to blog posts
  * Create new post form with validation
  * Update & delete functionality
* Connect templates → forms → models for full CRUD flow

**Homework:**

* Build task tracker app with full CRUD operations

---

# 🧱 DAY 29 – Mini Project & Integration

**Objectives:**

* Build a full Django web application
* Integrate HTML/CSS/JS with backend
* Apply Git workflow

**Morning:**

* Plan project: Blog, Task Tracker, or Portfolio app
* Design models, views, templates
* Prepare component hierarchy for frontend

**Afternoon:**

* Implement features:

  * CRUD operations
  * Dynamic templates
  * Form validation
  * Include JS interactivity (e.g., toggles, fetch API)
* Style with CSS from previous bootcamp
* Peer review and code refactor

**Outcome:**

* Students leave with production-ready Django app
* Confident with models, views, templates, forms, validation
* Ready for Wagtail CMS integration

---

# 🧠 Why Django Bootcamp Comes After Python & Before Wagtail

* Python skills now translate into backend logic
* HTML/CSS/JS knowledge ensures proper frontend integration
* Prepares students for CMS workflows and production content management

