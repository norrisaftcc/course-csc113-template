# CSC-113 AI Fundamentals: Development Status & Gap Analysis

**Document Version:** 0.2
**Last Updated:** 2026-01-01
**Purpose:** Track course content development status and prioritize work

---

## 1. Course Metadata

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

### Learning Outcomes
1. Apply professional software development workflows using GitHub (Issues, branches, PRs, reviews)
2. Effectively collaborate with AI tools to solve problems and create applications
3. Demonstrate prompt engineering techniques across multiple AI platforms
4. Evaluate AI outputs critically, identifying limitations, bias, and appropriate use cases
5. Build and deploy a functional AI-assisted application (SAGE project)
6. Communicate technical work through documentation and portfolio presentation
7. Apply ethical reasoning to AI implementation decisions

---

## 2. Module Structure (Updated)

| Module | Name | Weeks | Primary Focus |
|--------|------|-------|---------------|
| M01 | AI Foundations & GitHub Workflow | 1-2 | GitHub basics, AI introductions, SAGE setup |
| M02 | AI Tool Exploration | 3-4 | AI History, Bad Bot design experiments |
| M03 | Prompt Engineering | 5-6 | Good Bot iteration, practical research |
| M04 | Project Ideation | 7-8 | Project ideas, track specialization |
| M05 | Rapid Prototyping | 9-10 | MVP development, quick iterations |
| M06 | Application Building | 11-12 | Sprint 1, feature development |
| M07 | Real-World Integration | 13-14 | Sprint 2, community partner work |
| M08 | Capstone & Portfolio Defense | 15-16 | Final project, presentation, portfolio |

---

## 3. Content Inventory: Current Status

### 3.1 Student-Facing Assignments (Primary Deliverables)

| Week | Assignment Name | Status | Location | Source Material |
|------|-----------------|--------|----------|-----------------|
| 1 | Hello GitHub | ✅ **COMPLETE** | `/assignments/Week_01_Assignment_Hello_GitHub.md` | Original + Canvas m1_assign1 |
| 2 | Meet Kevin & SAGE | ✅ **COMPLETE** | `/assignments/Week_02_Assignment_Meet_Kevin_and_SAGE.md` | Original + Canvas m1_assign2 |
| 3 | AI Timeline Research | ✅ **COMPLETE** | `/assignments/Week_03_Assignment_AI_Timeline_Research.md` | Original |
| 4 | Bad Bot | ❌ **NEEDS CREATION** | - | Canvas m2_hw1, bad-bot-gallery.md |
| 5 | Good Bot | ❌ **NEEDS CREATION** | - | Canvas m3_hw1, Good Bot PDF |
| 6 | Holiday Shopping Research | ✅ **COMPLETE** | `/assignments/Week_06_Assignment_Holiday_Shopping_Research.md` | Original |
| 7 | Project Ideation | ❌ **NEEDS CREATION** | - | Canvas m4_assign1 |
| 8 | Track Specialization | ❌ **NEEDS CREATION** | - | Canvas content (vibe coding) |
| 9 | Rapid Prototype Sprint | ❌ **NEEDS CREATION** | - | Canvas m5_homework1 |
| 10 | Project Planning | ❌ **NEEDS CREATION** | - | Needs design |
| 11 | Sprint 1 Kickoff | ❌ **NEEDS CREATION** | - | Needs design |
| 12 | Sprint 1 Review | ❌ **NEEDS CREATION** | - | Needs design |
| 13 | Sprint 2 Kickoff | ❌ **NEEDS CREATION** | - | Needs design |
| 14 | Sprint 2 Review | ❌ **NEEDS CREATION** | - | Needs design |
| 15 | Portfolio Preparation | ❌ **NEEDS CREATION** | - | Canvas m8_project |
| 16 | Final Presentation | ❌ **NEEDS CREATION** | - | Canvas m8_project |

### 3.2 Canvas Import Mapping

| Canvas Module | Canvas Content | Maps To | Status |
|---------------|----------------|---------|--------|
| M1 | m1_assign1 (GitHub Profile) | Week 1 | ✅ Integrated |
| M1 | m1_assign2 (Hello G-Flash) | Week 2 | ✅ Integrated |
| M1 | m1_discuss1 (AI in Daily Life) | Discussion activity | ⚠️ Can integrate into Week 2 |
| M2 | m2_hw1 (HelperBot) | Week 4 | ❌ Needs assignment |
| M2 | bad-bot-gallery.md | Week 4 resource | ✅ Available for use |
| M3 | m3_hw1 (Better Bot) | Week 5 | ❌ Needs assignment |
| M3 | Good Bot PDF | Week 5 reference | ✅ Available for use |
| M4 | m4_assign1 (Research Ideation) | Week 7 | ❌ Needs assignment |
| M5 | m5_homework1 (Quick Prototype) | Week 9 | ❌ Needs assignment |
| M6/M8 | m8_project (Final Project) | Weeks 15-16 | ❌ Needs assignment |

### 3.3 Instructor Resources

| Document | Status | Notes |
|----------|--------|-------|
| CSC-113 Instructor Operations Manual | Complete | In artifacts |
| GameFAQs-Style Instructor Guide | Complete | In artifacts |
| Assessment Framework | Draft | Needs rubric formalization |
| CLAUDE.md (Claude Code instructions) | Complete | Primary development guide |

### 3.4 Technical Documentation

| Document | Status | Notes |
|----------|--------|-------|
| SAGE MVP Project Summary | Complete | Technical reference |
| Gemini Model Selection Guide | Complete | Tool guidance |
| Free AI Tools Research | Complete | Platform comparison |
| Bad Bot Gallery | Complete | `/artifacts/from_canvas/m2/bad-bot-gallery.md` |

---

## 4. Gap Analysis Summary

### Assignments Ready for Student Use
| Week | Assignment | Quality |
|------|-----------|---------|
| 1 | Hello GitHub | High - follows all standards |
| 2 | Meet Kevin & SAGE | High - dual track support |
| 3 | AI Timeline Research | High - research methodology |
| 6 | Holiday Shopping Research | High - practical application |

**Total Complete: 4 of 16 weeks (25%)**

### Assignments Needing Creation (Priority Order)

**Tier 1: Critical Path (Weeks 4-5)**
These are core assignments that define the course's "Bad Bot → Good Bot" arc:

1. **Week 4: Bad Bot** - HIGH PRIORITY
   - Source: Canvas m2_hw1, bad-bot-gallery.md
   - Purpose: Learn AI design by creating intentionally flawed bots
   - Deliverables: System prompt, testing, reflection

2. **Week 5: Good Bot** - HIGH PRIORITY
   - Source: Canvas m3_hw1, Good Bot PDF
   - Purpose: Iterate on Bad Bot to create useful assistant
   - Deliverables: Improved prompt, comparison, documentation

**Tier 2: Project Foundation (Weeks 7-9)**
These prepare students for capstone work:

3. **Week 7: Project Ideation** - MEDIUM PRIORITY
   - Source: Canvas m4_assign1 (comprehensive)
   - Purpose: Brainstorm 3+ project ideas
   - Deliverables: Ideas, rationale, scope assessment

4. **Week 8: Track Specialization** - MEDIUM PRIORITY
   - Purpose: Formalize Code Builders vs Prompt Masters
   - Deliverables: Track selection, initial exploration

5. **Week 9: Rapid Prototype** - MEDIUM PRIORITY
   - Source: Canvas m5_homework1 (very detailed)
   - Purpose: Build MVP using PRD methodology
   - Deliverables: PRD, working prototype, testing docs

**Tier 3: Sprint Phase (Weeks 10-14)**
These support project development:

6. **Week 10: Project Planning** - LOW PRIORITY
7. **Weeks 11-14: Sprint Assignments** - LOW PRIORITY

**Tier 4: Capstone (Weeks 15-16)**
8. **Weeks 15-16: Final Project & Presentation** - LOW PRIORITY
   - Source: Canvas m8_project

---

## 5. Recommended Development Sequence

### Sprint 1: Complete Core Arc (Immediate)
- [ ] Week 4: Bad Bot assignment
- [ ] Week 5: Good Bot assignment

### Sprint 2: Project Foundation (Next)
- [ ] Week 7: Project Ideation assignment
- [ ] Week 8: Track Specialization assignment
- [ ] Week 9: Rapid Prototype assignment

### Sprint 3: Project Phase (Later)
- [ ] Weeks 10-14: Sprint templates
- [ ] Weeks 15-16: Capstone materials

---

## 6. Resource Reuse from Canvas Imports

| Canvas Source | Reusable Content | Target Assignment |
|---------------|------------------|-------------------|
| bad-bot-gallery.md | Complete bot personas with prompts | Week 4 examples |
| m4_assign1 | Full ideation instructions, examples | Week 7 structure |
| m5_homework1 | PRD methodology, prototyping process | Week 9 framework |
| m8_project | Final submission requirements | Week 15-16 structure |

---

## 7. Quality Standards Checklist

Every assignment must include:
- [ ] Header with due date, points, submission method
- [ ] Learning objectives (3-5 measurable)
- [ ] Step-by-step instructions
- [ ] GitHub workflow integration
- [ ] Track differentiation (Code Builders / Prompt Masters)
- [ ] 4-category assessment rubric
- [ ] Common mistakes & troubleshooting
- [ ] Getting help section
- [ ] Looking ahead preview
- [ ] Final checklist

---

## 8. Notes for Development

### Key Pedagogical Elements to Maintain
- "Failure is just exercise" philosophy
- GitHub-first workflow always
- Process over product documentation
- Both tracks equally rigorous
- Rate limits as teaching moments

### Canvas Content Adaptation Notes
- Canvas content is more casual/brief than our template
- Need to expand with full rubrics and checklists
- Integrate dual-track support throughout
- Add GitHub workflow explicitly

---

*Document maintained for course development tracking*
*Last Updated: 2026-01-01*
