# CSC-113 Course Content Audit
## Assessment of Existing Materials and Gaps

### Date: November 4, 2025
### Purpose: Inventory what exists, identify what's needed, plan integration

---

## EXECUTIVE SUMMARY

**Current State:**
- Strong foundational philosophy and instructor guidance (80% complete)
- Week 1 and Weeks 7-8 are well-defined (75% complete)
- Weeks 2-6 have concepts but lack detailed assignments (40% complete)
- Assessment framework exists but needs assignment-specific rubrics (60% complete)
- Technical infrastructure well-documented (90% complete)
- Student-facing materials need development (30% complete)

**Critical Gaps:**
1. Detailed weekly assignments for Weeks 2-6
2. Module-by-module learning objectives
3. Non-programmer track specific assignments
4. Example artifacts and student work samples
5. Assignment-specific rubrics
6. Transition scaffolding from "use AI" to "build with AI"

---

## PART 1: WHAT WE HAVE (Completed or Near-Complete)

### A. Course Philosophy & Framework ✅ COMPLETE
**Documents:**
- `concept_issues_prs_first.md` - GitHub-first workflow justification
- `Designing_AI_Fundamentals` - Mixed-ability framework
- `CSC-113_Integrated_Implementation_Guide.md`

**What this gives us:**
- Core teaching philosophy ("failure is just exercise")
- Rationale for GitHub-first approach
- Progressive branching model for mixed abilities
- Professional workflow as default

**Status:** Ready to use as instructor reference

---

### B. Instructor Operations ✅ COMPLETE
**Documents:**
- `CSC-113_Instructor_Operations_Manual.md` (multiple versions)
- `GameFAQs_Style` version for readability

**What this gives us:**
- Pre-semester setup checklists
- Daily operations procedures
- Crisis management protocols
- Weekly monitoring routines
- Technology failure responses
- Student intervention triggers

**Status:** Ready for instructor use

---

### C. Assessment Framework ⚠️ 75% COMPLETE
**Documents:**
- `AI-Required_Course_Assessment_Framework_Development.md`

**What this gives us:**
- Four-category assessment model:
  1. AI Partnership Quality (25%)
  2. Problem-Solving Process (25%)
  3. Professional Communication (25%)
  4. Critical Thinking & Ethics (25%)
- Competency level definitions (Novice → Advanced)
- Portfolio-based assessment approach

**What's missing:**
- Assignment-specific rubrics
- Grading worksheets for individual tasks
- Student self-assessment templates
- Peer review rubrics tied to specific assignments

**Action needed:** Create assignment-level rubrics using the 4-category framework

---

### D. Technical Infrastructure ✅ 90% COMPLETE
**Documents:**
- `free_ai_tools_research.md`
- `Gemini_2_5_Model_Selection_Guide.md`
- `Practical_Guide_to_Googles_Free_Gemini_Tools.md`
- `Building_Custom_AI_Agents_with_HF_and_Local_Models.md`
- `PROJECT_SUMMARY.md` (SAGE MVP)
- `docker-compose.yml`

**What this gives us:**
- Tool selection rationale
- Cost optimization strategies
- Cascade routing (Flash-Lite → Flash → Pro)
- Rate limit management
- Deployment options
- SAGE assistant implementation

**What's missing:**
- Student-facing "getting started" guides
- Troubleshooting FAQs for common technical issues
- Video walkthrough scripts

**Action needed:** Create student-facing technical onboarding materials

---

### E. Week 1: GitHub Initiation ✅ 75% COMPLETE
**Documents:**
- Covered in both Instructor Operations Manuals
- Detailed in Integrated Implementation Guide

**What this gives us:**
- Day 1: "Hello, Scholars!" opening
- Live demo sequence (repo → issue → branch → PR → merge)
- Daily standup ritual establishment
- First PR review process
- Student success metrics

**What's missing:**
- Student-facing assignment sheet for Week 1
- Video or visual tutorial for non-programmers
- Checklist for students to self-assess completion

**Action needed:** Create Week 1 student assignment document

---

### F. Weeks 7-8: Capstone & Community Projects ✅ 80% COMPLETE
**Documents:**
- Covered in Instructor Operations Manuals
- Community partner coordination detailed

**What this gives us:**
- Partner matching process
- Project scope definition
- Presentation format and logistics
- Assessment criteria
- Event coordination procedures

**What's missing:**
- Student-facing capstone project guidelines
- Project proposal template
- Presentation rubric
- Partner feedback form

**Action needed:** Create capstone project package (guidelines + templates)

---

## PART 2: WHAT WE HAVE (Partially Complete - Needs Development)

### G. Week 2: SAGE Assistant Development ⚠️ 50% COMPLETE
**Documents:**
- Concept mentioned in multiple documents
- Technical implementation in PROJECT_SUMMARY.md

**What this gives us:**
- General idea: build first AI assistant
- Technical approach (if programming track)
- Rate limit management as learning opportunity

**What's missing:**
- Specific assignment prompt for both tracks
- Non-programmer version (how do they build an assistant?)
- Step-by-step instructions
- Deliverables checklist
- Grading rubric for this specific assignment
- Example good/bad submissions

**Action needed:** Create complete Week 2 assignment for both tracks

---

### H. Weeks 3-6: Specialization Tracks ⚠️ 40% COMPLETE
**Documents:**
- Conceptually described in multiple documents
- Track characteristics defined (Prompt Masters vs Code Builders)

**What this gives us:**
- General track descriptions
- Tool recommendations per track
- Community project preparation mentioned

**What's missing:**
- Weekly assignments for each track
- Clear progression through concepts
- Bad Bot → Good Bot sequence details
- Holiday shopping research challenge specifics
- Cross-track collaboration assignments
- Skill-building scaffolds

**Action needed:** Design 4 weeks of assignments (Weeks 3-6) for both tracks

---

### I. Retrospectives & Reflection ⚠️ 30% COMPLETE
**Documents:**
- Mentioned as template in Instructor Operations
- Emphasized in philosophy documents

**What this gives us:**
- Concept of weekly retrospectives
- Importance established

**What's missing:**
- Actual retrospective template
- Reflection prompts
- How reflections are assessed
- Integration with GitHub Issues

**Action needed:** Create retrospective template and assessment approach

---

### J. Peer Review System ⚠️ 40% COMPLETE
**Documents:**
- Process described in Instructor Operations
- Quality control procedures defined

**What this gives us:**
- Peer review assignment process
- Quality monitoring approach
- Intervention triggers

**What's missing:**
- Peer review rubric/checklist
- Training materials for giving good feedback
- Examples of helpful vs unhelpful reviews
- How peer review is graded

**Action needed:** Create peer review training materials and rubric

---

## PART 3: WHAT'S MISSING (Needs to Be Created)

### K. Module-by-Module Outline ❌ MISSING
**What we need:**
- 8 modules with clear learning objectives
- Week-by-week content and skills progression
- Alignment with assessment framework
- Prerequisites and dependencies
- Time estimates for each component

**Format needed:**
```
Module 1: GitHub Foundations
- Learning Objectives: [specific, measurable]
- Key Concepts: [list]
- Activities: [specific assignments]
- Assessments: [how measured]
- Resources: [materials needed]
```

---

### L. Assignment Specifications (Weeks 2-6) ❌ MOSTLY MISSING
**What we need for each assignment:**
1. Assignment prompt (student-facing)
2. Learning objectives
3. Deliverables checklist
4. Grading rubric (tied to 4-category framework)
5. Example submissions (good/okay/poor)
6. Common pitfalls and troubleshooting
7. Extension opportunities for advanced students

**Specific assignments mentioned but not detailed:**
- Week 2: SAGE Assistant (initial version)
- Week 3: Bad Bot exercise
- Week 4: Good Bot iteration
- Week 5: Holiday shopping research challenge
- Week 6: Capstone ideation and planning

---

### M. Non-Programmer Track Materials ❌ MISSING
**What we need:**
- Track-specific assignment versions
- "Upload to GitHub" visual guide
- Tool recommendations (no-code platforms)
- Success criteria that don't require coding
- Example projects from non-programmer perspective

**Philosophy is clear but execution details missing**

---

### N. Student-Facing Documentation ❌ MOSTLY MISSING
**What we need:**
1. **Course syllabus** (student version with policies)
2. **Week-by-week schedule** with due dates
3. **GitHub survival guide** for students
4. **AI tools getting started guide**
5. **Troubleshooting FAQ**
6. **Portfolio building guide**
7. **Success stories** from past students

---

### O. Example Artifacts & Exemplars ❌ MISSING
**What we need:**
- Sample GitHub portfolios (A, B, C quality)
- Example SAGE assistants
- Good vs poor commit messages
- Effective vs ineffective issue descriptions
- Strong vs weak PR reviews
- Sample capstone projects

**Purpose:** Show students what success looks like

---

### P. Prompt Engineering Curriculum ⚠️ 30% COMPLETE
**What we have:**
- General emphasis on prompt engineering
- Kevin from IT persona concept

**What's missing:**
- Systematic progression of prompt techniques
- Exercises that teach specific prompt strategies
- Prompt iteration assignments
- Comparing AI responses across tools
- Building a personal prompt library

---

## PART 4: INTEGRATION OPPORTUNITIES

### Previous Work to Retrofit:

#### 1. Bad Bot → Good Bot Progression
**Mentioned in:** concept_issues_prs_first.md
**How to integrate:** 
- Week 3 assignment: Intentionally create "bad" AI responses
- Week 4 assignment: Iterate to "good" AI responses
- Learning objective: Understanding failure as data
- Assessment: Document what made something "bad" and how to fix it

#### 2. Holiday Shopping Research Challenge
**Mentioned in:** Course overview discussions
**How to integrate:**
- Week 5 assignment: Use AI for practical task (gift research)
- Demonstrates prompt engineering in action
- Comparison shopping across AI tools
- Real-world applicability

#### 3. AI Application Brainstorming
**Mentioned in:** Capstone preparation
**How to integrate:**
- Week 6 assignment: Capstone ideation
- Use AI to help generate and evaluate project ideas
- Document the ideation process
- Creates bridge to Weeks 7-8

#### 4. Rogues Gallery of Bots
**Mentioned in:** Various documents
**How to integrate:**
- Ongoing collection throughout semester
- Students contribute examples of interesting AI behavior
- Class resource for understanding AI capabilities/limitations
- Could be Week 3-4 mini-assignment

---

## PART 5: PRIORITIZED ACTION ITEMS

### IMMEDIATE PRIORITIES (Start Here)

**Priority 1: Create Module Outline**
- [ ] Draft 8-module structure
- [ ] Define learning objectives per module
- [ ] Map to assessment framework
- [ ] Identify which modules are "complete" vs "need work"
- [ ] **Deliverable:** "CSC-113_Course_Outline.md"

**Priority 2: Complete Week 2 Assignment**
- [ ] Write student-facing assignment prompt
- [ ] Create both track versions (programmer/non-programmer)
- [ ] Develop grading rubric
- [ ] List technical requirements and tools
- [ ] **Deliverable:** "Week_2_SAGE_Assistant_Assignment.md"

**Priority 3: Design Weeks 3-6 Assignments**
- [ ] Specify Bad Bot (Week 3)
- [ ] Specify Good Bot (Week 4)
- [ ] Specify Holiday Shopping Challenge (Week 5)
- [ ] Specify Capstone Ideation (Week 6)
- [ ] **Deliverable:** Four assignment documents

### SECONDARY PRIORITIES (After Immediate)

**Priority 4: Student Documentation Suite**
- [ ] Create student syllabus
- [ ] Write GitHub survival guide
- [ ] Develop AI tools getting started guide
- [ ] Build troubleshooting FAQ
- [ ] **Deliverable:** Student documentation package

**Priority 5: Assessment Materials**
- [ ] Create assignment-specific rubrics
- [ ] Develop peer review training
- [ ] Build example artifacts
- [ ] Write self-assessment templates
- [ ] **Deliverable:** Assessment toolkit

**Priority 6: Non-Programmer Track Details**
- [ ] Adapt all assignments for no-code approach
- [ ] Create visual GitHub guides
- [ ] Identify no-code tool recommendations
- [ ] Develop track-specific success criteria
- [ ] **Deliverable:** Non-programmer track supplement

### ONGOING WORK (Throughout Development)

**Collect Example Artifacts**
- As we design assignments, create example submissions
- Build library of good/okay/poor work samples
- Document common student mistakes

**Test and Refine**
- Review assignments for clarity
- Check alignment with assessment framework
- Verify time estimates are realistic
- Ensure both tracks are equally rigorous

---

## PART 6: PROPOSED WORKFLOW

### Phase 1: Outline and Structure (Week 1)
1. Create detailed module outline
2. Map learning objectives to assessments
3. Verify progression and scaffolding
4. Identify dependencies between modules

### Phase 2: Assignment Development (Weeks 2-3)
1. Complete Week 2 assignment
2. Draft Weeks 3-6 assignments
3. Create assignment rubrics
4. Develop both track versions

### Phase 3: Student Materials (Week 4)
1. Write student-facing documentation
2. Create GitHub and AI tools guides
3. Build troubleshooting FAQ
4. Collect/create example artifacts

### Phase 4: Refinement and Testing (Week 5)
1. Review all materials for coherence
2. Check alignment across documents
3. Verify both tracks are equally supported
4. Test assignment clarity with outside reader

---

## PART 7: QUESTIONS TO RESOLVE

### Curriculum Design Questions:
1. **How much AI theory vs. practice?**
   - Current emphasis is heavily practical
   - Should we add "how AI works" content?
   - Where does ethics fit specifically?

2. **How do tracks stay aligned?**
   - Same learning objectives, different implementations?
   - How do we ensure non-programmers aren't "lesser"?
   - Can tracks collaborate or must they stay separate?

3. **What's the minimum viable product for assignments?**
   - How detailed should instructions be?
   - How much scaffolding vs. discovery learning?
   - What's appropriate challenge level?

4. **How prescriptive vs. open-ended?**
   - Weeks 1-2 seem prescriptive (good)
   - Weeks 3-6 could be more open?
   - Week 7-8 is student-driven
   - Is this the right balance?

### Assessment Questions:
1. **How do we handle the GitHub activity as grade data?**
   - Commits, PRs, issues all provide evidence
   - How much weight on quantity vs. quality?
   - How to prevent gaming the system?

2. **What percentage of grade is process vs. product?**
   - Current philosophy emphasizes process
   - But community partners care about product
   - How do we balance?

3. **How do we grade AI collaboration specifically?**
   - We have framework (25% of grade)
   - But what does "excellent AI partnership" look like at Week 2 vs Week 8?
   - Need progression markers

### Implementation Questions:
1. **How do we support non-programmers meaningfully?**
   - They can't/shouldn't use APIs
   - No-code tools change rapidly
   - How do we keep their work equivalent but appropriate?

2. **What happens when AI tools change mid-semester?**
   - Gemini updates, rate limits change, new tools emerge
   - How do we build flexibility into assignments?
   - Backup plans needed?

3. **How do we manage community partner expectations?**
   - They may expect more polish than students can deliver
   - Need clear scope from the start
   - What if partnership falls through?

---

## PART 8: NEXT STEPS

### Immediate Next Actions:
1. **Review this audit** - Confirm assessment is accurate
2. **Prioritize gaps** - Which ones block others?
3. **Create outline** - Start with module structure
4. **Draft Week 2** - Complete one assignment fully as template
5. **Schedule design sessions** - Map out Weeks 3-6

### Success Criteria:
- ✅ Complete module-by-module outline exists
- ✅ All assignments (Weeks 1-8) have student-facing documents
- ✅ Both tracks have equivalent materials
- ✅ Assessment framework connects to specific assignments
- ✅ Example artifacts demonstrate expectations
- ✅ Student documentation supports independent work

---

## NOTES & OBSERVATIONS

### Strengths of Current Materials:
1. **Clear philosophy** - The "why" is very strong
2. **Instructor support** - Detailed operational guidance
3. **Assessment framework** - Solid foundation
4. **Technical infrastructure** - Well-researched tool choices
5. **Real-world connection** - Community partners, GitHub, professional workflows

### Areas Needing Attention:
1. **Student perspective** - Most materials are instructor-facing
2. **Granularity** - Need to move from concepts to specific tasks
3. **Examples** - Abstract descriptions need concrete instantiation
4. **Non-programmer equity** - Track needs equal detail/support
5. **Progressive complexity** - Need to show skill building over time

### Philosophical Tensions to Resolve:
- **Scaffolding vs. Discovery:** How much do we guide vs. let them explore?
- **Process vs. Product:** Both matter, but which matters more when?
- **Individual vs. Collaborative:** GitHub emphasizes collaboration; how do we assess individuals?
- **AI as Tool vs. AI as Teacher:** Are we teaching them to use AI or to build AI?

---

## APPENDIX: DOCUMENT MAP

### Where to Find What:

**Course Philosophy:**
- concept_issues_prs_first.md
- Designing_AI_Fundamentals...mixed-ability.md

**Instructor Operations:**
- CSC-113_Instructor_Operations_Manual.md (standard)
- CSC-113_Instructor_Operations_Manual_GameFAQs.md (accessible)
- CSC-113_Integrated_Implementation_Guide.md (combined)

**Assessment:**
- AI-Required_Course_Assessment_Framework_Development.md

**Technical Setup:**
- free_ai_tools_research.md
- Gemini_2_5_Model_Selection_Guide.md
- Practical_Guide_to_Googles_Free_Gemini_Tools.md
- Building_Custom_AI_Agents_with_HF_and_Local_Models.md

**SAGE Project:**
- PROJECT_SUMMARY.md
- docker-compose.yml

**Syllabus (brief):**
- syllabus_mvp

---

**End of Audit**
**Next Action:** Confirm priorities and begin Phase 1 (Outline and Structure)
