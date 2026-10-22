
# IndieHub

An AI-assisted collaboration platform for indie game development teams.

## 1. Project Overview

IndieHub is a learning project designed to help small indie game teams manage projects, tasks, and development resources, with AI-assisted workflow features.

## 2. Goals

- Build a backend service using Java and Spring Boot.
- Store project and task data in MySQL.
- Learn Python through practical scripts and AI service integration.
- Explore LLM API integration and structured AI outputs.
- Practice Git, testing, deployment, and Linux fundamentals.

## 3. Planned Tech Stack

- Java
- Spring Boot
- MySQL
- Python
- Git and GitHub
- Linux
- LLM API integration

## 4. Development Roadmap

- [x] Initialize the repository
- [ ] Complete Java fundamentals
- [ ] Learn Python fundamentals
- [ ] Learn Git and SQL basics
- [ ] Build the Spring Boot backend
- [ ] Implement task management APIs
- [ ] Integrate an AI-assisted task planning feature
- [ ] Add tests and documentation
- [ ] Deploy the application

## 5. Project Status

Currently in the learning and initial development stage.

The repository currently contains project documentation and the license only.
The backend, database setup, Python scripts, and AI integration are planned;
there is no runnable application or build/test command yet.

## 6. Notes

This project is developed incrementally as part of a software engineering learning and internship preparation plan.

## 7. Repository Structure

```text
IndieHub/          # Repository root
|-- README.md      # Project overview and development plan
`-- LICENSE        # MIT license
```

Open the repository root in your editor. Application source directories will be
added here as implementation begins; a second nested `IndieHub/` directory is
not required.

A nested folder left by a local move does not necessarily exist on GitHub.
Inspect its contents and any Git history before moving or deleting it. Never
delete or replace the repository's `.git` directory as part of synchronization.

## 8. Clone and Synchronize

For a new checkout, run these commands from the parent directory where you want
the project to live. The destination `IndieHub` folder must not already exist.

```powershell
git clone https://github.com/LiZhuoyan17/IndieHub.git IndieHub
Set-Location IndieHub
```

For an existing checkout, open its root and check for local changes first:

```powershell
git status
git remote -v
```

Confirm that `origin` points to this repository. If the working tree is clean
and you are on `main`, synchronize with:

```powershell
git pull --ff-only origin main
```

If there are local changes or Git reports diverged history, preserve that work
and inspect the difference before proceeding. Avoid `reset --hard`, `clean`, or
force pushes for routine synchronization.

When adding integrations, keep API keys, passwords, and local environment files
out of commits. Document required configuration with placeholder values only.

## 9. License

This project is licensed under the [MIT License](LICENSE).

