## Version Control for Developers

This is not “Git commands memorization.”

This is:

* Workflow discipline
* Collaboration mindset
* Production safety
* Real developer habits

Git must prepare students for:

* React projects
* Django teams
* Deployment workflows
* Pull requests & code reviews

---

# 🎯 Learning Outcomes

By end of Day 2, students will:

✅ Understand what Git actually tracks
✅ Create meaningful commits
✅ Use branches confidently
✅ Resolve merge conflicts
✅ Collaborate using pull requests
✅ Avoid destructive mistakes
✅ Understand how Git fits into real teams

---

# 🗓 OVERVIEW

| Day   | Focus                                      |
| ----- | ------------------------------------------ |
| Day 8 | Git Fundamentals & Local Workflow          |
| Day 9 | Collaboration, Branching & Real-World Flow |

---

# 🧱 DAY 8 – Git Foundations & Local Workflow

## 🎯 Goal

Students understand:

* What Git tracks
* How commits work
* How history works
* Why version control matters

---

## 🧠 9:00 – Reset the Mindset

Ask:

Why do we need Git?

Common answers:

* Backup
* Save versions

Correct answer:
Git tracks change history of code over time.

Explain:

Git is a time machine for code.

---

## 🧠 9:30 – What Git Actually Tracks

Git tracks:

* Files
* Changes (diffs)
* Snapshots
* History

Not:

* Running programs
* Servers
* Databases

Explain:

Git = snapshot system, not file overwrite system.

---

## ⚙️ 10:30 – Core Concepts

Working directory
Staging area
Repository

Draw the 3-zone model:

Working → Staging → Repository

This diagram must be memorized.

---

## 🛠 11:30 – Guided Lab 1: First Repo

Students:

* Initialize repo
* Create HTML file
* Add
* Commit

Teach proper commit messages:

Bad:
“update”

Good:
“Add homepage structure”

Train professional behavior early.

---

## 🧠 1:00 – Reading History

Commands:

* git log
* git status
* git diff

Teach:

Developers read history more than they write commits.

---

## 🔄 2:00 – Undoing Mistakes

Safe methods:

* git restore
* git reset (soft explanation)
* amend commit

Teach carefully:

Git is powerful but dangerous.

---

## 🌱 3:00 – Branching Introduction

Why branches exist:

To isolate features.

Create:

feature-navbar branch

Make change.
Switch branches.

Show difference.

This moment changes perspective.

---

## 🛠 4:00 – Mini Exercise

Students:

* Create new feature branch
* Add section to HTML page
* Commit
* Merge back to main

Simple local workflow.

---

# 🎓 End of Day 1

Students understand:

* Snapshot model
* Staging concept
* Commits
* Branching basics
* Merge basics

---

# 🧱 DAY 9 – Collaboration & Real Workflow

This is where Git becomes real.

---

## 🎯 Goal

Students will:

* Work with remote repositories
* Push and pull safely
* Handle merge conflicts
* Use pull request workflow
* Simulate team development

---

## 🌍 9:00 – What Is GitHub?

Explain:

Git = version control tool
GitHub = remote repository hosting

Local vs Remote.

---

## 🛠 9:30 – Connecting to Remote

Students:

* Create GitHub repo
* Add remote origin
* Push code

Explain:

Push = publish your commits.

---

## 🔄 10:30 – Pull & Sync

Explain:

* git pull
* git fetch

Simulate scenario:

Instructor changes remote.
Students must pull updates.

---

## ⚔️ 11:30 – Merge Conflicts (Important)

Simulate:

Two students edit same file.

Trigger conflict.

Walk through:

Conflict markers
Manual resolution
Commit merge

This builds confidence.

---

## 🌳 1:00 – Branching Strategy (Professional)

Introduce simple model:

main → stable code
feature branches → new work

Explain:

Never code directly on main in real teams.

---

## 🛠 2:00 – Simulated Team Exercise

Group of 3:

* Student A builds navbar
* Student B builds footer
* Student C builds blog section

All via branches.

Then:

Pull request → review → merge.

Instructor reviews PR quality.

---

## 🧠 3:30 – Good Commit Culture

Teach:

Small commits
Clear messages
Logical grouping

Example format:

feat: add responsive navbar
fix: correct footer alignment
refactor: clean semantic structure

Prepare for React & Django team workflows.

---

## 🚨 4:00 – Real-World Scenarios

What happens if:

* You push broken code?
* You merge wrong branch?
* You delete main?
* You commit secrets?

Introduce:

.gitignore
Why secrets must not be committed.

---

# 🎓 End of Git Phase Outcomes

Students can:

✅ Create clean commit history
✅ Use branches confidently
✅ Merge safely
✅ Resolve conflicts
✅ Collaborate using pull requests
✅ Think like part of a team

They are now ready for:

⚡ 5-Day JavaScript Deep Dive

Because now they can safely experiment.

---

# 🧠 Why Git Comes Before JS

Because:

JS experimentation = many mistakes.

Without Git:
Students panic.

With Git:
Students experiment confidently.

