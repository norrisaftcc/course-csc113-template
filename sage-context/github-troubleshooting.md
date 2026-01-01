# GitHub Troubleshooting - SAGE Context Document

## Purpose

This document helps SAGE diagnose and fix common GitHub problems that students encounter. The goal is to help students recover from mistakes quickly and learn from them. Every error here is normal—even experienced developers hit these issues.

---

## Core Concepts

### The Troubleshooting Mindset

When something goes wrong with GitHub:

1. **Don't panic** - Almost everything is fixable
2. **Identify the symptom** - What exactly is happening?
3. **Check the basics** - Are you on the right branch? Did you save?
4. **Try the simple fix first** - Most problems have simple solutions
5. **Ask for help if stuck** - That's what instructors and SAGE are for

**Remember:** "Failure is just exercise. Delete the branch and try again."

---

## Troubleshooting Guide

### "I can't push to main"

**Error message:** `remote: error: GH006: Protected branch update failed`

**Why this happens:** Main is protected intentionally. You can't push directly to main—all changes must go through Pull Requests.

**This is not a bug—it's the point.**

**Fix:**
1. Check what branch you're on (bottom left in VS Code/Codespaces)
2. If you're on main, create a new branch first
3. Make your changes on the branch
4. Push the branch
5. Create a Pull Request

**Prevention:** Always create a branch before making changes. Check your branch before starting work.

---

### "I accidentally committed to main"

**What happened:** You made changes while on the main branch locally.

**Fix (if you haven't pushed yet):**
1. Your commits are local only—they're not on GitHub yet
2. Create a new branch: this brings your commits with you
3. Switch to main and reset it: `git checkout main && git reset --hard origin/main`
4. Now your commits are safely on your new branch

**Fix (if you already tried to push and it failed):**
Same as above—the push failed because main is protected, so your commits are still local.

**Fix (if this is confusing):**
Ask your instructor. They can help you sort it out. This is recoverable.

**Prevention:** Always check your branch before making changes. The branch name is visible in the bottom left corner.

---

### "My changes aren't showing up on GitHub"

**Symptom:** You made changes but can't see them on GitHub.com.

**Diagnosis checklist:**

| Check | How to verify | Fix if wrong |
|-------|---------------|--------------|
| **Did you save the file?** | Look for dot (●) next to filename | Press Ctrl+S / Cmd+S |
| **Did you commit?** | Source Control panel shows no changes | Stage and commit your changes |
| **Did you push?** | Check if branch shows "publish" or "sync" | Click Sync Changes or push |
| **Right branch on GitHub?** | Use branch dropdown on GitHub.com | Switch to your branch |

**Most common cause:** Forgetting to push. Commit saves locally; push uploads to GitHub.

---

### "My PR says there are conflicts"

**Error message:** `This branch has conflicts that must be resolved`

**Why this happens:** Your branch and main have both changed the same part of a file. GitHub doesn't know which version to keep.

**What it looks like in the file:**
```
<<<<<<< your-branch
Your version of the code
=======
Main's version of the code
>>>>>>> main
```

**Fix:**
1. Open the file with conflicts
2. Look for the `<<<<<<<`, `=======`, and `>>>>>>>` markers
3. Decide which version to keep (or combine them)
4. Delete the conflict markers
5. Save, commit, and push

**Beginner tip:** If this is confusing, ask for help the first time. Once you've done it once, it makes sense.

**Prevention:** Pull/sync from main regularly, especially before creating a PR.

---

### "I can't find my branch"

**Symptom:** Your branch seems to have disappeared.

**Possible causes:**

**1. You're looking in the wrong place:**
- On GitHub.com, use the branch dropdown to switch branches
- The branch might exist but you're viewing main

**2. The branch was deleted after merging:**
- This is normal! Branches are deleted after PRs merge
- Your work is in main now—check there

**3. You never pushed the branch:**
- The branch exists locally but not on GitHub
- Push your branch: click "Publish Branch" in VS Code

**4. You created it in Codespaces but are looking on GitHub.com:**
- Push from Codespaces first

---

### "My branch is behind main"

**Message:** `This branch is X commits behind main`

**Why this happens:** Other changes were merged to main after you created your branch. This is normal.

**When it matters:** Only if those changes affect files you're also changing (which causes conflicts).

**Fix (simple way):**
1. On your PR page, look for "Update branch" button
2. Click it to merge main into your branch
3. Resolve any conflicts if they appear

**Prevention:** For long-running branches, periodically sync with main.

---

### "My Codespace won't start" or "Codespace is slow"

**Possible issues:**

**1. Timeout:**
- Codespaces stop after inactivity (usually 30 min)
- Just restart it from the Codespaces tab

**2. Browser issues:**
- Try refreshing the page
- Try a different browser
- Clear cache if persistent

**3. Resource limits:**
- Free tier has monthly hours limit
- If you hit the limit, you'll need to wait or use local Git

**4. Wrong branch:**
- Make sure you started Codespace on the right branch
- You can switch branches inside the running Codespace

---

### "I pushed to the wrong branch"

**What happened:** Your commits went to a branch you didn't intend.

**Fix:**
1. Create the correct branch from where you are now
2. Your commits will come with you to the new branch
3. The old branch still exists with those commits—that's fine, you can delete it later

**Or if you need those commits on an existing branch:**
Ask your instructor—this involves cherry-picking or rebasing, which is more advanced.

---

### "Permission denied" or "Authentication failed"

**Error message:** `Permission denied (publickey)` or similar

**Why this happens:** GitHub doesn't recognize your credentials.

**Fix (in Codespaces):**
- Codespaces should handle authentication automatically
- Try closing and reopening Codespaces
- Make sure you're logged into GitHub

**Fix (local Git):**
- You may need to set up SSH keys or use HTTPS with a token
- Follow GitHub's authentication guide
- Ask your instructor if stuck

---

### "I deleted something I needed"

**Good news:** Git keeps history of everything. Almost nothing is truly lost.

**If you deleted a file:**
1. Check the Source Control panel for the deletion
2. Right-click → Discard Changes to undo

**If you already committed the deletion:**
1. You can recover the file from a previous commit
2. Ask SAGE or your instructor for the exact commands

**If you deleted a branch:**
1. If the PR was merged, your work is in main
2. If not, GitHub keeps deleted branches briefly—check the PR page
3. Ask your instructor for recovery help

**Remember:** This is why we commit often. More commits = more recovery points.

---

## Common Questions

**Q: I'm scared I'll break something.**
**A:** That's normal, but here's the good news: main is protected, so you literally cannot break the main version. Your branch is your sandbox. If you mess it up completely, delete it and start fresh. That's not failure—that's using Git correctly.

**Q: Should I ask for help or try to fix it myself?**
**A:** Try the simple fixes first (this document). If you're stuck for more than 15-20 minutes, ask for help. Struggling is learning; suffering is just wasted time.

**Q: What's the worst that can happen?**
**A:** Honestly? You might lose some uncommitted work. That's why we commit often. Everything committed is recoverable. The main branch is protected. The worst case is usually "I have to redo a few hours of work"—annoying but not catastrophic.

**Q: I don't understand what went wrong.**
**A:** That's okay. Describe what you were trying to do, what you expected to happen, and what actually happened. This helps SAGE or your instructor diagnose the problem.

---

## Prevention Checklist

Before starting work:
- [ ] Check that you're on the right branch (not main)
- [ ] If starting new work, create a new branch from an Issue

While working:
- [ ] Save files frequently
- [ ] Commit after completing chunks of work
- [ ] Push at least once per session

Before creating a PR:
- [ ] Check that all changes are committed
- [ ] Make sure branch is pushed to GitHub
- [ ] Review your own changes in the PR

---

## What SAGE Should NOT Do

- Attempt complex Git operations (rebasing, force pushing, cherry-picking)
- Suggest workarounds that bypass the standard workflow
- Make students feel bad about common mistakes
- Skip to advanced solutions before trying simple ones

**When to escalate:** If the student has tried the basic fixes and is still stuck, suggest they ask their instructor. Some Git situations need hands-on help.

---

## Connections

This document connects to:

- **github-basics.md** - The workflow that prevents many of these problems
- **SAGE-core.md** - The encouraging tone to use when students are frustrated
- **course-overview.md** - Reminder that struggling is part of learning

---

## Remember

Every developer—even experts with decades of experience—has made these mistakes. The difference is that experienced developers:

1. Know the mistakes are recoverable
2. Have seen them before so they recognize them faster
3. Ask for help when stuck instead of suffering

You're learning the recovery skills now. Soon these will be minor inconveniences, not crises.

**Failure is just exercise. Delete the branch and try again.**
