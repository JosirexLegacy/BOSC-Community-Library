\# Contributing to BOSC Community Library



First of all thank you for taking the time to contribute!  

Every contribution, big or small, makes this project better for the entire community.



Please read this guide carefully before submitting anything.



\---



\##  Table of Contents



1\. \[Code of Conduct](#code-of-conduct)

2\. \[What Can I Contribute?](#what-can-i-contribute)

3\. \[Step 1 — Fork the Repository](#step-1--fork-the-repository)

4\. \[Step 2 — Clone Your Fork](#step-2--clone-your-fork)

5\. \[Step 3 — Create a Branch](#step-3--create-a-branch)

6\. \[Step 4 — Make Your Changes](#step-4--make-your-changes)

7\. \[Step 5 — Commit Your Changes](#step-5--commit-your-changes)

8\. \[Step 6 — Push and Submit a Pull Request](#step-6--push-and-submit-a-pull-request)

9\. \[Review Process](#review-process)



\---



\## Code of Conduct



By participating in this project, you agree to abide by our \[Code of Conduct](CODE\_OF\_CONDUCT.md).



\---



\## What Can I Contribute?



\-  New resources, guides, or documentation

\-  Bug reports (broken links, errors in guides)

\-  Feature suggestions via Issues

\-  Reviewing and commenting on open Pull Requests

\-  Fixing typos or improving clarity of existing content



\---



\## Step 1 — Fork the Repository



Forking creates your own copy of the project on GitHub.



1\. Go to the repository: `https://github.com/YOUR-USERNAME/BOSC-Community-Library`

2\. Click the \*\*"Fork"\*\* button in the top-right corner

3\. GitHub will create a copy at: `https://github.com/YOUR-GITHUB-USERNAME/BOSC-Community-Library`



\---



\## Step 2 — Clone Your Fork



Download your fork to your local machine:



```bash

git clone https://github.com/YOUR-GITHUB-USERNAME/BOSC-Community-Library.git

cd BOSC-Community-Library

```



Add the original repository as a remote called `upstream` (so you can sync changes later):



```bash

git remote add upstream https://github.com/ORIGINAL-OWNER/BOSC-Community-Library.git

```



\---



\## Step 3 — Create a Branch



\*\*Never work directly on `main`.\*\* Always create a new branch for your changes.



Name your branch descriptively:



```bash

git checkout -b feature/add-python-resources

```



\*\*Branch naming conventions:\*\*

| Type | Format | Example |

|------|--------|---------|

| New feature/content | `feature/short-description` | `feature/add-git-guide` |

| Bug fix | `fix/short-description` | `fix/broken-link-readme` |

| Documentation | `docs/short-description` | `docs/improve-contributing` |



\---



\## Step 4 — Make Your Changes



\- Add your files to the correct folder (`/docs` for guides, `/resources` for links/tools)

\- Follow the existing file naming style (lowercase, hyphens, no spaces)

\- Keep content clear, accurate, and beginner-friendly



\---



\## Step 5 — Commit Your Changes



Write clear, descriptive commit messages:



```bash

git add .

git commit -m "feature: add beginner Python resource guide to /resources"

```



\*\*Commit message format:\*\*

type: short description of what you did

Types: `feature`, `fix`, `docs`, `refactor`, `style`



\---



\## Step 6 — Push and Submit a Pull Request



Push your branch to your fork:



```bash

git push origin feature/add-python-resources

```



Then:

1\. Go to your fork on GitHub

2\. Click \*\*"Compare \& pull request"\*\*

3\. Fill in the PR template that appears

4\. Set the base branch to `main` on the original repository

5\. Click \*\*"Create Pull Request"\*\*



\---



\## Review Process



\- A maintainer will review your PR within a few days

\- You may be asked to make changes this is normal and constructive

\- Once approved, your PR will be merged into `main`

\- Your contribution will be credited in the project



\---



\*Thank you for being part of the BOSC Community! \*

