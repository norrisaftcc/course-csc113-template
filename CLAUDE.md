# CLAUDE.md - Instructions for Claude Code Instances
## CSC-113 AI Fundamentals Course Template Development

**Repository Purpose**: This is the master template repository for CSC-113 AI Fundamentals course materials. Multiple Claude Code instances will collaborate on developing assignments, guides, and supporting materials while maintaining consistency in pedagogical approach and quality standards.

---

## 🎯 WORKING IN THIS REPOSITORY

### Your Role
You are a Claude Code instance tasked with developing course materials for CSC-113 AI Fundamentals. Your work will be:
- Assigned via GitHub Issues
- Developed in feature branches
- Submitted as Pull Requests for review
- Merged after approval

### Core Directive
**Maintain the established pedagogical philosophy while creating clear, actionable, student-friendly materials.**

---

## 📁 REPOSITORY STRUCTURE

```
course-csc113-template/
├── CLAUDE.md                    # This file - your instructions
├── README.md                    # Repository overview
├── artifacts/                   # Legacy/reference materials
│   ├── overview/               # Course overview documents
│   └── deprecated/             # Old versions (reference only)
├── assignments/                # Student-facing assignments
│   ├── week-01-hello-github.md
│   ├── week-02-meet-kevin-sage.md
│   ├── week-03-ai-timeline.md
│   ├── week-04-bad-bot.md
│   ├── week-05-good-bot.md
│   ├── week-06-holiday-shopping.md      # NEEDS CREATION
│   ├── week-07-project-ideation.md
│   ├── week-08-track-specialization.md  # NEEDS EXPANSION
│   ├── week-09-community-kickoff.md     # NEEDS CREATION
│   └── week-10-project-planning.md      # NEEDS CREATION
├── guides/                     # Student support materials
│   ├── github-survival-guide.md         # NEEDS CREATION
│   ├── ai-tools-getting-started.md      # NEEDS CREATION
│   └── troubleshooting-faq.md           # NEEDS CREATION
├── instructor/                 # Instructor-facing materials
│   ├── operations-manual.md             # EXISTS (reference)
│   ├── assessment-rubrics.md            # NEEDS CREATION
│   └── example-submissions/             # NEEDS CREATION
├── templates/                  # Reusable templates
│   ├── assignment-template.md           # NEEDS CREATION
│   ├── reflection-template.md           # EXISTS (reference)
│   └── pr-template.md                   # NEEDS CREATION
└── outline/                    # Course structure
    └── complete-16week-outline.md       # EXISTS
```

---

## 🎓 PEDAGOGICAL PHILOSOPHY (CRITICAL - READ FIRST)

### Core Principles

**1. "Failure is Just Exercise"**
- Mistakes are learning opportunities, not disasters
- Iteration is expected and encouraged
- Delete the branch and try again - that's what Git is for
- Process documentation matters more than perfect outcomes
- Growth mindset is built into every assignment

**2. GitHub-First Workflow**
- Professional development practices from day 1
- Issue → Branch → PR → Review → Merge for EVERYTHING
- Main branch is protected (students literally can't break it)
- Version control makes failure safe
- Portfolio building is automatic via contribution graph

**3. Second-Order Skills Focus**
The course teaches AI/ML concepts through developing transferable skills:
- **Documentation**: Clear communication of process and results
- **Resilience**: Embracing failure as data
- **Growth Mindset**: Celebrating progress over perfection
- **Critical Thinking**: Questioning AI outputs, understanding limitations
- **Professional Workflow**: Industry-standard practices

**4. Progressive Branching Model**
- Weeks 1-3: Everyone together (foundations)
- Weeks 4-6: Differentiation begins
- Weeks 7-10: Two tracks (Prompt Masters / Code Builders)
- Weeks 11-16: Tracks converge for community projects
- **Both tracks are equally rigorous** - different methods, same competencies

**5. Process Over Product**
- Assessment values documentation and reflection
- "How did you approach this?" matters more than "Did it work perfectly?"
- Students document AI interactions, iterations, dead-ends
- Portfolio shows learning journey, not just final artifacts

### Key Mantras (Use These!)

> "Hello, Scholars!" - Opening every class/document with respect
>
> "Failure is just exercise. Delete the branch and try again."
>
> "The GitHub contribution graph IS your grade."
>
> "We're not teaching them to code. We're teaching them to learn."
>
> "Kevin from IT never judges your code. Kevin just helps."

### What This Means for Your Work

When creating materials, always:
- **Normalize failure**: Build in expected mistakes and how to recover
- **Document process**: Require showing work, not just final answers
- **Encourage iteration**: Multiple attempts are the point
- **Support both tracks**: Non-coders are not "lesser" - equal rigor, different tools
- **Be specific**: Vague instructions increase frustration
- **Be encouraging**: Assume students are trying their best
- **Be realistic**: Acknowledge challenges while providing solutions

---

## 📝 ASSIGNMENT DEVELOPMENT STANDARDS

### Required Components for Every Assignment

Every student-facing assignment must include:

#### 1. Header Section
```markdown
# Week X Assignment: "[Memorable Title]"
## CSC-113 AI Fundamentals - [Subtitle/Theme]

**Due**: End of Week X (Friday, 11:59 PM)  
**Points**: 25 (25% of Module grade)  
**Submission**: Via GitHub repository (PR #X)
```

#### 2. Assignment Overview (2-3 paragraphs)
- What they're learning (skills and concepts)
- Why it matters (real-world context)
- How it connects to previous/future work

#### 3. Learning Objectives (3-5 bullets)
"By completing this assignment, you will:"
- Action verbs (demonstrate, create, analyze, explain)
- Measurable outcomes
- Aligned with course-level objectives

#### 4. Detailed Instructions
- **Step-by-step format** (numbered or clearly sequenced)
- **GitHub workflow integrated** (Issue → Branch → Work → PR)
- **Code blocks** for anything students should copy
- **Screenshots or visual aids** where helpful
- **Deliverables checklist** at task boundaries

#### 5. Track Differentiation (When Applicable)
If tracks diverge (Weeks 7+):
```markdown
## CORE ASSIGNMENT (ALL STUDENTS)
[Tasks everyone does]

## TRACK-SPECIFIC ADDITIONS
### Option A: Code Builders Track
[Additional technical tasks]

### Option B: Prompt Masters Track  
[Additional no-code/prompt tasks]
```

**Critical**: Both tracks must have equivalent time/effort/rigor

#### 6. Assessment Rubric
Four categories (25% each = 6.25 points each):

**AI Partnership Quality**
- Prompt sophistication over time
- Appropriate tool selection
- Evidence of iteration
- Critical evaluation of outputs

**Problem-Solving Process**
- Clear problem definition
- Systematic approach
- Testing methodology
- Learning from failures

**Professional Communication**
- Documentation clarity
- GitHub portfolio quality
- Peer review effectiveness
- Presentation skills

**Critical Thinking & Ethics**
- Questioning AI outputs
- Bias identification
- Independent judgment
- Ethical considerations

Each category needs:
- Excellent (5.5-6.25): Detailed description
- Good (4.5-5.4): Detailed description
- Needs Improvement (<4.5): Detailed description

#### 7. Common Mistakes & Troubleshooting
Anticipate student struggles:
```markdown
### "I can't [common problem]"
**Fix**: [Clear solution]
**Why this happens**: [Brief explanation]
```

#### 8. Getting Help Section
- When to ask for help
- Where to get help (channels, office hours)
- How to ask good questions
- What to try first before asking

#### 9. Looking Ahead
- Brief preview of next week
- How this assignment connects forward
- Portfolio building context

#### 10. Final Checklist
Students can self-assess completion:
- [ ] Task-specific items
- [ ] GitHub workflow items
- [ ] Documentation items
- [ ] Quality standards met

---

## 🔧 GITHUB WORKFLOW FOR CLAUDE CODE

### Before Starting Work

1. **Review assigned Issue** carefully
2. **Check for dependencies**: Does this require other work to be completed first?
3. **Note any special requirements** in the Issue description
4. **Verify you understand the pedagogical context**

### Branch Naming Convention

```
feature/[issue-number]-[brief-description]

Examples:
feature/12-week-6-holiday-shopping
feature/15-student-github-guide
feature/18-assessment-rubrics
```

### Commit Message Format

```
type(scope): brief description

Types:
- feat: New feature/assignment
- docs: Documentation changes
- fix: Bug fixes or corrections
- refactor: Restructuring without changing functionality
- chore: Maintenance tasks

Examples:
feat(assignments): add Week 6 Holiday Shopping Research assignment
docs(guides): create GitHub survival guide for students
fix(week-02): correct track differentiation instructions
refactor(rubrics): align all assignments to 4-category framework
```

### Pull Request Standards

**PR Title Format:**
```
Closes #[issue-number] - [Clear description]

Example:
Closes #12 - Add Week 6 Holiday Shopping Research assignment
```

**PR Description Must Include:**

```markdown
## What This Adds/Changes
[Clear description of the work done]

## Checklist
- [ ] Follows assignment template structure
- [ ] Includes all required components
- [ ] Assessment rubric uses 4-category framework
- [ ] Both tracks addressed (if applicable)
- [ ] Troubleshooting section included
- [ ] Reviewed for clarity and encouragement
- [ ] Proofread for typos and formatting
- [ ] Tested any code examples provided

## Pedagogical Notes
[How this assignment reinforces course philosophy]

## Questions/Concerns
[Any uncertainties or areas needing review]

## Closes
Closes #[issue-number]
```

### When to Use Available Agents/Tools

**File Operations Agent**:
- Creating new assignment files
- Reading existing templates
- Updating directory structures
- Organizing folders

**Web Search Agent**:
- Verifying factual information (dates, technical details)
- Finding current AI tool capabilities/pricing
- Checking if concepts are explained correctly
- Researching pedagogical best practices

**Bash Tool**:
- Minimal use - mostly for file operations
- Creating directory structures if needed
- Running validation scripts (if we create them)

**When in Doubt**: 
- Check existing assignments for patterns
- Reference the pedagogical philosophy
- Ask in PR description if clarification is needed

---

## ✅ QUALITY STANDARDS

### Student-Facing Language

**DO:**
- Use "you" and active voice
- Be encouraging and supportive
- Normalize struggle and mistakes
- Provide specific examples
- Break complex tasks into steps
- Celebrate small wins
- Use accessible technical language

**DON'T:**
- Use passive voice or academic jargon
- Assume prior knowledge
- Be condescending or dismissive
- Leave students guessing
- Skip the "why" behind tasks
- Create busywork

**Tone Examples:**

✅ Good: "Let's create your first branch! This might feel like extra steps now, but you'll thank yourself later when you need to undo changes."

❌ Bad: "Creating branches is standard practice in version control systems and will be required for all submissions."

✅ Good: "Hit a rate limit? Great! You just learned why professional developers optimize for cost. Let's talk about what to do next."

❌ Bad: "Students must manage rate limits appropriately to avoid service interruptions."

### Instructor-Facing Materials

**DO:**
- Be direct and concise
- Provide decision-making frameworks
- Include time estimates
- Anticipate problems with solutions
- Reference pedagogical theory when relevant

**DON'T:**
- Overexplain the obvious
- Skip practical implementation details
- Assume unlimited time
- Leave gap-filling to instructors

### Code Examples

All code must be:
- **Tested**: Run it yourself before including
- **Commented**: Explain what each section does
- **Beginner-appropriate**: Even "simple" code needs explanation
- **Copy-pasteable**: Correct syntax, no typos
- **Safe**: No security issues, no dangerous operations

### Markdown Formatting

- Use **bold** for emphasis (sparingly)
- Use `code blocks` for commands, filenames, code
- Use > blockquotes for key principles or quotes
- Use tables for comparisons
- Use checklists [ ] for tasks
- Use headers hierarchically (don't skip levels)
- Include blank lines between sections for readability

---

## 🎯 CURRENT STATUS & PRIORITIES

### ✅ Complete and Available for Reference

Located in `artifacts/overview/` or as indicated:

**Assignments:**
- Week 1: Hello GitHub (reference)
- Week 2: Meet Kevin & SAGE (reference)
- Week 3: AI Timeline Research (reference)
- Week 4: Bad Bot (exists in artifacts)
- Week 5: Good Bot (exists in artifacts)
- Week 7: Project Ideation (exists in artifacts)
- Week 8: Vibe Coding (Code Builders only - exists in artifacts)

**Instructor Materials:**
- Operations Manual (multiple versions in artifacts)
- Assessment Framework document
- Technical infrastructure research
- Course philosophy documents

**Course Structure:**
- 16-week outline (reference)

### 🟡 Partial - Needs Completion

**Priority 1 (Needed Immediately):**
- Week 6: Holiday Shopping Research (concept exists, needs full assignment)
- Week 8: No-Code AI Agent (Prompt Masters track - needs creation)

**Priority 2 (Needed Soon):**
- Week 9: Community Partner Kickoff (structure exists, needs student-facing materials)
- Week 10: Project Planning Package (needs creation)

**Priority 3 (Supporting Materials):**
- Student GitHub Survival Guide
- AI Tools Getting Started Guide
- Troubleshooting FAQ
- Assessment Rubrics (consolidated)

### 🔴 Missing - Needs Creation

**Templates:**
- Assignment template (for consistency)
- PR template (for repository)
- Sprint templates (Weeks 11-16)

**Examples:**
- Example submissions (A/B/C quality for each assignment)
- Example portfolios
- Example peer reviews

**Project Phase (Weeks 11-16):**
- Sprint planning templates
- Retrospective formats
- Partner check-in agendas
- Final presentation guidelines
- Handoff documentation template

---

## 🎨 TRACK DIFFERENTIATION GUIDELINES

### Core Principles

1. **Equal Rigor**: Different methods, same learning objectives
2. **No Value Judgments**: Neither track is "better" or "easier"
3. **Convergence**: Both tracks collaborate on community projects (Weeks 11-16)
4. **Flexibility**: Students can switch tracks until Week 6

### Code Builders Track

**Focus**: Programming with AI assistance, technical implementation, API integration

**Typical Tools:**
- GitHub Codespaces
- Python + libraries
- Google Colab / Jupyter
- Local models (Ollama)
- API integration

**Assignment Additions:**
- Setting up development environments
- Writing and testing code
- Understanding technical documentation
- Debugging with AI assistance
- Version control beyond web interface

**Deliverables Often Include:**
- Working code with tests
- Technical documentation
- Architecture decisions explained
- Performance considerations

### Prompt Masters Track

**Focus**: Natural language AI collaboration, no-code tools, prompt engineering mastery

**Typical Tools:**
- Google AI Studio / Gemini
- Custom GPTs / Gems
- No-code automation platforms
- Visual design tools with AI integration

**Assignment Additions:**
- Advanced prompt engineering techniques
- Custom AI assistant creation
- Workflow automation design
- Business process thinking
- User experience design

**Deliverables Often Include:**
- Sophisticated prompts with iteration history
- No-code system configurations
- User documentation
- Workflow diagrams

### Creating Track-Specific Content

When an assignment has track-specific sections:

1. **Start with core content** (everyone does this)
2. **Clearly label track sections**: Use headers and visual separation
3. **Equivalent time/effort**: Track additions should take ~same amount of time
4. **Meet same objectives**: Different paths to same learning outcomes
5. **Cross-pollination opportunities**: Consider where tracks can learn from each other

**Template Structure:**
```markdown
## PART 1: CORE ASSIGNMENT (ALL STUDENTS)
[Everyone does this - 60-70% of assignment]

## PART 2: TRACK-SPECIFIC ADDITIONS
[Choose ONE track - 30-40% of assignment]

### OPTION A: CODE BUILDERS TRACK
**Additional Time**: [X hours]
**What You'll Learn**: [Specific to this track]
[Detailed instructions]

### OPTION B: PROMPT MASTERS TRACK  
**Additional Time**: [X hours]
**What You'll Learn**: [Specific to this track]
[Detailed instructions]
```

---

## 📊 ASSESSMENT FRAMEWORK INTEGRATION

### The Four-Category Model

Every assignment must be assessed across four categories (25% each):

**1. AI Partnership Quality (25%)**
*How effectively does the student collaborate with AI tools?*

Evaluation criteria:
- Prompt sophistication and iteration
- Appropriate tool selection for tasks
- Evidence of learning from AI interactions
- Critical evaluation of AI outputs
- Documentation of AI collaboration process

**2. Problem-Solving Process (25%)**
*How systematically does the student approach challenges?*

Evaluation criteria:
- Clear problem definition
- Logical approach to solutions
- Testing methodology
- Learning from failures
- Process documentation

**3. Professional Communication (25%)**
*How clearly does the student document and present work?*

Evaluation criteria:
- GitHub portfolio quality
- Documentation clarity
- Peer review participation and quality
- Professional presentation standards
- Commit messages and PR descriptions

**4. Critical Thinking & Ethics (25%)**
*How thoughtfully does the student evaluate AI and its implications?*

Evaluation criteria:
- Questioning AI outputs rather than blind acceptance
- Identifying potential bias or limitations
- Making informed decisions about AI use
- Considering ethical implications
- Demonstrating growth mindset in reflections

### Creating Rubrics

For each category in each assignment, provide:

**Excellent (5.5-6.25 points)**: 
- 3-4 specific observable behaviors
- Examples of what this looks like in context

**Good (4.5-5.4 points)**:
- 3-4 specific observable behaviors
- How this differs from excellent

**Needs Improvement (<4.5 points)**:
- 3-4 specific observable behaviors
- What's missing or problematic

**Example:**

```markdown
### AI Partnership Quality (25% = 6.25 pts)

**Excellent (5.5-6.25):**
- Prompts show clear iteration and refinement (3+ versions documented)
- Student explains tool selection rationale with specific reasons
- Evidence of testing multiple approaches and comparing results
- Reflections demonstrate critical evaluation ("This worked because...")

**Good (4.5-5.4):**
- Prompts show some iteration (2 versions documented)
- Tool selection mentioned but reasoning is basic
- Some testing visible in documentation
- Reflections include evaluation but are brief

**Needs Improvement (<4.5):**
- No evidence of prompt iteration or refinement
- Random tool selection without explanation
- No testing methodology visible
- Reflections are generic or missing
```

---

## 🔍 REVIEW CHECKLIST FOR PULL REQUESTS

Before submitting your PR, verify:

### Content Completeness
- [ ] All required sections included
- [ ] Learning objectives are clear and measurable
- [ ] Instructions are step-by-step and specific
- [ ] Both tracks addressed (if applicable)
- [ ] Assessment rubric uses 4-category framework
- [ ] Examples and templates provided where helpful
- [ ] Troubleshooting section anticipates common issues
- [ ] Final checklist enables student self-assessment

### Pedagogical Alignment
- [ ] "Failure is exercise" philosophy visible
- [ ] GitHub workflow integrated naturally
- [ ] Second-order skills emphasized
- [ ] Process documentation required
- [ ] Growth mindset encouraged
- [ ] Realistic about challenges
- [ ] Encouraging and supportive tone

### Quality Standards
- [ ] All code examples tested and working
- [ ] Markdown formatting is clean
- [ ] No typos or grammatical errors
- [ ] Links work correctly
- [ ] File/folder names follow conventions
- [ ] Consistent with other assignments in style

### Student Experience
- [ ] Instructions are clear without prior knowledge
- [ ] Time estimates are realistic
- [ ] Deliverables are well-defined
- [ ] Help resources are provided
- [ ] Connection to previous/future work is clear
- [ ] Student can self-assess readiness to submit

---

## 🚨 SPECIAL CONSIDERATIONS

### Rate Limits as Teaching Moments

When students hit API rate limits, this is **intentional pedagogy**, not a problem to solve:

**DO:**
- Present rate limits as normal professional constraint
- Teach resource management and optimization
- Provide backup tools (cascade: Flash → Flash-Lite → Claude → ChatGPT)
- Document when/why to switch tools
- Make this a reflection opportunity

**DON'T:**
- Apologize for rate limits
- Suggest paid tiers (course must remain free)
- Work around limits via multiple accounts (teaches wrong lesson)
- Skip the learning opportunity

**Example Language:**
```markdown
### When You Hit Rate Limits

**This is normal!** Professional developers manage resource constraints daily. 
When Gemini Flash slows down after ~10 prompts:

1. Switch to Flash-Lite (cheaper, faster, less sophisticated)
2. Use Claude or ChatGPT as backup
3. Take a break and come back later
4. Document this in your reflection: What did you learn about tool management?

This is the lesson: Real-world AI has real-world constraints.
```

### Non-Programmers Are Not "Lesser"

Language matters. Never imply that:
- Code Builders track is more "technical" or "advanced"
- Prompt Masters is the "easier" track
- Programming is inherently more valuable

**DO:**
- Emphasize different strengths serve different purposes
- Show how both tracks require sophisticated thinking
- Demonstrate how prompt engineering is its own technical skill
- Value business thinking and user experience design

**Example:**
✅ "The Prompt Masters track focuses on sophisticated natural language AI orchestration and business process design."

❌ "The non-programming track is for students who can't code."

### Privacy and Safety

Students work on public portfolios but may have privacy concerns:

**Guidelines:**
- Students can use first name or username (not required to use full name)
- Repository can be private until they choose to make it public
- Personal information in reflections is optional
- No requirement to share social media or personal details
- GitHub profiles are professional, not social

**Never require:**
- Real names if student uncomfortable
- Personal photos
- Contact information beyond school email
- Social media presence

---

## 📚 REFERENCE MATERIALS LOCATION

### In This Repository

**Artifacts folder** (`/artifacts/`):
- Course philosophy documents
- Original operations manuals
- Assessment framework
- Technical research (AI tools, costs, deployment)
- Bad Bot / Good Bot assignments (originals)

**Outline folder** (`/outline/`):
- 16-week complete outline
- Module-by-module structure
- Learning objectives by week

### External References

If you need to verify something:
- Use web search to check current AI tool capabilities
- Verify technical information (API limits, costs, features)
- Research pedagogical best practices when relevant
- **Always cite sources** when pulling external information

---

## 🤝 COLLABORATION NOTES

### Multiple Claude Instances Working Simultaneously

**To avoid conflicts:**
1. **Work on separate Issues**: Each Issue = one Claude instance
2. **Create feature branch immediately**: Before any commits
3. **Communicate in PR descriptions**: Note any dependencies
4. **Check existing work**: Reference similar completed assignments
5. **Maintain consistency**: Use established patterns and templates

### When You Notice Inconsistencies

If you see something that doesn't match standards:
- **Note it in your PR description**
- **Suggest improvements** if you have them
- **Don't unilaterally change** other completed work
- **Ask for clarification** via PR comments

### Questions or Uncertainties

Include a **Questions/Concerns** section in every PR:
- "Should this assignment include a video component?"
- "Is 3 hours a realistic time estimate for this?"
- "Track differentiation seems light here - intentional?"
- "Similar to Week X but with these differences - correct?"

---

## 🎯 SUCCESS CRITERIA

Your work is successful when:

**For Students:**
- Instructions are so clear that students can succeed independently
- Mistakes are anticipated and solutions provided
- Time to complete is realistic (not too easy, not overwhelming)
- Students feel encouraged and supported
- Deliverables demonstrate learning, not just completion

**For Instructors:**
- Assignment can be implemented without extensive preparation
- Assessment is straightforward using provided rubrics
- Common issues are documented with solutions
- Materials are ready-to-use, not outlines requiring expansion

**For Course:**
- Pedagogical philosophy is evident throughout
- Learning objectives are met through authentic tasks
- Professional standards are maintained
- Both tracks are supported equally
- Portfolio artifacts demonstrate real competency

---

## 📞 GETTING HELP / QUESTIONS

If you're uncertain about something:

1. **Check this CLAUDE.md** first
2. **Review similar completed assignments** for patterns
3. **Search artifacts** for existing examples
4. **Note questions in PR description** - maintainer will clarify
5. **Make your best judgment** and document your reasoning

**Remember**: It's better to ask in the PR than to guess wrong and create work that needs revision.

---

## 🎓 FINAL REMINDERS

### The Big Picture

We're not just creating assignments. We're building:
- A course that makes AI literacy accessible to everyone
- Professional portfolio artifacts students can show employers
- Confidence in using and evaluating AI tools
- Critical thinking about AI capabilities and limitations
- Transferable skills that outlast specific technologies

### Your Role Matters

Every assignment you create will be used by real students who:
- May have never coded before
- May be returning to education after years away
- May be intimidated by technology
- May be brilliant but need clear guidance
- **Will remember if we made them feel capable or confused**

Make them feel capable.

### When In Doubt

Ask yourself:
- Would I understand these instructions if I'd never used GitHub?
- Would this make me excited to learn, or stressed about failing?
- Does this reward process and learning, or just correct answers?
- Can both tracks succeed equally with these instructions?
- Is the pedagogical purpose clear?

If the answer to any is "no" - revise until it's "yes."

---

**Thank you for contributing to CSC-113 AI Fundamentals course development. Your work will directly impact students' learning experiences and career preparation.**

---

*Version: 1.0*  
*Last Updated: November 4, 2025*  
*For Questions: Check GitHub Issues or create new Issue for clarification*
