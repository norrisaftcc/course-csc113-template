sage-teachers-guide.md

# Teacher’s Guide to SAGE

## What It Is, Why We’re Doing It, and How It Works

-----

## The One-Paragraph Summary

SAGE (Scholar’s Adaptive Growth Engine) is a personal AI study assistant that students build progressively throughout CSC-113. They start by using pre-configured AI tools (Claude Projects or Gemini Gems), then gradually add “context documents” that teach the AI new knowledge. By adding these documents and watching SAGE improve, students learn how AI systems actually work—not through lectures, but through direct experience. By semester’s end, they understand AI well enough to create assistants for any domain.

-----

## Why SAGE Exists

### The Problem We’re Solving

Traditional AI courses face a dilemma:

- **Theory-first approaches** bore students before they see value
- **Tool-first approaches** create users who can’t adapt when tools change
- **Code-first approaches** lose non-programmers before they start

Students need to understand AI deeply enough to:

1. Use it effectively today
1. Adapt as tools evolve tomorrow
1. Know when to trust it and when to verify

### The SAGE Solution

SAGE threads the needle by making students **AI designers from Day 1**, even before they write code:

|Week|What Students Do |What They Learn |
|----|-----------------------------------|-----------------------------------|
|1 |Set up Claude Project or Gemini Gem|AI tools exist and are configurable|
|2 |Add a document, watch SAGE improve |Context shapes AI behavior |
|5 |Write their own document |Knowledge can be encoded for AI |
|8 |Apply to another class |These skills transfer anywhere |
|12 |Build custom application |The magic becomes engineering |

The genius is that students **use SAGE to learn the course** while **building SAGE teaches them AI**. It’s recursive in the best way.

-----

## How SAGE Works (Non-Technical Version)

### The Core Mechanism

Both Claude Projects and Gemini Gems allow you to add documents that the AI can reference. When students add a document about GitHub, SAGE can suddenly answer GitHub questions well. When they add a document about prompt engineering, SAGE can help them write better prompts.

**Students observe this cause-and-effect directly:**

- Before document: SAGE gives generic answers
- After document: SAGE gives course-specific, actionable answers

This visibility is the teaching tool. They’re not told that “context matters”—they experience it.

### The Progressive Reveal

We control the pacing by releasing context documents weekly:

**Weeks 1-4 (Configure):** Students add instructor-provided documents. They see SAGE improve but don’t fully understand why.

**Weeks 5-8 (Expand):** Students start writing their own documents. Now they understand the mechanism.

**Weeks 9-12 (Customize):** Students specialize SAGE for their track. They’re designing AI behavior.

**Weeks 13-16 (Build):** Students build actual applications. The mystery becomes engineering.

-----

## What This Means for Your Teaching

### You’re Not Teaching “AI Tools”

You’re teaching **AI literacy**—the understanding of how AI systems work that will remain relevant regardless of which tools exist in five years.

Students who complete this course will:

- Understand that AI behavior comes from training and context
- Know how to shape AI responses through good prompting and context design
- Recognize the limits of AI and when human judgment is needed
- Be able to create AI assistants for any domain they encounter

### Your Role Changes

|Traditional Role |SAGE-Based Role |
|-------------------------|------------------------------------|
|Explain how AI works |Point to evidence in their SAGE |
|Assign practice exercises|Assign context documents to add |
|Grade outputs |Assess context design quality |
|Troubleshoot tool issues |Ask “what does your SAGE say?” first|

You become a guide helping students interpret their own experiments rather than a lecturer transmitting knowledge.

### The Transparency Moments

Throughout the course, pause to make the invisible visible:

- **Week 1:** “Notice how SAGE knew about our course? That’s because we gave it the course-overview document.”
- **Week 3:** “Why does your SAGE answer GitHub questions better now? What changed?”
- **Week 5:** “You just taught your AI a new skill. You could do this for any subject.”
- **Week 8:** “Could you add your biology textbook chapters to a copy of SAGE? What would happen?”

These moments connect experience to principle.

-----

## Common Instructor Concerns

### “What if students just use SAGE to cheat?”

SAGE is designed to **help them learn the course**, so using it IS the assignment. The assessment isn’t “did you figure this out without help”—it’s “can you demonstrate understanding and create effective context?”

Students who rely entirely on SAGE without developing understanding will struggle to:

- Write effective context documents (Week 5+)
- Explain their SAGE’s behavior (assessment component)
- Adapt when SAGE gives incomplete answers

### “What if they use ChatGPT instead?”

That’s fine for general queries, but their SAGE (with course-specific context) will outperform generic ChatGPT for course-related questions. Students discover this empirically:

> “I asked ChatGPT about our branching strategy and got generic advice. I asked my SAGE and it knew exactly how we do Issue → Branch → PR in this class.”

This teaches tool selection through experience.

### “What if Claude/Gemini changes their interface?”

The underlying principle—that context documents shape AI behavior—is platform-independent. If we need to migrate to a new platform, students who understand the principle can adapt. Those who only learned button-clicking would struggle either way.

### “I don’t really understand how AI works myself.”

You don’t need to. Your job is to:

1. Release context documents on schedule
1. Point students toward their own SAGE when they have questions
1. Help them interpret what they observe
1. Assess their context design quality

The documents do the technical heavy lifting. You provide the pedagogical framing.

-----

## Practical Setup (What You Actually Do)

### Before Semester

1. **Create course accounts** (if sharing) or instructions for individual accounts
1. **Review the context documents** as they’re developed
1. **Test SAGE yourself** with student-type questions
1. **Prepare video tutorials** for Claude Projects and Gemini Gems setup

### Week 1

1. **Day 1:** Explain SAGE concept, assign account setup
1. **Day 2:** Guide Project/Gem creation (use tutorial video)
1. **Day 3:** Distribute `SAGE-core.md`, have them add it
1. **Day 4:** Distribute `course-overview.md`, have them add it
1. **Day 5:** First interaction exercise, discuss what they notice

### Weekly Thereafter

1. **Release new context document** according to schedule
1. **Have students add it** to their SAGE
1. **Assign interaction exercise** that uses new capability
1. **Discuss observations** during class

### Assessment Checkpoints

- **Week 4:** Can they explain why SAGE answers course questions well?
- **Week 8:** Can they write an effective original context document?
- **Week 12:** Can they design context for a new domain?
- **Week 16:** Can they explain their SAGE’s architecture to a partner?

-----

## How SAGE Connects to GitHub Workflow

SAGE and GitHub reinforce each other:

|SAGE Activity |GitHub Activity |
|-------------------------|-------------------|
|Store context documents |In SAGE repository |
|Track document iterations|Via commits |
|Collaborate on documents |Via PRs and reviews|
|Document SAGE development|In Issues |

Students practice professional workflow while building their AI assistant. Neither is an add-on—they’re integrated.

-----

## The Bigger Picture

By the end of CSC-113, your students will have:

1. **A working AI assistant** customized to their needs
1. **Transferable skills** they can apply to any domain
1. **Genuine understanding** of how AI context works
1. **A GitHub portfolio** demonstrating professional workflow
1. **Critical thinking habits** about AI capabilities and limits

Most importantly, they’ll approach new AI tools with confidence rather than confusion. They’ll ask “how do I give this context?” instead of “why isn’t this working?”

That’s AI literacy. SAGE is how we build it.

-----

## Quick Reference

### SAGE Phases

1. **Configure** (Weeks 1-4): Use pre-built context
1. **Expand** (Weeks 5-8): Add documents, understand mechanism
1. **Customize** (Weeks 9-12): Design own context strategies
1. **Build** (Weeks 13-16): Create deployable applications

### Platforms Supported

- **Claude Projects** (Anthropic) - claude.ai with Projects feature
- **Gemini Gems** (Google) - gemini.google.com with Gems feature
- **Google AI Studio** - Later in semester for more control
- **Streamlit/Gradio** - Final phase application building

### Key Principle

Every context document added to SAGE:

- Makes SAGE more capable (functional value)
- Teaches students how AI context works (educational value)

This dual purpose is the core of the SAGE approach.

-----

*Questions about SAGE implementation? The Instructor Operations Manual has detailed daily/weekly guidance.*