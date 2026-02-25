# 🧩 5-Day Wagtail Bootcamp

## From Django Apps to CMS-Powered Production Sites

**Prerequisites:**

* Django backend mastery (models, views, templates, forms, CRUD)
* HTML, CSS, JS, React basics
* Git workflow

**Learning Philosophy:**

* Wagtail = **production CMS** built on Django
* Emphasize content management, page types, and templates
* Teach best practices for real-world websites
* Integrate frontend & backend workflows

**Format:** ~8 hours/day

* 30% lecture/concept
* 55% guided coding & CMS hands-on
* 15% critique and production best practices

---

# 🗓 OVERVIEW (Days 30–34)

| Day    | Theme                                | Focus                                             |
| ------ | ------------------------------------ | ------------------------------------------------- |
| Day 30 | Wagtail Fundamentals & Setup         | Install, project structure, pages, admin          |
| Day 31 | Page Models & Content Management     | Custom page types, fields, snippets               |
| Day 32 | Templates, StreamField & Media       | Dynamic templates, rich content, images, video    |
| Day 33 | Forms, Search & Advanced Features    | User forms, search, workflows, permissions        |
| Day 34 | Mini Project & Production Deployment | Build full Wagtail site, Git workflow, deployment |

---

# 🧱 DAY 30 – Wagtail Fundamentals & Setup

**Objectives:**

* Understand Wagtail architecture
* Install & configure project
* Navigate admin interface

**Morning (9:00–12:00):**

* Wagtail vs Django: why use a CMS
* Install Wagtail, start project: `wagtail start mysite`
* Project structure overview
* Run server, access admin at `/admin/`

**Afternoon (1:00–5:00):**

* Create home page in admin
* Add basic content: title, body text
* Parent/child pages in tree
* Guided Lab:

  * Build multi-page site structure
  * Explore Wagtail admin UI

**Homework:**

* Plan site structure for mini project (3–4 page types)

---

# 🧱 DAY 31 – Page Models & Content Management

**Objectives:**

* Create custom page types
* Use models to structure content
* Leverage snippets for reusable content

**Morning:**

* Page models: `class BlogPage(Page)`
* Fields: CharField, RichTextField, DateField, ImageField
* Meta data: `search_fields`, `content_panels`

**Afternoon:**

* Snippets: reusable content (e.g., authors, categories)
* Guided Lab:

  * Create `BlogPage` and `Author` snippet
  * Add blog posts via admin
  * Display authors & categories dynamically

**Homework:**

* Add 3 blog posts with authors and categories

---

# 🧱 DAY 32 – Templates, StreamField & Media

**Objectives:**

* Build dynamic templates
* Use StreamField for flexible content
* Handle images, video, and media

**Morning:**

* Template hierarchy in Wagtail
* Access page fields in templates: `{{ page.title }}`, `{{ page.body }}`
* StreamField basics: text blocks, image blocks, custom blocks

**Afternoon:**

* Guided Lab:

  * Add StreamField to BlogPage
  * Allow rich content layout: heading, paragraph, image
  * Add media gallery block with multiple images
* CSS styling integration
* Render dynamic content in templates

**Homework:**

* Refactor homepage to use StreamField for hero section, feature blocks

---

# 🧱 DAY 33 – Forms, Search & Advanced Features

**Objectives:**

* Capture user input with Wagtail forms
* Add search functionality
* Understand workflows, permissions

**Morning:**

* Wagtail forms: `AbstractForm`, `FormBuilder`
* Form validation, save submissions
* Guided Lab: Contact form page

**Afternoon:**

* Search: Wagtail search API
* Workflows: scheduling, draft approval
* Permissions: page editor vs admin
* Guided Lab:

  * Add search page
  * Add contact form page
  * Assign permissions for content editors

**Homework:**

* Add search bar and contact form to mini project

---

# 🧱 DAY 34 – Mini Project & Production Deployment

**Objectives:**

* Build a full Wagtail site
* Integrate templates, CSS, JS
* Follow Git workflow
* Prepare for production deployment

**Morning:**

* Plan mini project site: e.g., blog + portfolio + contact page
* Create page models, snippets, templates
* Implement forms and dynamic content

**Afternoon:**

* Deploy site locally
* Integrate CSS from previous bootcamp
* Add JS interactions for dynamic components
* Peer review & critique
* Prepare for production deployment (Heroku / DigitalOcean / AWS)

**Outcome:**

* Students leave with a fully functional Wagtail CMS site
* Confident creating pages, StreamField blocks, forms, search, and media galleries
* Ready for production-ready full-stack web development

---

# 🧠 Why Wagtail Bootcamp Comes Last

* Students already understand Django models, views, templates
* Can leverage React for interactive components if desired
* CMS introduces real-world workflow and content management best practices
* Prepares for scalable, maintainable websites in production

---

✅ With Wagtail Bootcamp complete, your **full 34-day full-stack roadmap** is now covered:

* HTML Deep Dive – 3 Days
* CSS Mastery – 3 Days
* Git Bootcamp – 2 Days
* JavaScript Bootcamp – 5 Days
* Python Bootcamp – 5 Days
* React Bootcamp – 5 Days
* Django Bootcamp – 5 Days
* Wagtail Bootcamp – 5 Days

