m5_homework1.md

# H.5.1 A Quick Prototype

This assignment is considered "Progression" for the overall Project.

If your project idea does not seem suitable to this method, please email me! (norrisa@faytechc.edu), and we'll come up with another option.

In this assignment we'll take your project idea and see what shakes out of it. 

See the following document for full instructions.

Due 12/1.

Allowed Tools: Any. (I've tested this workflow on ChatGPT, Gemini, and Claude, so those should be fine. There are a number of models on Poe that will work also.)

CSC-113: Rapid Prototyping Your Mini-Project MVP
"From Idea to Reality in One Sprint"
Assignment Overview

Hello, Scholars! You've been exploring AI tools and professional workflows. Now it's time to put it all together: build something real that you can show to the world.

This assignment is about rapid prototyping - using AI assistance to go from idea to working demo fast. You'll create a Minimum Viable Product (MVP) that demonstrates at least one core feature of your mini-project idea. Or, if you're still exploring ideas, you'll build a simple web-based game or tool.

The Big Lesson: You don't need to understand every line of code to ship something valuable. You DO need to understand what you're building, test it thoroughly, and document your process.

What You'll Build

Option A: Your Mini-Project MVP

Pick ONE core feature from your project idea
Build a working demo that proves the concept
Document what you learned for the full project

Option B: Simple Web Game/Tool

Choose from suggested ideas (or propose your own)
Build a complete, playable experience
Practice the rapid prototyping workflow

Technical Stack: Single Page Application (JavaScript/HTML/CSS)

Why? Easy to deploy and share (no server needed!)
You can host it free on GitHub Pages
Perfect for portfolio demonstrations
Part 1: Product Requirements Document (1-2 hours)
What's a PRD?

A Product Requirements Document answers: "What are we building and why?" It's how professionals plan before coding.

Your Task

Create a PRD using AI assistance. Your PRD should include:

1. Project Overview

What does it do? (1-2 sentences)
Who is it for?
What problem does it solve?

2. Core Features (Pick 1-3 for MVP)

Feature name and description
Why this feature matters
Success criteria (how do you know it works?)

3. User Experience

What does the user see first?
What can they do?
What happens when they interact?

4. Technical Constraints

Single page application
Must work in web browser
No server-side code needed

5. Out of Scope (What you're NOT building yet)

List features you'd add later
Helps you stay focused
AI Assistance Strategy
Good Prompt:
"Help me create a Product Requirements Document for a [describe your idea]. 
I'm building an MVP as a single page web application. I need: overview, 
2-3 core features, basic user experience flow, and technical constraints."

Better Prompt:
"I'm a computer science student building an MVP for [your idea]. Help me 
create a PRD that includes: problem statement, target user, 3 must-have 
features for the MVP, user interaction flow, and what to exclude from v1. 
Format as a markdown document I can use to generate code later."

Deliverable: PRD.md

Save this in your project repository. You'll use it in Part 2.

GitHub Workflow Reminder:

Create Issue: "Create PRD for [project name]"
Create branch: 1-create-prd
Write and commit PRD
Create PR, link to issue
Get peer review before merging
Part 2: Rapid Prototyping Sprint (4-6 hours)
The Experiment

You'll use your PRD to generate code from multiple AI tools, then choose the best starting point. This teaches you:

How different AI models interpret requirements
How to evaluate AI-generated code
When to switch tools vs. iterate with one
Step 1: Generate Initial Prototypes (1 hour)

Use your PRD with at least 2 different AI tools:

Recommended Tools (all free):

Claude (claude.ai)
ChatGPT (chat.openai.com)
Google Gemini (gemini.google.com)
GitHub Copilot (if you have access)

The Prompt Template:

I need you to create a single-page web application based on this PRD:

[Paste your entire PRD here]

Requirements:
- Single HTML file with embedded CSS and JavaScript
- No external dependencies or libraries needed
- Works when opened directly in a browser
- Include clear comments explaining major sections

Please generate the complete code.

Step 2: Test and Compare (1 hour)

For each generated version:

Save it: prototype-v1-claude.html, prototype-v1-chatgpt.html, etc.
Test it: Open in browser, try all features
Document results: What works? What doesn't?

Create PROTOTYPE_TESTING.md:

## Version 1: Claude
- ✅ Works: [list what works]
- ❌ Broken: [list what's broken]
- 💭 Observations: [any interesting choices]

## Version 2: ChatGPT
- ✅ Works: [list what works]
- ❌ Broken: [list what's broken]
- 💭 Observations: [any interesting choices]

## Decision
I'm going with [tool name] because [reasoning]

Step 3: Iteration & Refinement (2-3 hours)

Now improve your chosen version:

The Iteration Pattern:

Test the code
Find what doesn't work or could be better
Craft a specific fix prompt
Test again
Repeat

Track Your Iterations in ITERATION_LOG.md:

## Iteration 1
**Problem**: [what wasn't working]
**Prompt**: [what you asked the AI]
**Result**: [what happened]
**Status**: ✅ Fixed / ❌ Still broken / 🤔 Partially working

## Iteration 2
...


Pro Tips:

Make ONE change at a time
Save versions: v1.html, v2.html, etc.
If you get stuck after 3 tries, try a different approach
It's okay to ask the AI: "This isn't working because [error]. How do I fix it?"
Step 4: Polish & Documentation (1 hour)

Make It Portfolio-Ready:

✅ Add clear title and instructions on the page
✅ Handle errors gracefully (what if user does something unexpected?)
✅ Make it look decent (doesn't have to be fancy!)
✅ Test in at least 2 browsers

Update Your README.md:

# [Project Name] MVP

## What It Does
[Brief description]

## How to Use
1. [Step 1]
2. [Step 2]
...

## Features Implemented
- [Feature 1]
- [Feature 2]

## Try It Yourself
[Link to GitHub Pages deployment]

## What I Learned
[Your reflection here]

## Future Improvements
[What you'd add next]

Part 3: Deployment to GitHub Pages (30 minutes)
Making It Live

GitHub Pages turns your repository into a website. Free. Instantly.

Steps:

Your main file should be named index.html
In your repository: Settings → Pages
Source: Deploy from branch main
Wait 1-2 minutes
Your site is live at: https://[your-username].github.io/[repo-name]

Test Your Live Site:

Does it work on your phone?
Can someone else use it?
Share the link in class Discord!
Submission Requirements

In Your GitHub Repository:

Required Files
✅ PRD.md - Your product requirements document
✅ index.html - Your working application
✅ PROTOTYPE_TESTING.md - Your AI tool comparison
✅ ITERATION_LOG.md - Your development journey
✅ README.md - Complete documentation
Required GitHub Workflow
✅ Issue for PRD creation
✅ Issue for implementation
✅ Issues for major iterations (optional but recommended)
✅ Pull requests with good descriptions
✅ At least one peer review
Demonstration
✅ Working live link (GitHub Pages URL)
✅ 2-3 minute video showing:
What your MVP does
You using it
One thing that was hard
One thing you're proud of
Assessment Rubric
Functionality (30 points)
Completeness (10 pts): Implements core features from PRD
Reliability (10 pts): Works consistently, handles errors
Usability (10 pts): Someone else can figure out how to use it
AI Collaboration (25 points)
PRD Quality (10 pts): Clear, specific, actionable requirements
Tool Comparison (5 pts): Genuinely tested multiple options
Iteration Strategy (10 pts): Shows refinement, not just first output
Process & Documentation (25 points)
Iteration Log (10 pts): Honest reflection on what worked/didn't
README (10 pts): Enables others to understand and use your work
GitHub Workflow (5 pts): Proper use of issues, branches, PRs
Professional Practice (20 points)
Deployment (10 pts): Successfully hosted and accessible
Portfolio Ready (5 pts): Something you'd show an employer
Reflection (5 pts): Demonstrates learning and growth
Project Ideas (If You're Stuck)
Productivity Tools
Pomodoro Timer: Work/break timer with task tracking
Daily Reflection Journal: Simple prompt-based journaling
Habit Tracker: Visual tracker for daily habits
Learning Tools
Flashcard Generator: Create and study flashcards
Quiz Maker: Build and take custom quizzes
Study Buddy: Explain-it-back-to-me practice tool
Creative Tools
Story Starter: Generate creative writing prompts
Color Palette Generator: Create and save color schemes
Random Decision Maker: Fun decision-making tool
Simple Games
Word Guessing Game: Like Wordle but your rules
Memory Match: Card matching game
Trivia Quiz: Topic-specific trivia with scoring
Number Challenge: Math puzzle generator
Utility Tools
Unit Converter: Convert between measurements
Password Generator: Create secure passwords
Budget Calculator: Simple expense tracking
Goal Tracker: Set and monitor progress on goals
Expected Challenges (And That's Good!)

You WILL experience:

"The AI Made Broken Code"

This is expected. AI tools are assistants, not magic. Learn to:

Read error messages in browser console (F12)
Test each feature individually
Ask the AI to fix specific problems
Know when to try a different approach
"I Don't Understand JavaScript"

That's okay! You're learning to:

Work with code as a "black box"
Test systematically
Read and modify (even if you can't write from scratch)
Recognize patterns
"It Doesn't Look Professional"

Start with working, then make it pretty.

Function > Form for MVP
"Good enough" is the goal
You can always improve v2
"I Hit a Wall"

Strategies when stuck:

Simplify: Remove features until it works
Switch: Try a different AI tool
Search: Someone else has solved this
Ask: Peers, instructor
Timeline & Milestones

(This timeline assumes no more than 30 minutes of work per day -- if you marathon it, at least do Week 1 and 2 in separate sessions.)

Week 1:

✅ Day 1-2: Create PRD, get it reviewed
✅ Day 3-4: Generate and test initial prototypes
✅ Day 5: Choose version and start iterating

Week 2:

✅ Day 1-3: Iteration and refinement
✅ Day 4: Polish and documentation
✅ Day 5: Deploy and create demo web page




Why This Matters

For Your Career:

Employers want to see you can ship working products
AI-assisted development is becoming industry standard
Documentation skills matter as much as coding skills
Portfolio-ready projects open doors

For Your Learning:

Rapid prototyping is a valuable skill
Learning to work WITH AI, not depend on it
Professional workflows become second nature
Confidence comes from completing projects

For Your Class:

Foundation for your final project
Practice before higher stakes
Build community by sharing and testing
Celebrate progress, not perfection
Final Thoughts

Remember: "Failure is just exercise."

You're going to:

Generate code that doesn't work
Iterate more times than you expect
Learn by doing, not by perfection
Build something you can point to

That's not just okay – that's the point.

By the end, you'll have:

A working application you built
A link you can share with anyone
Evidence of your process
Confidence for your next project

The hardest part is starting. You've got this.

Questions? Stuck? Confused? That's normal. That's growth. Let's figure it out together.

Hello, Scholars, and happy building! 🚀