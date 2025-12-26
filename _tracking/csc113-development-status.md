# CSC-113 AI Fundamentals: Development Status & Planning Document

**Document Version:** 0.1  
**Last Updated:** 2025-01-26  
**Purpose:** Establish baseline for course manifest creation and prioritize development work

---

## 1. Course Metadata (Confirmed)

| Field | Value |
|-------|-------|
| **Course ID** | CSC-113 |
| **Course Name** | AI Fundamentals |
| **Credits** | 3 |
| **Prerequisites** | None |
| **Corequisites** | None |
| **Semester Length** | 16 weeks |
| **Module Structure** | 8 modules × 2 weeks each |
| **Repository** | `course-csc113-template` |
| **Badge Criteria** | To be developed |

### Catalog Description (Current)
> This course provides a survey of artificial intelligence and machine learning. Topics include the history, development, and current applications of artificial intelligence and machine learning. Upon completion, students should be able to demonstrate general artificial intelligence and machine learning concepts.

### Learning Outcomes (Need Expansion)
The current catalog description is minimal. Suggested expanded outcomes based on existing course materials:

1. Apply professional software development workflows using GitHub (Issues, branches, PRs, reviews)
2. Effectively collaborate with AI tools to solve problems and create applications
3. Demonstrate prompt engineering techniques across multiple AI platforms
4. Evaluate AI outputs critically, identifying limitations, bias, and appropriate use cases
5. Build and deploy a functional AI-assisted application (SAGE project)
6. Communicate technical work through documentation and portfolio presentation
7. Apply ethical reasoning to AI implementation decisions

---

## 2. Proposed Module Structure

| Module | Name | Weeks | Primary Focus |
|--------|------|-------|---------------|
| M01 | AI Foundations & GitHub Workflow | 1-2 | What is AI, GitHub basics, professional workflow |
| M02 | Your First AI Assistant | 3-4 | Gemini/Claude basics, SAGE introduction, rate limits |
| M03 | Prompt Engineering Fundamentals | 5-6 | Effective prompting, iteration, documentation |
| M04 | AI-Assisted Problem Solving | 7-8 | Using AI for real tasks, critical evaluation |
| M05 | Specialization Tracks | 9-10 | Prompt Masters vs Code Builders divergence |
| M06 | Building AI Applications | 11-12 | Technical implementation, APIs, deployment |
| M07 | Real-World Integration | 13-14 | Community partners, authentic projects |
| M08 | Capstone & Portfolio Defense | 15-16 | Final project, presentation, badge assessment |

---

## 3. Content Inventory: What Exists

### 3.1 Instructor Resources (Strong)

| Document | Status | Notes |
|----------|--------|-------|
| CSC-113 Instructor Operations Manual | Complete | Comprehensive daily/weekly operations |
| GameFAQs-Style Instructor Guide | Complete | Engaging alternative format, same content |
| Integrated Implementation Guide | Complete | Ties philosophy to practice |
| AI-Required Assessment Framework | Complete | Philosophy established, needs rubric conversion |

### 3.2 Technical Documentation (Strong)

| Document | Status | Notes |
|----------|--------|-------|
| SAGE MVP Project Summary | Complete | Architecture, code samples, deployment |
| Gemini 2.5 Model Selection Guide | Complete | Cost optimization, task routing |
| Free AI Tools Research | Complete | Platform comparison, student options |
| Hugging Face Implementation Guide | Complete | Local models, advanced deployment |
| Practical Gemini Guide for Students | Complete | Student-accessible technical reference |
| Docker Compose Configuration | Complete | Deployment ready |

### 3.3 Pedagogical Framework (Strong)

| Document | Status | Notes |
|----------|--------|-------|
| GitHub-First Workflow Rationale | Complete | "Correct process, creative code" philosophy |
| Progressive Branching Model | Complete | Mixed-ability learner design |
| Assessment Framework Development | Draft | Categories defined, rubrics not formalized |

### 3.4 Student-Facing Content (Weak)

| Content Type | Exists | Notes |
|--------------|--------|-------|
| Chapter readings | 0 | Need full development |
| Step-by-step tutorials | ~2 partial | Gemini guide is close, needs adaptation |
| Lab assignments | 0 | Described in instructor docs, not written |
| Homework assignments | 0 | Not developed |
| Project specifications | 0 | SAGE described but no formal spec |
| Rubrics (usable format) | 0 | Framework exists, needs conversion |

---

## 4. Gap Analysis by Module

### M01: AI Foundations & GitHub Workflow
**Instructor content:** Excellent (Week 1 operations fully documented)  
**Student content needed:**
- [ ] Reading: "What is AI?" (history, types, current applications)
- [ ] Reading: "Professional Development Workflows" (GitHub basics)
- [ ] Tutorial: GitHub account setup and first repository
- [ ] Tutorial: Issues, branches, and PRs walkthrough
- [ ] Lab 1: Environment verification and first commit
- [ ] Lab 2: Complete Issue → Branch → PR → Merge cycle

### M02: Your First AI Assistant
**Instructor content:** Good (Week 2 operations, rate limit management)  
**Student content needed:**
- [ ] Reading: "Working with AI Assistants" (Gemini, Claude, ChatGPT)
- [ ] Reading: "Understanding Rate Limits and Costs"
- [ ] Tutorial: Google AI Studio setup
- [ ] Tutorial: Your first conversation with Gemini
- [ ] Lab 3: Building "Kevin Jr." - basic assistant prompts
- [ ] Lab 4: Prompt iteration and documentation
- [ ] Homework 1: AI assistant comparison exercise

### M03: Prompt Engineering Fundamentals
**Instructor content:** Scattered references, no dedicated module  
**Student content needed:**
- [ ] Reading: "The Art of Prompting" (techniques, patterns)
- [ ] Reading: "Context, Constraints, and Examples"
- [ ] Tutorial: Prompt engineering patterns with examples
- [ ] Tutorial: Multi-turn conversations and memory management
- [ ] Lab 5: Structured prompt development
- [ ] Lab 6: Prompt templates and reusability
- [ ] Homework 2: Prompt library creation

### M04: AI-Assisted Problem Solving
**Instructor content:** Philosophy in mixed-ability learner doc  
**Student content needed:**
- [ ] Reading: "AI as Thought Partner" (problem decomposition)
- [ ] Reading: "Critical Evaluation of AI Outputs"
- [ ] Tutorial: Debugging with AI assistance
- [ ] Tutorial: Research and synthesis with AI
- [ ] Lab 7: Solve a real problem with documented AI collaboration
- [ ] Lab 8: Error detection and correction exercise
- [ ] Project 1 Spec: "SAGE Foundation" - basic study assistant

### M05: Specialization Tracks
**Instructor content:** Track descriptions exist  
**Student content needed:**
- [ ] Reading: "Choosing Your Path" (Prompt Masters vs Code Builders)
- [ ] Prompt Masters Tutorial: Advanced AI Studio techniques
- [ ] Prompt Masters Tutorial: Custom GPT/Assistant creation
- [ ] Code Builders Tutorial: Python + API basics
- [ ] Code Builders Tutorial: LangChain introduction
- [ ] Lab 9A/9B: Track-specific exercises (two versions)
- [ ] Lab 10A/10B: Track-specific exercises (two versions)

### M06: Building AI Applications
**Instructor content:** SAGE technical docs are strong  
**Student content needed:**
- [ ] Reading: "From Prototype to Application"
- [ ] Reading: "AI Application Architecture Patterns"
- [ ] Tutorial: Streamlit/Gradio basics (for Prompt Masters)
- [ ] Tutorial: FastAPI + Gemini integration (for Code Builders)
- [ ] Lab 11: Build a deployable component
- [ ] Lab 12: Testing and iteration
- [ ] Project 2 Spec: "SAGE Enhancement" - add features to base

### M07: Real-World Integration
**Instructor content:** Community partner coordination documented  
**Student content needed:**
- [ ] Reading: "Working with Stakeholders"
- [ ] Reading: "Requirements Gathering for AI Projects"
- [ ] Tutorial: Scoping an AI solution
- [ ] Tutorial: Presentation and demo preparation
- [ ] Lab 13: Partner project kickoff
- [ ] Lab 14: Mid-project review and pivot
- [ ] Homework 3: Project documentation update

### M08: Capstone & Portfolio Defense
**Instructor content:** Assessment operations documented  
**Student content needed:**
- [ ] Reading: "Building Your Portfolio"
- [ ] Reading: "Presenting Technical Work"
- [ ] Tutorial: GitHub portfolio optimization
- [ ] Tutorial: Demo preparation checklist
- [ ] Project 3 Spec: "Community Partner Deliverable"
- [ ] Capstone Spec: Portfolio defense requirements
- [ ] Rubric: Final assessment criteria

---

## 5. Deliverable Summary

| Type | Total Needed | Currently Exist | Gap |
|------|--------------|-----------------|-----|
| Readings | 16 | 0 | 16 |
| Tutorials | 18 | ~2 (partial) | 16 |
| Labs | 14 | 0 | 14 |
| Homework | 3 | 0 | 3 |
| Projects | 3 | 0 | 3 |
| Capstone | 1 | 0 | 1 |
| Rubrics | 4 | 0 (framework only) | 4 |
| **TOTAL** | **59** | **~2** | **57** |

**Estimated Current Completion: ~3%** (student-facing content only)  
**With instructor materials factored: ~20-25%** (strong foundation, weak deliverables)

---

## 6. Priority Matrix

### Tier 1: Critical Path (Blocks Everything Else)
1. **Formalize learning outcomes** - Required for all downstream work
2. **M01 Reading: What is AI?** - Students need this Day 1
3. **M01 Reading: GitHub Workflow** - Foundation for entire course
4. **M01 Labs 1-2** - Students must practice immediately
5. **Convert Assessment Framework to Rubric** - Need grading criteria

### Tier 2: Core Course Function (Weeks 1-8 Content)
6. M02 Readings and Tutorials (AI assistant basics)
7. M02 Labs 3-4 (First assistant)
8. M03 Readings (Prompt engineering)
9. M03 Labs 5-6 (Prompt practice)
10. M04 Readings (Problem solving)
11. M04 Labs 7-8 (Real problems)
12. **Project 1 Spec** (SAGE Foundation - "C grade" milestone)

### Tier 3: Specialization Content (Weeks 9-12)
13. M05 Track-specific tutorials and labs
14. M06 Application building content
15. **Project 2 Spec** (SAGE Enhancement - "B grade" milestone)

### Tier 4: Capstone Content (Weeks 13-16)
16. M07 Community partner content
17. M08 Portfolio and presentation guides
18. **Project 3 + Capstone Spec** (Final deliverables - "A grade")
19. Badge criteria formalization

---

## 7. Resource Reuse Opportunities

Several existing documents can be adapted rather than written from scratch:

| Existing Document | Can Become |
|-------------------|------------|
| Practical Gemini Guide for Students | M02 Reading (with edits) |
| Free AI Tools Research | M02 Reference material |
| SAGE MVP Summary | M06 Reading foundation |
| Gemini Model Selection Guide | M02/M06 Reference |
| Assessment Framework | Rubric source material |
| Mixed-Ability Learner Design | M05 Track guidance |

---

## 8. Recommended Development Sequence

### Sprint 1: Foundation (Target: 2-3 days of focused work)
- [ ] Expand learning outcomes (7 outcomes minimum)
- [ ] M01 Reading 1: What is AI?
- [ ] M01 Reading 2: GitHub Workflow
- [ ] M01 Lab 1: Environment setup
- [ ] M01 Lab 2: GitHub cycle practice
- [ ] 4-Category Rubric v1.0

### Sprint 2: AI Basics (Target: 2-3 days)
- [ ] M02 Reading 1: Working with AI (adapt from Gemini guide)
- [ ] M02 Reading 2: Rate limits and costs
- [ ] M02 Tutorial 1: AI Studio setup
- [ ] M02 Labs 3-4: Kevin Jr. development
- [ ] M02 Homework 1: Platform comparison

### Sprint 3: Prompt Engineering (Target: 2 days)
- [ ] M03 Reading 1: Prompting techniques
- [ ] M03 Reading 2: Context and constraints
- [ ] M03 Labs 5-6: Prompt practice

### Sprint 4: Problem Solving + Project 1 (Target: 2 days)
- [ ] M04 Readings 1-2
- [ ] M04 Labs 7-8
- [ ] Project 1 Specification (SAGE Foundation)

*Subsequent sprints cover M05-M08 as time allows*

---

## 9. Notes for Claude Code Instance

When working on this repository:

1. **Check manifest first** - `course-manifest.yaml` is source of truth for what exists
2. **Follow directory structure** - `module-XX/` with `readings/`, `tutorials/`, `labs/`, `homework/`, `projects/` subdirectories
3. **Update manifest when creating content** - Change status from `planned` → `draft` → `complete`
4. **Maintain consistent voice** - Student content should be engaging, instructor content can be detailed
5. **Reference existing materials** - Don't recreate what exists in different form
6. **Preserve "failure is just exercise" culture** - This philosophy permeates all content

---

## 10. Open Questions

1. **Badge name and skills?** - Need to define what the CSC-113 badge certifies
2. **Community partner integration timeline?** - When do partners get involved?
3. **Assessment weighting?** - How much is each project/category worth?
4. **Synchronous vs asynchronous?** - Is this designed for in-person, online, or hybrid?
5. **Textbook integration?** - Is there an adopted text, or all custom content?

---

*This document should be updated as decisions are made and content is developed.*
