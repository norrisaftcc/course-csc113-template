sage-githubprompt.md

# Addition 1: GitHub Tasks

# GitHub Basics - SAGE Context Document

## Purpose

This document gives SAGE knowledge about GitHub and the professional workflow used in CSC-113. Students will ask questions like “what’s a branch?” and “how do I submit my work?” and SAGE should be able to guide them through our specific workflow.

-----

## Core Concepts

### What is GitHub?

GitHub is a platform for storing, tracking, and collaborating on code and other files. Think of it as:

- **Google Docs for code** - Multiple people can work on the same project
- **Time machine** - Every change is saved, and you can go back to any point
- **Professional portfolio** - Your GitHub profile shows your work to employers

In CSC-113, GitHub is where ALL work happens. It’s not just for submitting—it’s for working.

-----

### Repository (Repo)

A repository is a project folder that GitHub tracks. It contains:

- Your files (code, documents, etc.)
- The complete history of all changes
- Issues, discussions, and project management tools

**In this course:** Each student has their own repositories in the course organization. Your main repo is where SAGE development happens.

-----

### Issues

Issues are tasks, bugs, or ideas—tracked in GitHub rather than on sticky notes or in your head.

**Why we use Issues:**

- Creates a record of what you planned to do
- Lets you (and instructors) see progress
- Links directly to the work that addresses them
- Builds professional habits

**How to write a good Issue:**

- Clear title: “Add github-basics document to SAGE” not “stuff to do”
- Description of what you’re trying to accomplish
- Any relevant details or questions

**In this course:** Create an Issue BEFORE you start working. This is how professionals track their work.

-----

### Branches

A branch is a separate version of your repository where you can make changes without affecting the main version.

**Think of it like this:**

- **Main branch** = The “official” version that works
- **Your branch** = Your workspace where you experiment

**Why we use branches:**

- You can’t break the main version while experimenting
- Multiple people can work on different features simultaneously
- Changes are reviewed before becoming official
- Easy to abandon bad ideas without consequences

**Branch naming in CSC-113:**
Use this pattern: `issue-number-short-description`

- `1-add-introduction`
- `5-sage-core-document`
- `12-fix-readme-typo`

The number links to the Issue you’re addressing.

-----

### Commits

A commit is a saved snapshot of your changes. Every commit has:

- The actual changes to files
- A message describing what changed
- A timestamp and author
- A unique ID (the “hash”)

**How often to commit:**

- After completing a logical chunk of work
- Before trying something risky
- At minimum, every time you stop working

**Writing good commit messages:**

Bad messages:

- “stuff”
- “fixed it”
- “asdfasdf”
- “work”

Good messages:

- “Add SAGE-core.md to context documents”
- “Fix typo in README introduction”
- “Update course overview with Week 2 content”

**The pattern:** Start with a verb, describe WHAT changed, keep it under 50 characters.

-----

### Pull Request (PR)

A Pull Request is how you propose merging your branch changes into the main branch. It’s called a “request” because someone reviews it before it’s accepted.

**What happens in a PR:**

1. You describe what you changed and why
1. Others can see your changes highlighted
1. Reviewers comment and suggest improvements
1. Once approved, changes merge into main
1. Your branch can be deleted (it’s done its job)

**Why PRs matter:**

- Catches mistakes before they reach main
- Creates a record of what changed and why
- Teaches you to explain your work
- Mirrors real professional workflow

**In this course:** All work goes through PRs. You cannot push directly to main—this is intentional.

-----

### The CSC-113 Workflow

This is the exact process for every piece of work in this course:

```
1. CREATE ISSUE
"I'm going to add the github-basics document"

2. CREATE BRANCH
Name it: "3-github-basics" (3 is the Issue number)

3. DO THE WORK
Open Codespaces, make your changes

4. COMMIT REGULARLY
Save progress with clear messages

5. PUSH YOUR BRANCH
Upload your commits to GitHub

6. CREATE PULL REQUEST
Describe your changes, link to Issue
Write: "Fixes #3" to auto-link

7. GET REVIEW
Peer or instructor looks at your work

8. MERGE
Once approved, your changes join main

9. DELETE BRANCH
It's done—clean up after yourself
```

This is not busywork. This is how software development actually works at companies. You’re building professional habits.

-----

### GitHub Codespaces

Codespaces is a development environment that runs in your browser. It’s like having a computer in the cloud set up for coding.

**Why we use Codespaces:**

- No software installation needed on your computer
- Everyone has the same environment (fewer “it works on my machine” problems)
- Directly connected to GitHub
- Free for students

**To open Codespaces:**

1. Go to your repository on GitHub
1. Click the green “Code” button
1. Select “Codespaces” tab
1. Click “Create codespace on [branch-name]”

**Important:** Make sure you’re on the RIGHT BRANCH before opening Codespaces. If you’re on main, your changes will be in the wrong place.

-----

## Common Questions

**Q: Why can’t I just commit directly to main like a normal folder?**
A: Because in professional development, main is protected. It’s the version that “works.” By forcing all changes through PRs, we catch mistakes, create documentation, and learn review skills. This feels like overhead now, but it prevents disasters and is required at any tech job.

**Q: I made changes but they’re not showing up. What happened?**
A: Check these things:

1. Did you save the file? (Ctrl+S or Cmd+S)
1. Did you commit your changes?
1. Did you push your commits to GitHub?
1. Are you looking at the right branch?

**Q: How do I know what branch I’m on?**
A: In Codespaces/VS Code, look at the bottom left corner—it shows the current branch. On GitHub.com, there’s a dropdown near the top left of your repo that shows the branch.

**Q: I accidentally committed to main. What do I do?**
A: Don’t panic. This is exercise. Tell your instructor—there are ways to fix it. For the future: always check your branch before working.

**Q: What’s the difference between commit and push?**
A:

- **Commit** = Save changes locally (like saving a file, but with history)
- **Push** = Upload your commits to GitHub (so others can see them)

You can commit many times before pushing. Push when you want your work backed up online or ready for PR.

**Q: My PR says there are “conflicts.” What does that mean?**
A: Conflicts happen when your changes overlap with other changes to main. It’s like two people editing the same sentence differently. GitHub doesn’t know which version to keep, so you have to decide. Ask for help the first time—this is normal and fixable.

**Q: How often should I commit?**
A: More often than you think. A good rule: if you’d be upset losing this work, commit it. Professional developers often commit every 15-30 minutes of work.

**Q: Can I work on multiple things at once?**
A: Yes, but use separate branches for separate Issues. Don’t mix unrelated changes in one branch—it makes review harder and history confusing.

-----

## Procedures

### Creating a New Issue

1. Go to your repository on GitHub.com
1. Click the “Issues” tab
1. Click “New Issue”
1. Write a clear title (what you’re going to do)
1. Add description if helpful
1. Click “Submit new issue”
1. Note the issue number (you’ll use it for your branch name)

### Creating a Branch

**From GitHub.com:**

1. Go to your repository
1. Click the branch dropdown (shows “main”)
1. Type your new branch name: `[issue-number]-[description]`
1. Click “Create branch: [name] from main”

**From Codespaces:**

1. Click the branch name in the bottom left
1. Select “Create new branch”
1. Type your branch name
1. Press Enter

### Making a Pull Request

1. Push your branch to GitHub
1. Go to your repository on GitHub.com
1. You’ll often see a yellow banner: “Compare & pull request” - click it
1. Or: Click “Pull requests” tab → “New pull request”
1. Make sure it says: `main` ← `your-branch-name`
1. Write a title describing your changes
1. In the description, write `Fixes #[issue-number]`
1. Click “Create pull request”

-----

## What SAGE Should NOT Do

- SAGE should not make commits or PRs for students
- SAGE should not tell students to skip the workflow “just this once”
- SAGE should not dismiss the workflow as unnecessary
- SAGE should encourage students to ask instructors about complex Git problems (like rebasing or force-pushing)

-----

## Connections

This document connects to:

- **course-overview.md** - Mentions the workflow as a core course requirement
- **github-troubleshooting.md** (coming Week 3) - Covers error recovery in detail
- **SAGE-core.md** - SAGE’s encouraging tone when students struggle with workflow

-----

## Key Vocabulary Quick Reference

|Term |Definition |
|---------------------|----------------------------------------------|
|**Repository (repo)**|A project folder tracked by GitHub |
|**Issue** |A tracked task or planned work item |
|**Branch** |A separate version for making changes safely |
|**Main** |The primary branch; the “official” version |
|**Commit** |A saved snapshot of changes |
|**Push** |Upload commits from your computer to GitHub |
|**Pull Request (PR)**|A request to merge your branch into main |
|**Merge** |Combining changes from one branch into another|
|**Codespaces** |Browser-based development environment |
|**Clone** |Download a repo to work locally |
|**Fork** |Copy someone else’s repo to your account |

-----

## Remember

The workflow feels like a lot of steps at first. That’s normal. Within a few weeks, it becomes automatic—like saving a document without thinking about it.

**The mantra:** Issue → Branch → Work → Commit → Push → PR → Review → Merge

Every professional developer follows some version of this process. You’re not doing homework—you’re practicing professional software development.

And if you mess something up? Delete the branch and start again. Failure is just exercise.