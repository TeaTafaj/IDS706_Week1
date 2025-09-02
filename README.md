# IDS706_Week1
Class Assignment
Author: Tea Tafaj
Course: IDS 706 (Data Engineering / MIDS)
Repo: IDS706_Week1

This repository contains my Week 1 assignment, designed to help us learn the essentials of Git (local version control) and GitHub (remote hosting, collaboration, and workflows). The goal is to become comfortable cloning a repo, creating branches, committing changes, pushing to GitHub, and opening pull requests (PRs)—plus a quick intro to README writing and good project hygiene.

What This Assignment Teaches:
Version control habits: small, descriptive commits and meaningful branch names.
Collaboration flow: working on branches, using PRs for review, and keeping main clean.
Documentation basics: including a project overview, setup steps, and usage instructions

What I Did:
Created this repo on GitHub.
Opened it in Codespaces | benefiting from the free-period of Codespace
Added: Automation command (Makefile), Python dependencies (requirements.txt), sample script (hello.py), unit tests for the script (test_hello.py)
Committed and pushed everything straight from the browser.


Setup & Usage
1. Install dependencies - make install
3. Run tests - make test
4. Format Code - make format
5. Lint Code - make lint
6. Clean Project files - make clean

Continuous Integration (CI/CD)
The repository includes a GitHub Actions workflow (ci.yml) that runs automatically on every push and pull request.
The pipeline performs the following steps:
Installs dependencies.
Runs lint checks using flake8.
Executes tests with pytest.
Reports results in the Actions tab.

Key Learnings for me:
2. Creating repositories in Github
4. Connecting Github with Local space
5. Starting over and using Codespace when something goes wrong when pushing from VS to Github
6. checking that "tab" and not "space" is used in script - understand that was the reason it wasn't working in the first place
7. trying make lint earlier in the process is wise
8. Core Git operations: add ., commit, push





