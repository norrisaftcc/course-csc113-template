sage-course-outline.md

```NOTE: this will need to be reconciled with the other course outlines to create a definitive course outline.

constraints: 
8 modules, 16 weeks, assignments should be labeled by MODULE not by week (as they have a 2 week window for these modules)

when multiple options are offered, consider whether to merge them, or pick the best version.

double check the final outline for coherency and ensure the dates make sense (e.g. not asking students to do 4 weeks of work in 2)

As an example of module size, SAGE might be 
its own module (m1? m2?) probably before bad bot, and one setup assignment and one use of SAGE assignment seems reasonable for that two week window.```

# CSC-113 AI Fundamentals: SAGE-Integrated Course Outline

## “Scholar’s Adaptive Growth Engine” - Progressive AI Assistant Development

**Document Version:** 1.0
**Purpose:** 16-week course structure with SAGE phases and context document progression

-----

## Course Philosophy

Students build SAGE (their personal AI study assistant) throughout the semester using a **USE → MODIFY → CREATE** progression:

|Phase |Weeks|Platform |Student Action |
|----------------------|-----|-----------------------------|-------------------------------------------|
|**Phase 1: Configure**|1-4 |Claude Projects / Gemini Gems|Set up and use pre-built context |
|**Phase 2: Expand** |5-8 |Same + AI Studio exploration |Add context documents, understand prompting|
|**Phase 3: Customize**|9-12 |AI Studio focus |Design own prompts and context strategies |
|**Phase 4: Build** |13-16|Streamlit/Gradio |Create deployable application |

**Key Insight:** Each context document added to SAGE teaches students how LLM context works. By semester end, they can replicate this for any domain (biology course, work project, etc.).

-----

## SAGE Context Document Inventory

Documents are added progressively. Each serves two purposes:

1. **Functional** - Makes SAGE more helpful for that topic
1. **Educational** - Demonstrates context design patterns

### Foundation Documents (Weeks 1-2)

|Document |Purpose |Pattern Demonstrated |
|--------------------|-----------------------------------|--------------------------------|
|`SAGE-core.md` |Base personality, interaction style|System prompting, persona design|
|`course-overview.md`|CSC-113 structure, expectations |Domain context injection |

### Workflow Documents (Weeks 3-4)

|Document |Purpose |Pattern Demonstrated |
|---------------------------|------------------------------|-----------------------------|
|`github-basics.md` |Issues, branches, commits, PRs|Procedural knowledge encoding|
|`github-troubleshooting.md`|Common errors and fixes |Q&A pattern, error handling |

### AI Literacy Documents (Weeks 5-6)

|Document |Purpose |Pattern Demonstrated |
|-----------------------|---------------------------------|------------------------------------|
|`prompt-engineering.md`|Prompting techniques and patterns|Meta-knowledge (AI helping learn AI)|
|`ai-platforms.md` |Claude vs Gemini vs others |Comparative knowledge structure |
|`rate-limits-costs.md` |Managing API constraints |Practical constraints documentation |

### Problem-Solving Documents (Weeks 7-8)

|Document |Purpose |Pattern Demonstrated |
|------------------------|-------------------------------|--------------------------|
|`debugging-guide.md` |How to debug with AI assistance|Process-oriented context |
|`critical-evaluation.md`|Assessing AI outputs |Judgment criteria encoding|

### Specialization Documents (Weeks 9-12)

|Document |Purpose |Pattern Demonstrated |
|------------------------|--------------------------------------|--------------------------|
|`code-assistance.md` |Python help, API usage (Code Builders)|Technical domain depth |
|`conversation-design.md`|Dialog flows, UX (Prompt Masters) |Creative domain depth |
|`project-planning.md` |Scoping, requirements, milestones |Project management context|

### Integration Documents (Weeks 13-16)

|Document |Purpose |Pattern Demonstrated |
|----------------------|---------------------------|-------------------------|
|`portfolio-guide.md` |GitHub profile optimization|Self-presentation context|
|`presentation-prep.md`|Demo and pitch assistance |Communication context |

-----

## Week-by-Week Outline

### PHASE 1: CONFIGURE (Weeks 1-4)

-----

#### Week 1: Foundation Setup

**Theme:** “Hello, Scholars! Let’s set up your AI study partner.”

**SAGE Activities:**

- [ ] Day 1: Account setup (Claude or Gemini - student choice)
- [ ] Day 2: Create Project/Gem named “SAGE-CSC113”
- [ ] Day 3: Add `SAGE-core.md` to context
- [ ] Day 4: Add `course-overview.md` to context
- [ ] Day 5: First real conversation - “Help me understand what we’re building”

**GitHub Activities:**

- [ ] Create GitHub account
- [ ] Join course organization
- [ ] Create first repository
- [ ] Complete Issue → Branch → PR → Merge cycle

**Context Documents Introduced:**

1. `SAGE-core.md` - Base personality and interaction patterns
1. `course-overview.md` - What CSC-113 covers, weekly structure

**Learning Outcomes:**

- Students have working SAGE instance providing immediate value
- Students understand “context = knowledge the AI can use”
- GitHub workflow muscle memory begins

**Transparency Moment:** “Notice how SAGE knew about our course structure? That’s because we gave it the course-overview document. This is how you teach an AI about any topic.”

-----

#### Week 2: GitHub Workflow Mastery

**Theme:** “SAGE learns GitHub so it can help you with GitHub”

**SAGE Activities:**

- [ ] Add `github-basics.md` to SAGE context
- [ ] Practice: Ask SAGE to explain a concept, then do it
- [ ] Practice: Ask SAGE to review your commit message before committing
- [ ] Reflection: What questions does SAGE answer well? Poorly?

**GitHub Activities:**

- [ ] Create 3+ Issues for planned work
- [ ] Branch naming conventions practice
- [ ] PR descriptions and linking to Issues
- [ ] First peer review

**Context Documents Introduced:**
3. `github-basics.md` - Core GitHub concepts and workflows

**Learning Outcomes:**

- SAGE becomes useful for GitHub questions
- Students see direct correlation: add document → SAGE gets smarter
- Workflow becoming automatic

**Transparency Moment:** “You just taught your AI a new skill by adding one document. What else could you teach it?”

-----

#### Week 3: AI Assistants Deep Dive

**Theme:** “Understanding the tools you’re using”

**SAGE Activities:**

- [ ] Add `github-troubleshooting.md` for error help
- [ ] Compare: Ask same question to SAGE vs raw Claude/Gemini
- [ ] Document: What makes SAGE’s answers better?
- [ ] Experiment: What happens if you remove a context document?

**GitHub Activities:**

- [ ] “Kevin Jr.” assistant development begins
- [ ] Document AI interactions in Issues
- [ ] PR with prompt iterations shown

**Context Documents Introduced:**
4. `github-troubleshooting.md` - Common errors and solutions

**Learning Outcomes:**

- Students understand context window impact
- Students can articulate why their SAGE works better than generic AI
- First debugging with AI assistance

**Transparency Moment:** “The troubleshooting doc uses a specific pattern: Error → Cause → Fix → Prevention. This structure helps the AI give actionable answers.”

-----

#### Week 4: Prompt Engineering Foundations

**Theme:** “The documents ARE the prompts”

**SAGE Activities:**

- [ ] Add `prompt-engineering.md` to context
- [ ] Add `ai-platforms.md` to context
- [ ] Meta-exercise: Ask SAGE how to write better prompts
- [ ] Revise one context document based on what you learned

**GitHub Activities:**

- [ ] Complete Kevin Jr. assistant
- [ ] Peer review with constructive feedback
- [ ] Retrospective: What worked, what didn’t

**Context Documents Introduced:**
5. `prompt-engineering.md` - Techniques for effective prompting
6. `ai-platforms.md` - Platform comparison and selection

**Learning Outcomes:**

- Students understand system prompts vs user prompts vs context
- Students can modify existing context documents
- First “aha” moment about how LLMs actually work

**Transparency Moment:** “You now have 6 documents in your SAGE. Each one is teaching the AI something specific. You’re not just using AI - you’re designing AI behavior.”

-----

### PHASE 2: EXPAND (Weeks 5-8)

-----

#### Week 5: Context Design Principles

**Theme:** “From user to designer”

**SAGE Activities:**

- [ ] Add `rate-limits-costs.md` to context
- [ ] Assignment: Write your own context document for a topic SAGE doesn’t know
- [ ] Test your document: Does SAGE answer better now?
- [ ] Peer review: Trade context documents with classmate

**GitHub Activities:**

- [ ] Track context document development in Issues
- [ ] PR your new context document to personal repo
- [ ] Review classmate’s context document

**Context Documents Introduced:**
7. `rate-limits-costs.md` - API economics and management
8. [Student-created document] - First original context

**Learning Outcomes:**

- Students can create effective context documents from scratch
- Students understand what makes context “good”
- Transferable skill: they could do this for any domain

**Milestone:** “You could now add your biology textbook chapters to a SAGE fork and have a biology study assistant.”

-----

#### Week 6: AI Studio Exploration

**Theme:** “Seeing behind the curtain”

**SAGE Activities:**

- [ ] Google AI Studio walkthrough
- [ ] Replicate SAGE behavior using explicit system prompts
- [ ] Compare: Same question in Projects/Gems vs AI Studio
- [ ] Experiment with temperature, token limits, etc.

**GitHub Activities:**

- [ ] Document AI Studio experiments
- [ ] Create comparison report

**Context Documents Introduced:**
9. `debugging-guide.md` - Systematic debugging with AI

**Learning Outcomes:**

- Students understand the abstraction layers (Gems/Projects → AI Studio → API)
- Students can articulate trade-offs between convenience and control
- Foundation for later API work

**Transparency Moment:** “Claude Projects is doing this configuration for you automatically. Now you see exactly what’s happening.”

-----

#### Week 7: Problem-Solving Integration

**Theme:** “SAGE as thought partner”

**SAGE Activities:**

- [ ] Add `critical-evaluation.md` to context
- [ ] Real problem: Use SAGE to help debug actual code/workflow issue
- [ ] Document the entire problem-solving conversation
- [ ] Evaluate: When did SAGE help? When did it mislead?

**GitHub Activities:**

- [ ] SAGE Foundation project begins (basic study assistant)
- [ ] Issues track feature development
- [ ] PRs show iterative progress

**Context Documents Introduced:**
10. `critical-evaluation.md` - How to assess AI outputs

**Learning Outcomes:**

- Students can use AI effectively for real problems
- Students know when to trust and when to verify
- Project planning skills developing

**Project 1 Specification Available:** SAGE Foundation (C-grade milestone)

-----

#### Week 8: First Integration Milestone

**Theme:** “Your SAGE is now sophisticated”

**SAGE Activities:**

- [ ] Audit: Review all context documents, revise weak ones
- [ ] Test: Can SAGE help with actual coursework from another class?
- [ ] Document: What would you add next?

**GitHub Activities:**

- [ ] Complete SAGE Foundation project
- [ ] Portfolio checkpoint: Is your GitHub telling a good story?
- [ ] Peer presentation: Show your SAGE to classmate

**Assessment Checkpoint:**

- SAGE has 10+ context documents
- Student can explain why each document exists
- Student has created at least one original context document
- SAGE Foundation project complete

**Milestone:** “Halfway point. You’ve gone from AI user to AI designer. Phase 3 is about customization and specialization.”

-----

### PHASE 3: CUSTOMIZE (Weeks 9-12)

-----

#### Week 9: Track Divergence

**Theme:** “Choose your path”

**SAGE Activities - Prompt Masters:**

- [ ] Add `conversation-design.md` to context
- [ ] Focus: Making SAGE more conversational, nuanced
- [ ] Explore: Custom GPT creation, advanced Gems features

**SAGE Activities - Code Builders:**

- [ ] Add `code-assistance.md` to context
- [ ] Focus: Making SAGE help with code review, debugging
- [ ] Explore: API calls, structured outputs

**Both Tracks:**

- [ ] Add `project-planning.md` to context

**Context Documents Introduced:**
11. `conversation-design.md` OR `code-assistance.md` (track-specific)
12. `project-planning.md` (both tracks)

-----

#### Week 10: Deep Specialization

**Theme:** “Expertise development”

**SAGE Activities - Prompt Masters:**

- [ ] Design multi-turn conversation flows
- [ ] Create specialized personas within SAGE
- [ ] Build prompt library for specific use cases

**SAGE Activities - Code Builders:**

- [ ] Implement function calling / tool use
- [ ] Build code generation templates
- [ ] Create testing assistance workflows

**GitHub Activities:**

- [ ] Track-specific exercises in PRs
- [ ] Cross-track peer review (Prompt Master reviews Code Builder and vice versa)

-----

#### Week 11: Application Architecture

**Theme:** “From chat to application”

**Instructor Demo:** Streamlit/Gradio reference implementation

**SAGE Activities:**

- [ ] Review instructor’s implementation
- [ ] Map: How do my context documents translate to this architecture?
- [ ] Plan: What would my version look like?

**GitHub Activities:**

- [ ] SAGE Enhancement project begins (B-grade milestone)
- [ ] Architecture decision records in Issues
- [ ] Feature branches for each enhancement

**Project 2 Specification Available:** SAGE Enhancement

-----

#### Week 12: Build Sprint

**Theme:** “Implementation week”

**SAGE Activities:**

- [ ] Build your Streamlit/Gradio version
- [ ] Port context documents to application format
- [ ] Test with classmates

**GitHub Activities:**

- [ ] Rapid iteration with daily commits
- [ ] PR reviews for code quality
- [ ] Documentation updates

**Assessment Checkpoint:**

- Working application (can be simple)
- Clear documentation of design decisions
- Demonstrates context management understanding

-----

### PHASE 4: BUILD (Weeks 13-16)

-----

#### Week 13: Community Partner Kickoff

**Theme:** “Real stakeholders, real problems”

**SAGE Activities:**

- [ ] Add `portfolio-guide.md` to context
- [ ] Use SAGE to help with requirements gathering
- [ ] Use SAGE to help scope partner project

**Partner Activities:**

- [ ] Initial stakeholder meeting
- [ ] Requirements documentation
- [ ] Scope agreement

**Context Documents Introduced:**
13. `portfolio-guide.md` - GitHub profile optimization

-----

#### Week 14: Partner Project Development

**Theme:** “Building for someone else”

**SAGE Activities:**

- [ ] Add `presentation-prep.md` to context
- [ ] Use SAGE for project planning and problem-solving
- [ ] Document how SAGE helped (and didn’t)

**Context Documents Introduced:**
14. `presentation-prep.md` - Demo and pitch preparation

**GitHub Activities:**

- [ ] Partner project in dedicated repository
- [ ] Regular commits showing progress
- [ ] Mid-project review with partner

-----

#### Week 15: Polish and Preparation

**Theme:** “Getting ready to ship”

**SAGE Activities:**

- [ ] Final context audit: What would make SAGE even better?
- [ ] Portfolio review: Use SAGE to critique your GitHub profile
- [ ] Presentation practice: Use SAGE to rehearse

**GitHub Activities:**

- [ ] Portfolio finalization
- [ ] Project documentation complete
- [ ] Presentation materials ready

-----

#### Week 16: Capstone Presentations

**Theme:** “Show what you built, explain how you think”

**Presentation Components:**

1. Partner project demo (working software)
1. SAGE walkthrough (your AI assistant)
1. Context design explanation (how you taught the AI)
1. Portfolio tour (your GitHub story)
1. Reflection (what you learned)

**Assessment:**

- Technical implementation quality
- Context design sophistication
- Ability to explain AI behavior
- Professional communication
- Portfolio completeness

-----

## Context Document Specifications

### Document Template

```markdown
# [Topic Name] - SAGE Context Document

## Purpose
[Why SAGE needs this knowledge]

## Core Concepts
[Key information, organized for retrieval]

## Common Questions
[Q&A pairs for frequent queries]

## Procedures
[Step-by-step processes if applicable]

## Troubleshooting
[Error → Cause → Fix patterns if applicable]

## Connections
[How this relates to other context documents]
```

### Design Principles for Context Documents

1. **Chunked Knowledge** - Break into retrievable pieces
1. **Action-Oriented** - Include what to DO, not just what to KNOW
1. **Error-Aware** - Anticipate confusion points
1. **Cross-Referenced** - Link to related documents
1. **Evolving** - Designed for revision as understanding grows

-----

## Assessment Integration

### How SAGE Work Maps to Grades

|Grade|SAGE Sophistication |Context Documents |Application |
|-----|------------------------------|-----------------------|--------------------------------|
|**A**|Can design new context systems|14+ docs, 2+ original |Deployable app + partner project|
|**B**|Can create effective context |12+ docs, 1+ original |Working app with enhancements |
|**C**|Can use and modify context |10+ docs, modifications|Basic SAGE Foundation complete |
|**D**|Basic usage only |Provided docs only |Incomplete implementation |

### Portfolio Evidence

Students demonstrate SAGE mastery through:

- Context document collection in repository
- Commit history showing iterative improvement
- Documentation explaining design decisions
- Working application (Phase 4)
- Reflection on AI collaboration process

-----

## Transferability Checkpoint

**By Week 8, students should be able to:**

- [ ] Create a new Claude Project or Gemini Gem from scratch
- [ ] Write effective context documents for any domain
- [ ] Explain why context improves AI responses
- [ ] Evaluate AI output quality critically

**By Week 16, students should be able to:**

- [ ] Design complete context systems for new domains
- [ ] Build simple AI-powered applications
- [ ] Articulate how LLMs use context
- [ ] Apply these skills to future courses and jobs

-----

## Next Development Steps

1. [ ] Write `SAGE-core.md` - Base personality document
1. [ ] Write `course-overview.md` - CSC-113 context
1. [ ] Create Claude Projects setup tutorial (video script)
1. [ ] Create Gemini Gems setup tutorial (video script)
1. [ ] Develop remaining context documents per schedule
1. [ ] Build instructor reference Streamlit/Gradio app
1. [ ] Create student-facing project specifications

-----

*This outline integrates SAGE throughout the curriculum, making context design a visible, learnable skill rather than hidden magic.*
