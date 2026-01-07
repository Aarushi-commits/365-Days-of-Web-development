🤝 Contributing Guidelines
365 Days of Web Development (ECWoC)

Thank you for your interest in contributing to 365 Days of Web Development.
This document explains how to contribute correctly, the required structure, and the rules for ECWoC participation.

🚨 Important Rule

Do NOT open a Pull Request directly.

All contributors must follow the process below.
PRs that skip any step will be closed without review.

🔁 Contribution Flow (Mandatory)

Create an Issue (Project Proposal)

Wait for project allotment / approval

Start working only after assignment

Submit a Pull Request

🧾 Step 1: Create an Issue

Before writing any code, open a new Issue and include:

Track: Animation or Product

Phase & Day number

Project title

Short project description

Tech stack

This helps:

avoid duplicate work

maintain roadmap quality

ensure fair ECWoC allotment

🛠 Step 2: Setup & Work (Terminal Commands)
🔹 Fork & Clone the Repository
git clone https://github.com/<your-username>/365-Days-of-Web-development.git
cd 365-Days-of-Web-development

🔹 Create a New Branch
git checkout -b username-day-xx


Branch naming format:

username-day-xx

🎬 Animation Track — Required Structure

Use this structure strictly for animation projects:

animation-track/
└── <PHASE_NAME>/
    └── day-xx-project-name/
        ├── index.html
        ├── style.css
        ├── script.js   (if required)
        └── README.md

🏗️ Product Track — Required Structure

Use this structure strictly for product projects:

product-track/
└── <PHASE_NAME>/
    └── day-xx-project-name/
        ├── README.md
        ├── index.html
        ├── style.css
        ├── script.js
        ├── server.js   (if backend)
        ├── routes/     (if backend)
        └── controllers/ (if backend)

📝 Code Comments & Documentation (Mandatory)

This repository is a learning roadmap, not just a code dump.

Contributors must:

Add comments explaining why the code works

Comment:

complex logic

animations & calculations

API flow & conditions

Use simple, beginner-friendly language

PRs may be rejected if code lacks explanation.

📦 Commit Rules

Use clear and meaningful commit messages.

git add .
git commit -m "Day xx: short description of the work"


❌ Avoid messages like:

update

final

done

🚀 Step 3: Open a Pull Request

When creating a PR:

Mention the approved Issue number

Mention track + phase + day

Briefly explain what you built

PRs without an approved Issue reference will be rejected.

❌ What Will NOT Be Accepted

PR without issue approval

Copy-pasted tutorial code

Missing README.md

Broken folder structure

Duplicate or low-effort submissions

🧠 Final Note

This project values:

Learning over speed

Clarity over complexity

Structure over randomness

Follow the process, document your work, and be open to feedback.
