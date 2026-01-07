🤝 Contributing Guidelines
365 Days of Web Development (ECWoC)

Thank you for your interest in contributing to 365 Days of Web Development.
This document explains how to contribute correctly and ECWoC-specific rules that must be followed.

📌 Mandatory Contribution Flow

⚠️ Do NOT open a Pull Request directly.

All contributors must follow this order:

Create an Issue (Project Proposal)

Wait for allotment / approval

Start working only after assignment

Submit a Pull Request

❌ PRs submitted without issue approval will be closed.

🧾 Step 1: Create an Issue (Required)

Before starting any work, create an Issue mentioning:

Track: Animation or Product

Phase & Day number

Project title

Brief description of what you plan to build

Tech stack

This avoids duplication and helps maintainers guide you early.

🛠 Step 2: Setup & Work
Fork and Clone
git clone https://github.com/<your-username>/365-Days-of-Web-development.git
cd 365-Days-of-Web-development

Create a Branch
git checkout -b username-day-xx

🎬 Animation Track — Required Structure
animation-track/
└── <PHASE_NAME>/
    └── day-xx-project-name/
        ├── index.html
        ├── style.css
        ├── script.js (if needed)
        └── README.md

🏗️ Product Track — Required Structure
product-track/
└── <PHASE_NAME>/
    └── day-xx-project-name/
        ├── README.md
        ├── index.html
        ├── style.css
        ├── script.js
        ├── server.js (if backend)
        ├── routes/ (if backend)
        └── controllers/ (if backend)

📝 Code Comments & Documentation (Mandatory)

This is a learning-focused repository.

Contributors must:

Add comments explaining why the code works

Comment complex logic, animations, API flow, and conditions

Use simple, beginner-friendly language

📌 PRs may be rejected if code lacks explanation.

📦 Commit Rules

Use clear, meaningful commit messages.

git add .
git commit -m "Day xx: short description of work"

🚀 Pull Request Rules

When opening a PR:

Mention the approved Issue number

Mention track + phase + day

Briefly explain what you built

❌ PRs without an approved Issue reference will be rejected.

❌ What Will Not Be Accepted

PR without issue approval

Copy-pasted tutorial code

Missing README.md

Breaking folder structure

Duplicate or low-effort submissions

🧠 Final Note

This repository values learning, clarity, and structure over speed.
Follow the process, document your work, and be open to feedback.
