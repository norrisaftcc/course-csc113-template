# Week_02_Assignment_Track_A_Reference.md

### OPTION A: CODE BUILDERS TRACK (Additional 1.5 hours)

**For students interested in programming, APIs, and technical implementation.**

This is file Week_02_Assignment_Track_A_Reference.md. The rest of Track A is included here, so as not to scare off the Track B students. :^)

#### Additional Task 1: Set Up GitHub Codespaces (30 minutes)

GitHub Codespaces gives you a cloud development environment - no local setup required!

**Steps:**
1. In your `csc113-portfolio` repository, click the green "Code" button
2. Switch to "Codespaces" tab
3. Click "Create codespace on main"
4. Wait for environment to load (2-3 minutes)

**What You Get:**
- VS Code in your browser
- Python already installed
- Terminal access
- All your repository files

**First Task in Codespaces:**
1. Open terminal (bottom panel)
2. Type: `python --version` (verify Python is installed)
3. Create a new file: `week-02-sage/hello_sage.py`
4. Write this code:

```python
# hello_sage.py
# My first Python script in this course

def main():
    print("Hello from SAGE!")
    print("This is my Study Assistant & Guide Engine workspace")
    
    # Get user name
    name = input("What's your name? ")
    print(f"Welcome to CSC-113, {name}!")
    
    # List course goals
    goals = [
        "Learn AI fundamentals",
        "Master prompt engineering",
        "Build with AI tools",
        "Create portfolio projects"
    ]
    
    print("\nYour CSC-113 goals:")
    for i, goal in enumerate(goals, 1):
        print(f"{i}. {goal}")

if __name__ == "__main__":
    main()
```

5. Save the file
6. Run it: `python week-02-sage/hello_sage.py`
7. Test the interaction

**What to Document:**
Create `week-02-sage/technical-setup.md`:

```markdown
# Technical Setup - Code Builders Track

## Codespaces Setup
- [x] Created codespace
- [x] Verified Python installation
- [x] Created first Python script
- [x] Successfully ran script

## Python Version
Python version: [paste output of `python --version`]

## First Script
See `hello_sage.py` for my first Python script in this course.

## Learnings
[Write 2-3 sentences about what was new or challenging in this setup]

## Questions
[Any technical questions you have]
```

#### Additional Task 2: AI-Assisted Python (45 minutes)

Ask Kevin to help you create a simple prompt tracker script.

**Instructions to Give Kevin:**
```
I'm learning Python and I need a simple script that:
1. Asks me for a prompt I want to save
2. Asks me to categorize it (explanation/creative/info/problem-solving)
3. Saves it to a text file called "my-prompts.txt"
4. Lets me view all saved prompts
5. Uses simple Python (I'm a beginner)

Please create this script with lots of comments explaining what each part does.
```

**Your Job:**
1. Work with Kevin to create the script
2. Save it as `week-02-sage/prompt-tracker.py`
3. Test that it works
4. Document the collaboration process

**Create**: `week-02-sage/kevin-coding-session.md`:

```markdown
# AI-Assisted Coding Session with Kevin

## Goal
Create a simple prompt tracker script in Python

## The Conversation
[Paste or summarize your conversation with Kevin]

## What Kevin Generated
[Paste the initial code Kevin gave you]

## What I Modified
[If you changed anything, note it here]

## Testing Results
[Screenshot or describe testing the script]

## Reflection
- What did Kevin do well in generating this code?
- What did you have to clarify or ask for changes?
- Did you understand the code Kevin wrote?
- What Python concepts are you still confused about?

## Code Quality Assessment
[Rate the code Kevin generated: Excellent/Good/Okay/Poor]
[Explain your rating]
```

#### Deliverables (Code Builders Track)
In addition to core assignment:
- [ ] Codespaces created and working
- [ ] `hello_sage.py` script created and tested
- [ ] `technical-setup.md` documenting setup
- [ ] `prompt-tracker.py` script created with Kevin's help
- [ ] `kevin-coding-session.md` documenting the collaboration
- [ ] All code has comments explaining what it does

---
