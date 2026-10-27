# Backend Development Workspace

**Logan Runyan**  
Application Development I: Backend | Carlow University

## 1. Who am I?

I'm a computer science major at Carlow University with minors in game development and web design. I'm interested in game development and software development, and I want to get better at understanding how applications work behind the scenes.

## 2. What is this workspace for?

This repository is my central workspace for Application Development I: Backend. It will hold my projects, practice code, learning notes, and reference materials as I work toward the final REST API project. Keeping everything together should make it easier to find examples and see how my work improves throughout the course.

## 3. What do I want to learn?

My main goal is to build a backend application that I understand well enough to explain and troubleshoot myself. I want to learn how to:

- Write and debug backend scripts.
- Build RESTful APIs that handle requests and return useful responses.
- Design relational databases and use SQL to work with data.
- Implement authentication and authorization to protect user accounts and resources.
- Test successful requests, invalid input, and other error cases.
- Deploy an application and manage changes with Git and GitHub.

I also want to get into the habit of making smaller commits with clear messages instead of saving everything in one large update.

## 4. How will I use this repository throughout the semester?

I'll organize exercises and projects by unit, update my learning log as I practice new skills, and add helpful links to the resources file. I'll use the Git reference when I need a reminder about commands. Before each commit, I'll review my changes and write a message that describes what I completed. I'll push regularly so the remote repository stays up to date.

As the course progresses, I'll add project instructions, examples, and notes about problems I solve. By the end of the semester, I want this repository to be a useful reference and a record of my progress that I can discuss when applying for internships.

## Workspace contents

| File or folder | Purpose |
| --- | --- |
| [learning-log.md](learning-log.md) | Goals, progress checklist, and future learning entries. |
| [resources.md](resources.md) | Useful documentation and backend development references. |
| [git-reference.md](git-reference.md) | Personal Git command cheat sheet. |
| [unit-02-version-control/](unit-02-version-control/) | Version control exercises and notes. |
| [unit-03-backend-scripting/](unit-03-backend-scripting/) | Backend scripting projects and practice. |
| [unit-04-advanced-scripting/](unit-04-advanced-scripting/) | Advanced scripting projects and notes. |
| [unit-05-restful-apis/](unit-05-restful-apis/) | REST API exercises and documentation. |

## Working locally

Clone this repository using its GitHub URL, then open the folder in VS Code:

```bash
git clone https://github.com/ltr5147/backend-development-workspace.git
cd backend-development-workspace
code .
```

Review and save a change:

```bash
git status
git diff
git add .
git diff --staged
git commit -m "Describe the completed change"
git push
```

View the commit history:

```bash
git log --oneline
```
