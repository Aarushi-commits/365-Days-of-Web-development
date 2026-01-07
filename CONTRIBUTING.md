🤝 Contributing to 365 Days of Web Development
ECWoC 2025 | Official Contribution Guide

Welcome! This document explains how to contribute, what structure to follow, and mandatory rules for contributors participating through ECWoC 2025.

🚨 Important Notice

❗ Do NOT open a Pull Request directly.

All contributors must follow the defined workflow.
Pull Requests that do not follow this process will be closed without review.

🔁 Contribution Workflow (Mandatory)

All contributions must follow this exact order:

📝 Create an Issue (Project Proposal)

⏳ Wait for approval / allotment

🛠️ Start working after assignment

🚀 Submit a Pull Request

🧾 Step 1: Create an Issue (Project Proposal)

Before writing any code, open a new Issue and clearly mention:

Track:

🎬 Animation

🏗️ Product

Phase & Day number

Project title

Short description of what you plan to build

Tech stack you will use

✅ Why this is required

Prevents duplicate contributions

Helps maintain roadmap quality

Ensures fair project allotment (ECWoC rule)

🛠️ Step 2: Local Setup (Terminal Commands)
🔹 Fork & Clone the Repository
git clone https://github.com/<your-username>/365-Days-of-Web-development.git
cd 365-Days-of-Web-development

🔹 Create a New Branch
git checkout -b username-day-xx


Branch naming format:

username-day-xx

Example: alex-day-45

🎬 Animation Track — Required Project Structure

Use this structure strictly for animation-based projects:

animation-track/
└── <PHASE_NAME>/
    └── day-xx-project-name/
        ├── index.html
        ├── style.css
        ├── script.js   (if required)
        └── README.md

Animation Project README must include:

Project title

Day number

Objective

Animation concepts used

How to run the project

🏗️ Product Track — Required Project Structure

Use this structure strictly for product-based projects:

product-track/
└── <PHASE_NAME>/
    └── day-xx-project-name/
        ├── README.md
        ├── index.html
        ├── style.css
        ├── script.js
        ├── server.js        (if backend)
        ├── routes/          (if backend)
        └── controllers/     (if backend)

Product Project README must include:

Project title

Day number

Problem statement

Features

Tech stack

How to run (frontend / backend)

📝 Code Comments & Documentation (Mandatory)

This repository is a learning roadmap, not just a code archive.

All contributors must:

🧠 Explain why the code works, not just what it does

✍️ Add comments for:

complex logic

animations & calculations

API routes & data flow

authentication or validation logic

🗣️ Use simple, beginner-friendly language

📌 Pull Requests may be rejected if important logic is not explained.

📦 Commit Message Guidelines

Use clear, meaningful commit messages.

git add .
git commit -m "Day xx: short, meaningful description"

✅ Good Examples

Day 60: Scroll-based parallax landing page

Day 112: JWT authentication API

❌ Bad Examples

update

final

done

🚀 Step 3: Open a Pull Request

When creating your Pull Request:

🔗 Reference the approved Issue number

📍 Mention track + phase + day

📝 Briefly explain what you built

❗ PRs without an approved Issue reference will be rejected.

❌ What Will NOT Be Accepted

❌ Pull Requests without issue approval

❌ Missing README.md

❌ Breaking the folder structure

❌ Duplicate or low-effort submissions

🧠 Core Principles

This project values:

Learning over speed

Clarity over complexity

Structure over randomness

Consistency over shortcuts

🙌 Final Note

By contributing here, you are helping build a public learning roadmap for thousands of learners.

Follow the process, document your work, and contribute with intent.
