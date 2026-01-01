sage-file-list.md

# SAGE Context Documents Inventory

## Complete List of Context Documents for CSC-113

**Purpose:** This inventory tracks all context documents that students will add to their SAGE instance throughout the semester. Each document serves dual purposes: making SAGE more capable AND teaching students how LLM context design works.

-----

## Document Release Schedule

|Week|Document |Priority |Status |
|----|---------------------------|---------------------|----------|
|1 |`SAGE-core.md` |Required |🔴 To Build|
|1 |`course-overview.md` |Required |🔴 To Build|
|2 |`github-basics.md` |Required |🔴 To Build|
|3 |`github-troubleshooting.md`|Required |🔴 To Build|
|4 |`prompt-engineering.md` |Required |🔴 To Build|
|4 |`ai-platforms.md` |Required |🔴 To Build|
|5 |`rate-limits-costs.md` |Required |🔴 To Build|
|6 |`debugging-guide.md` |Required |🔴 To Build|
|7 |`critical-evaluation.md` |Required |🔴 To Build|
|9 |`conversation-design.md` |Track: Prompt Masters|🔴 To Build|
|9 |`code-assistance.md` |Track: Code Builders |🔴 To Build|
|9 |`project-planning.md` |Required |🔴 To Build|
|13 |`portfolio-guide.md` |Required |🔴 To Build|
|14 |`presentation-prep.md` |Required |🔴 To Build|

-----

## Document Specifications

### Week 1: Foundation Documents

#### `SAGE-core.md`

**Purpose:** Establishes SAGE’s personality, interaction style, and self-awareness.

**What it teaches:** System prompting, persona design, interaction patterns

**Key content areas:**

- Who SAGE is and isn’t
- Communication style guidelines
- How to handle uncertainty
- Escalation patterns (when to say “ask your instructor”)
- Encouraging iteration and experimentation

**Design pattern demonstrated:** Persona definition with behavioral constraints

-----

#### `course-overview.md`

**Purpose:** Gives SAGE knowledge of CSC-113 structure, expectations, and goals.

**What it teaches:** Domain context injection, scoping knowledge boundaries

**Key content areas:**

- Course learning outcomes
- 16-week structure and phases
- Assignment types and expectations
- Grading philosophy (“failure is just exercise”)
- Key concepts by module

**Design pattern demonstrated:** Domain knowledge with temporal structure

-----

### Weeks 2-3: Workflow Documents

#### `github-basics.md`

**Purpose:** Enables SAGE to help with GitHub workflow questions.

**What it teaches:** Procedural knowledge encoding, step-by-step guidance

**Key content areas:**

- Core concepts: repos, Issues, branches, commits, PRs
- The CSC-113 workflow: Issue → Branch → Work → Commit → PR → Review → Merge
- Naming conventions
- When to create Issues vs just commit
- How to write good commit messages

**Design pattern demonstrated:** Procedural workflows with decision points

-----

#### `github-troubleshooting.md`

**Purpose:** Helps SAGE diagnose and fix common GitHub problems.

**What it teaches:** Error-solution pattern matching, diagnostic trees

**Key content areas:**

- “I can’t push to main” (that’s the point)
- “My branch has conflicts”
- “I accidentally committed to main”
- “My PR won’t merge”
- “I can’t find my branch”
- Recovery procedures for each

**Design pattern demonstrated:** Error → Diagnosis → Solution → Prevention structure

-----

### Weeks 4-6: AI Literacy Documents

#### `prompt-engineering.md`

**Purpose:** Makes SAGE a meta-tutor for prompting skills.

**What it teaches:** Self-referential knowledge (AI teaching about AI)

**Key content areas:**

- What makes prompts effective
- The role of context, examples, and constraints
- Iteration strategies
- Common prompting patterns
- How to evaluate prompt quality

**Design pattern demonstrated:** Meta-knowledge and self-improvement guidance

-----

#### `ai-platforms.md`

**Purpose:** Helps students understand tool differences and make informed choices.

**What it teaches:** Comparative knowledge structures

**Key content areas:**

- Claude vs Gemini: strengths and differences
- Projects/Gems vs AI Studio vs API
- When to use which tool
- Cost and rate limit considerations
- Platform-specific features

**Design pattern demonstrated:** Comparison matrices with use-case guidance

-----

#### `rate-limits-costs.md`

**Purpose:** Practical guidance on managing AI resource constraints.

**What it teaches:** Constraint-aware planning, resource optimization

**Key content areas:**

- Free tier limits (Claude, Gemini)
- How rate limits work
- Strategies to stay within limits
- When to upgrade vs optimize
- Caching and batching approaches

**Design pattern demonstrated:** Practical constraints with workaround strategies

-----

### Weeks 7-8: Problem-Solving Documents

#### `debugging-guide.md`

**Purpose:** Structured approach to debugging with AI assistance.

**What it teaches:** Process-oriented problem solving

**Key content areas:**

- How to describe problems clearly
- What information to include
- Rubber duck debugging with AI
- When AI debugging helps vs hurts
- Verifying AI suggestions

**Design pattern demonstrated:** Systematic process with checkpoints

-----

#### `critical-evaluation.md`

**Purpose:** Framework for assessing AI output quality.

**What it teaches:** Judgment criteria, healthy skepticism

**Key content areas:**

- Signs of AI hallucination
- How to verify claims
- When to trust vs double-check
- Common AI failure modes
- Building calibrated confidence

**Design pattern demonstrated:** Evaluation rubrics and decision frameworks

-----

### Weeks 9-12: Specialization Documents

#### `conversation-design.md` (Prompt Masters Track)

**Purpose:** Advanced techniques for designing AI conversations.

**What it teaches:** UX for AI interactions, conversation flow

**Key content areas:**

- Multi-turn conversation patterns
- Persona development
- Handling edge cases gracefully
- User experience considerations
- Testing conversation quality

**Design pattern demonstrated:** Interaction design with user journey mapping

-----

#### `code-assistance.md` (Code Builders Track)

**Purpose:** Optimizing SAGE for programming help.

**What it teaches:** Technical domain depth, structured outputs

**Key content areas:**

- Code review workflows
- Debugging assistance patterns
- Documentation generation
- Testing suggestions
- API usage examples

**Design pattern demonstrated:** Technical specification with code examples

-----

#### `project-planning.md` (Both Tracks)

**Purpose:** Project scoping and management support.

**What it teaches:** Project management context

**Key content areas:**

- Breaking down projects
- Milestone definition
- Time estimation
- Risk identification
- Scope management

**Design pattern demonstrated:** Planning frameworks with templates

-----

### Weeks 13-16: Integration Documents

#### `portfolio-guide.md`

**Purpose:** GitHub profile optimization for job readiness.

**What it teaches:** Self-presentation and professional communication

**Key content areas:**

- README best practices
- Pinned repository selection
- Contribution graph strategies
- Professional bio writing
- Project documentation standards

**Design pattern demonstrated:** Personal branding with concrete examples

-----

#### `presentation-prep.md`

**Purpose:** Demo and pitch preparation assistance.

**What it teaches:** Communication and presentation skills

**Key content areas:**

- Demo structure and flow
- Handling Q&A
- Technical presentation tips
- Storytelling for technical work
- Backup plans for tech failures

**Design pattern demonstrated:** Communication templates with contingency planning

-----

## Document Template

All SAGE context documents should follow this structure:

```markdown
# [Topic Name] - SAGE Context Document

## Purpose
Why SAGE needs this knowledge. What questions will students ask about this topic?

## Core Concepts
Key information organized for retrieval. Use headers and lists for scannability.

## Common Questions
Anticipated Q&A pairs. Format:
- **Q:** [Question students will ask]
- **A:** [How SAGE should respond]

## Procedures (if applicable)
Step-by-step processes. Number each step clearly.

## Troubleshooting (if applicable)
Error → Cause → Fix → Prevention patterns.

## What SAGE Should NOT Do
Boundaries and limitations. When to escalate to instructor.

## Connections
How this topic relates to other context documents.
```

-----

## Design Principles

When creating context documents, follow these guidelines:

### 1. Chunked Knowledge

- Break information into retrievable pieces
- Use clear headers and structure
- Avoid dense paragraphs

### 2. Action-Oriented

- Include what to DO, not just what to KNOW
- Provide specific steps
- Give examples

### 3. Error-Aware

- Anticipate confusion points
- Include troubleshooting
- Acknowledge common mistakes

### 4. Appropriately Bounded

- Define what SAGE should NOT answer
- Include escalation triggers
- Acknowledge uncertainty

### 5. Cross-Referenced

- Note connections to other documents
- Build conceptual web
- Support progressive learning

-----

## Student-Created Documents

Starting Week 5, students create their own context documents. Examples:

- Study guides for other courses
- Personal productivity workflows
- Hobby/interest knowledge bases
- Work-related domain knowledge

**Assessment criteria for student documents:**

- Clear purpose statement
- Well-structured content
- Effective Q&A patterns
- Appropriate boundaries
- Demonstrated improvement in SAGE responses

-----

## Version Control

All context documents should be:

- Stored in student’s SAGE repository
- Version controlled with meaningful commits
- Updated as understanding grows
- Documented with revision notes

This creates an audit trail of the student’s growing understanding of context design.

-----

*This inventory will be updated as documents are developed. Check status column for current availability.*