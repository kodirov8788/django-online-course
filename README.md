# Django Project

A Django-based online course and quiz application focused on course enrollment, assessment, and admin-managed educational content.

## What This Project Shows
- Familiarity with classic server-rendered web application patterns
- Use of Django models, admin, routing, and view logic in a real domain
- Education-oriented product flows such as enrollment and exam results

## Why This Stack / Tooling
- **Django** was chosen because it provides an integrated stack: ORM, admin panel, auth primitives, routing, and templating.
- For an education product with content, users, submissions, and admin workflows, Django reduces infrastructure overhead compared with building every layer manually.
- Server-rendered templates are a practical choice for smaller products where developer speed matters more than a separate SPA frontend.

## Key Domain Objects Visible In The Repo
- Courses and lessons
- Instructors and learners
- Questions, choices, and submissions
- Enrollment and exam result flows

## Routing / Flow Examples
- Course list and detail pages
- Registration and login routes
- Enrollment flow
- Submission and exam result flow

## Current Repository Shape
This repository currently contains app-level Django files rather than a full polished project scaffold. The README documents the intent and structure so reviewers can still understand the architecture quickly.

## Why It Matters For Hiring
This repo shows breadth. It demonstrates comfort with a batteries-included Python web framework and a different set of trade-offs from the Node.js and Next.js projects in the portfolio.
