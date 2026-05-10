# Contributing to BOSC Community Library

First of all, thank you for taking the time to contribute! 
Every contribution, big or small, makes this project better for the entire community.

Please read this guide carefully before submitting anything.

---

## Table of Contents

1. [Code of Conduct](#code-of-conduct)
2. [What Can I Contribute](#what-can-i-contribute)
3. [Step 1: Fork the Repository](#step-1-fork-the-repository)
4. [Step 2: Clone Your Fork](#step-2-clone-your-fork)
5. [Step 3: Create a Branch](#step-3-create-a-branch)
6. [Step 4: Make Your Changes](#step-4-make-your-changes)
7. [Step 5: Commit Your Changes](#step-5-commit-your-changes)
8. [Step 6: Push and Submit a Pull Request](#step-6-push-and-submit-a-pull-request)
9. [Review Process](#review-process)

---

## Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md).

---

## What Can I Contribute

-  New resources, guides, or documentation
-  Bug reports (broken links, errors in guides)
-  Feature suggestions via Issues
-  Reviewing and commenting on open Pull Requests
-  Fixing typos or improving clarity of existing content

---

## Step 1: Fork the Repository

Forking creates your own copy of the project on GitHub.

1. Go to the repository: `https://github.com/JosirexLegacy/BOSC-Community-Library`
2. Click the **"Fork"** button in the top-right corner
3. GitHub will create a copy under your own account

---

## Step 2: Clone Your Fork

Download your fork to your local machine:

```bash
git clone https://github.com/YOUR-GITHUB-USERNAME/BOSC-Community-Library.git
cd BOSC-Community-Library
```

Add the original repository as a remote called `upstream`:

```bash
git remote add upstream https://github.com/JosirexLegacy/BOSC-Community-Library.git
```

This lets you pull in future updates from the main project into your fork.

---

## Step 3: Create a Branch

**Never work directly on `main`.** Always create a new branch for your changes.

```bash
git checkout -b feature/add-python-resources
```

**Branch naming conventions:**

| Type | Format | Example |
|------|--------|---------|
| New feature or content | `feature/short-description` | `feature/add-git-guide` |
| Bug fix | `fix/short-description` | `fix/broken-link-readme` |
| Documentation update | `docs/short-description` | `docs/improve-contributing` |

---

## Step 4: Make Your Changes

- Add files to the correct folder (`/docs` for guides, `/resources` for curated links and tools)
- Follow existing file naming conventions: lowercase, hyphens, no spaces
- Keep content clear, accurate, and accessible to beginners

### Resource File Standards

Every resource file must follow these conventions:

**File naming:** lowercase, hyphens only, no spaces. (`data-structures.md` ✅, `Data Structures.md` ❌)

**Heading hierarchy:** Start at `##` for main sections. Don't skip levels.

**Metadata footer:** Every resource file must end with this exact block:

**Internal links:** Always use relative paths from your file's location.

**RESOURCE_HUB.md:** If you add a new resource file, you must also add an
entry to `RESOURCE_HUB.md`. PRs that add resource files without updating
the hub will be asked to revise before merging.

---

## Step 5: Commit Your Changes

Write clear, descriptive commit messages:

```bash
git add .
git commit -m "feature: add beginner Python resource guide to /resources"
```

**Commit message format:**
Accepted types: `feature`, `fix`, `docs`, `refactor`, `style`, `chore`

---

## Step 6: Push and Submit a Pull Request

Push your branch to your fork:

```bash
git push origin feature/add-python-resources
```

Then on GitHub:

1. Go to your fork
2. Click **"Compare & pull request"**
3. Fill in the PR template
4. Set the base repository to `JosirexLegacy/BOSC-Community-Library` and base branch to `main`
5. Click **"Create Pull Request"**

---

## Review Process

- A maintainer will review your PR within a reasonable timeframe
- You may be asked to make revisions this is a normal part of collaboration
- Once approved, your PR will be merged into `main`
- Your name will be visible in the commit history as a contributor

---

*Thank you for being part of the BOSC Community.*