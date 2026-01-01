sage_assignment1.md

# Assignment 1: Meet Your SAGE

## Setting Up Your AI Study Assistant

**Course:** CSC-113 AI Fundamentals
**Due:** End of Week 1
**Points:** 20 (Setup: 10, Interaction: 10)

-----

## Overview

This week, you’ll set up SAGE—your Scholar’s Adaptive Growth Engine. SAGE is a personal AI assistant that will help you throughout this course and beyond. Unlike generic AI chatbots, SAGE will know about our course, our assignments, and our way of doing things.

By the end of this assignment, you will have:

- A working SAGE instance (using Claude or Gemini)
- Added two context documents that give SAGE course-specific knowledge
- Had your first real conversation with SAGE about what we’re building

-----

## Part 1: Choose Your Platform (Days 1-2)

You’ll use either **Claude Projects** or **Gemini Gems**. Both work well—pick based on your preference.

### Option A: Claude Projects

1. Go to [claude.ai](https://claude.ai)
1. Create a free account (or sign in if you have one)
1. Look for “Projects” in the left sidebar
1. Click “Create Project”
1. Name it: **SAGE-CSC113**
1. Add a description: “My AI study assistant for CSC-113 AI Fundamentals”

**Note:** Free Claude accounts have limited messages per day. This is fine for learning—we’ll discuss managing rate limits in Week 5.

### Option B: Gemini Gems

1. Go to [gemini.google.com](https://gemini.google.com)
1. Sign in with your Google account
1. Look for “Gem manager” in the left sidebar (or under the menu)
1. Click “New Gem”
1. Name it: **SAGE-CSC113**
1. Add instructions: “You are SAGE, my study assistant for CSC-113 AI Fundamentals”

**Note:** Gemini free tier has generous limits but may vary. We’ll cover this in detail later.

### Verification

Take a screenshot showing your empty SAGE project/gem created. You’ll submit this with Part 3.

-----

## Part 2: Add Context Documents (Days 3-4)

Now we’ll give SAGE knowledge about who it is and what our course covers.

### Day 3: Add SAGE-core.md

Download `SAGE-core.md` from the course materials.

**For Claude Projects:**

1. Open your SAGE-CSC113 project
1. Look for “Project knowledge” or the ability to add files
1. Upload or paste the contents of `SAGE-core.md`

**For Gemini Gems:**

1. Open your SAGE-CSC113 gem for editing
1. In the “Instructions” section, paste the contents of `SAGE-core.md`
1. Save your gem

### Day 4: Add course-overview.md

Download `course-overview.md` from the course materials.

Add it the same way you added the first document.

### Verification

Your SAGE now has two context documents. Take a screenshot showing both documents are loaded.

-----

## Part 3: First Conversation (Day 5)

Now let’s see what SAGE can do.

### Have This Conversation

Start a new chat with your SAGE and ask these questions (copy them exactly):

1. “Hey SAGE, what are you and how can you help me?”
1. “What’s the main project I’ll be building in this course?”
1. “I’m nervous about using GitHub. What should I know?”
1. “What happens if I break something in this class?”

### What to Notice

As you chat, pay attention to:

- Does SAGE know about our specific course?
- Does SAGE mention things from the documents you added?
- How is this different from asking a generic AI chatbot?

-----

## What to Submit

Create a document (Word, Google Doc, or Markdown) containing:

### 1. Setup Confirmation (5 points)

- Screenshot of your SAGE project/gem
- Which platform you chose and why (1-2 sentences)

### 2. Context Verification (5 points)

- Screenshot showing both documents are loaded
- Confirm: Did you read through the documents before adding them? What stood out?

### 3. Conversation Log (5 points)

- Copy/paste your full conversation with SAGE
- Include all four questions and SAGE’s responses

### 4. Reflection (5 points)

Answer these questions in 2-3 sentences each:

- What did SAGE know that a generic AI wouldn’t?
- What’s one thing SAGE said that was specifically about our course?
- What do you think would happen if we added more documents?

-----

## Grading Rubric

|Component |Points|Criteria |
|-----------------|------|--------------------------------------------|
|Platform Setup |5 |SAGE project/gem created with correct name |
|Context Documents|5 |Both documents successfully added |
|Conversation |5 |All four questions asked, responses included|
|Reflection |5 |Thoughtful answers showing understanding |

-----

## Common Issues

### “I can’t find Projects/Gems”

- For Claude: Make sure you’re on claude.ai (not the API). Projects is in the sidebar.
- For Gemini: Gems might be under a menu icon. Look for “Gem manager.”

### “I ran out of messages”

- Both free tiers have limits. Space out your work across days, or switch to the other platform.
- We’ll cover managing rate limits in detail in Week 5.

### “SAGE isn’t answering like the documents say”

- Make sure you added the full document content, not just the filename
- Try starting a new conversation (old conversations don’t see new documents)

### “The interface looks different than described”

- These platforms update frequently. The core concept (add documents to give AI context) works the same even if buttons move.
- Ask in class if you’re stuck.

-----

## Why We’re Doing This

Right now, this might feel like “just setting up a chatbot.” But something important just happened:

**You taught an AI new knowledge by adding a document.**

SAGE didn’t know anything about CSC-113 until you gave it `course-overview.md`. Now it does. You changed what the AI knows.

Over the next 15 weeks, you’ll add more documents. Each one will make SAGE smarter about a specific topic. By the end, you’ll understand exactly how this works—well enough to create AI assistants for any subject you want.

This is the beginning of understanding AI from the inside.

-----

## Looking Ahead

Next week, we’ll add `github-basics.md` to SAGE. Then you’ll have an AI assistant that can actually help you with the GitHub workflow we’re learning.

Notice the pattern: **learn something → teach it to SAGE → SAGE helps you practice it.**

That’s the SAGE loop. Get comfortable with it—we’ll use it all semester.

-----

*Questions? Post in the course discussion forum. Or ask your SAGE—though it might not know the answer yet!*