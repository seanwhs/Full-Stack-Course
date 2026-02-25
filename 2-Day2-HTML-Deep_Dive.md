# 🌐 HTML Deep Dive (3 Days)

## Structural Thinking for Full Stack Developers

Philosophy:
HTML is not about tags.
HTML is about:

* Structure
* Meaning
* Accessibility
* Data flow preparation
* Clean architecture for CSS & JS

Each day: ~8 hours
Format: 35% instruction, 55% build, 10% critique

---

# 🗓 OVERVIEW

| Day   | Theme                                         |
| ----- | --------------------------------------------- |
| Day 2 | Document Structure & Semantic Foundations     |
| Day 3 | Information Architecture & Multi-Page Systems |
| Day 4 | Forms, Data & Production-Ready HTML           |

---

# 🧱 DAY 2 – Document Structure & Semantic Foundations

## 🎯 Objectives

By end of Day 2, students can:

✅ Write a clean HTML document from scratch
✅ Understand DOM as a tree
✅ Use semantic tags correctly
✅ Structure content intentionally
✅ Think hierarchically
✅ Avoid div-spaghetti

---

## 🧠 9:00 – Re-anchor Mental Model (From Day 1)

Whiteboard:

HTML → DOM → CSS → JS → Render

Ask:
What does browser actually do with HTML?

Explain:
Browser parses text → builds DOM tree → renders structure.

HTML is data for the browser.

---

## 🏗 9:30 – Proper HTML Document Structure

Teach the minimal professional template:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Page Title</title>
</head>
<body>

</body>
</html>
```

Explain:

* DOCTYPE
* html lang
* meta charset
* viewport (future CSS relevance)
* separation of concerns

Explain why this matters for production apps.

---

## 🌳 10:30 – DOM Tree & Hierarchy

Core concepts:

* Parent
* Child
* Sibling
* Nesting
* Depth

Draw example DOM tree on whiteboard.

Exercise:
Predict the tree from given HTML.

Train predictive reasoning.

---

## 📚 11:30 – Core Content Tags (Used Properly)

Not a tag list — but structure logic.

Headings:

* One h1 per page (document title)
* Logical descending order

Paragraphs:

* Content grouping

Lists:

* When to use ul vs ol
* Lists are not for spacing

Links:

* Internal vs external
* Anchor as navigation tool

Images:

* alt attribute (accessibility mindset starts here)

---

## 🛠 1:00 – Guided Build 1: Structured Profile Page

Constraints:

* Must use proper heading hierarchy
* Must use semantic grouping
* No CSS
* No inline styles
* No random divs

Sections required:

* Header
* About
* Skills (list)
* Projects
* Footer

Focus:
Structure first, not aesthetics.

---

## 🧩 3:00 – Semantic HTML Deep Dive

Introduce properly:

* header
* nav
* main
* section
* article
* aside
* footer

Teach decision logic:

When to use:

* section?
* article?
* div?

Rule:
Use semantic first.
Use div only when no semantic alternative.

---

## 🔎 4:00 – DOM Inspection Lab

Students:

* Inspect their page in DevTools
* View DOM tree
* Identify hierarchy depth

Then refactor if needed.

---

## 📝 Homework

Rebuild profile page cleaner.
Add navigation bar (HTML only).

---

# 🧱 DAY 3 – Information Architecture & Multi-Page Systems

Now we scale beyond single page thinking.

---

## 🎯 Objectives

Students will:

✅ Build multi-page sites
✅ Organize file structure properly
✅ Use navigation correctly
✅ Think in information architecture
✅ Prepare for Django template thinking

---

## 🧠 9:00 – Critique Session

Review homework publicly.

Evaluate:

* Heading logic
* Sectioning correctness
* Overuse of div
* Missing alt text

Teach professional critique culture.

---

## 🏛 9:45 – Information Architecture

Explain:

Before coding:
You design content hierarchy.

Example:

Landing Page structure:

* Hero
* Features
* Testimonials
* CTA
* Footer

Draw site map.

Teach:
Plan before build.

---

## 📁 10:45 – File & Folder Structure

Professional structure:

/project
/index.html
/about.html
/contact.html
/assets
/images

Explain:
Clean structure now makes Django easier later.

---

## 🔗 11:30 – Linking Between Pages

Teach:

* Relative paths
* Absolute paths
* Common mistakes

Exercise:
Break a link intentionally → debug it.

Train debugging early.

---

## 🛠 1:00 – Guided Build 2: Multi-Page Website

Build:

* Home
* About
* Contact

Requirements:

* Working navigation
* Logical structure
* Proper headings
* Semantic grouping

No CSS yet.

---

## 🌍 3:00 – Accessibility & Professional HTML

Introduce:

* alt text
* meaningful link text
* proper heading structure
* label for form (preview for Day 4)

Explain:

HTML is not visual.
It’s structural and semantic.

---

## 🧠 4:00 – Architecture Exercise

Ask:

How would this site become dynamic?

Where would database content plug in?

Introduce idea of:

Static HTML → Django template later.

Prepare mental bridge to backend.

---

## 📝 Homework

Add blog page:

* Multiple articles
* Proper article tags
* Consistent structure

---

# 🧱 DAY 4 – Forms, Data & Production-Ready HTML

This is where HTML connects to backend.

---

## 🎯 Objectives

Students will:

✅ Understand how forms send data
✅ Use input types correctly
✅ Understand GET vs POST
✅ Prepare for backend integration
✅ Build production-quality HTML

---

## 🧠 9:00 – Review Blog Homework

Focus on:

* Article usage
* Sectioning correctness
* Structural clarity

---

## 📝 9:45 – Forms Deep Dive

Teach:

```html
<form action="/submit" method="POST">
  <label for="email">Email</label>
  <input type="email" id="email" name="email">
  <button type="submit">Submit</button>
</form>
```

Explain deeply:

* action
* method
* name attribute (critical for backend)
* label association
* input types

Explain:
Backend reads “name” field.

This prepares them for Django.

---

## 🔄 11:00 – What Happens When Form Submits?

Reinforce Day 1 model:

Browser → HTTP Request → Server → Response

Explain GET vs POST conceptually.

---

## 🛠 11:30 – Guided Build 3: Production Contact Form

Requirements:

* name
* email
* message
* dropdown
* checkbox
* radio button

Must use:

* labels
* field grouping
* proper semantics

---

## 🌐 1:30 – HTML Validation & Clean Code

Teach:

* Indentation
* Consistency
* Clean nesting
* Avoid inline styles
* Avoid deprecated tags

Professional standards begin here.

---

## 🧠 2:30 – Mini Capstone: Static Product Website

Build:

* Homepage
* Product listing page
* Product detail page
* Contact form

Focus:
Structure only.

No styling.

---

## 🔍 4:00 – Code Review & Refactor

Instructor checks:

* Semantic correctness
* Accessibility basics
* Clean hierarchy
* Correct form setup

Students refactor live.

---

# 🎓 End of HTML Phase Outcomes

Students can:

✅ Build structured multi-page sites
✅ Use semantic HTML properly
✅ Build accessible forms
✅ Understand how data flows to backend
✅ Think hierarchically
✅ Prepare clean markup for CSS
✅ Prepare clean markup for Django templates

They are now ready for:

* 3 Days CSS (layout systems)
* 2 Days Git (workflow discipline)
* 5 Days JS (behavior layer)
* 5 Days Python (backend logic)
* 5 Days React (frontend framework)
* 5 Days Django (backend framework)
* 5 Days Wagtail (CMS & production systems)

---

# 🧠 Why This HTML Phase Matters

Bad HTML:
→ Bad CSS
→ Hard JS
→ Messy Django templates
→ Production chaos

Good HTML:
→ Clean CSS
→ Predictable JS
→ Easy templating
→ Professional systems

HTML is foundation.

