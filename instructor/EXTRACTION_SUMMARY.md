# Instructor Guide Extraction Summary
## CSC-113 Course Template Repository Organization

**Date:** November 4, 2025  
**Task:** Extract instructor operations guides from project documents and organize into course template repository

---

## ✅ Completed Actions

### 1. Created Instructor Directory
**Location:** `/Users/norrisa/Documents/dev/github/course-csc113-template/instructor/`

Created the instructor materials directory as specified in CLAUDE.md structure requirements.

### 2. Extracted and Organized Instructor Guides

**Three documents created:**

#### A. operations-manual.md
- **Source:** Document index 8, 17, 18 from project files
- **Format:** Professional, formal instructor handbook
- **Content:** Complete operations guide from pre-semester through post-semester
- **Length:** ~15,000 words
- **Best for:** Official documentation, institutional requirements

#### B. operations-manual-gamefaqs.md  
- **Source:** Document index 7, 16 from project files
- **Format:** GameFAQs-style gaming guide (ASCII art, speedrun strategies, boss fights)
- **Content:** Same operational guidance as formal manual, presented with humor
- **Length:** ~12,000 words
- **Best for:** First-time instructors, approachable format, maintaining morale

#### C. README.md
- **Purpose:** Directory orientation and navigation guide
- **Content:** 
  - Overview of both manuals
  - Quick reference guides
  - Assignment mapping table
  - Crisis protocol summaries
  - Getting started checklist

---

## 📋 Assignment Mapping

Both manuals contain specific guidance for:

| Week(s) | Assignment | Manual Coverage |
|---------|-----------|-----------------|
| Pre-semester | Setup | GitHub org creation, AI tools, community partners |
| Week 1 | Hello GitHub | Tutorial level, first day ceremony, GitHub initiation |
| Week 2 | Meet Kevin & SAGE | Daily standup, AI setup, quality assurance |
| Week 3 | AI Timeline | Progress monitoring, peer review protocols |
| Weeks 4-6 | Bot Development | Track management, specialization support |
| Weeks 7-8 | Community Projects | Partner coordination, capstone management |
| Weeks 9-16 | Sprints | Ongoing operations, assessment, presentations |

---

## 🎯 Key Features of Extracted Guides

### Comprehensive Coverage
- **Pre-semester setup:** 2-week checklist with daily tasks
- **Week-by-week guidance:** Specific operations for each course phase
- **Daily operations:** Morning routines, class management, evening wrap-up
- **Crisis management:** Protocols for common failures and edge cases
- **Assessment operations:** GitHub-based grading workflows, rubric application

### Pedagogical Philosophy Integration
- "Failure is Just Exercise" mindset throughout
- GitHub-first workflow emphasis
- Second-order skills focus (documentation, resilience, critical thinking)
- Progressive branching model (Prompt Masters / Code Builders)
- Process-over-product assessment

### Practical Implementation Details
- **Checklists:** Pre-flight lists for every major operation
- **Time estimates:** Realistic time budgets for instructor tasks
- **Troubleshooting:** Common problems with solutions
- **Code examples:** Copy-pasteable templates and scripts
- **Emergency protocols:** What to do when everything breaks

---

## 📁 Repository Structure After Extraction

```
course-csc113-template/
├── CLAUDE.md                    # Instructions for Claude Code instances
├── README.md                    # Repository overview
├── artifacts/                   # Legacy/reference materials
├── assignments/                 # Student-facing assignments
├── guides/                      # Student support materials (to be created)
├── instructor/                  # ✨ NEW - Instructor materials
│   ├── README.md               # Directory navigation guide
│   ├── operations-manual.md    # Professional format operations guide
│   └── operations-manual-gamefaqs.md  # Alternative format guide
├── templates/                   # Reusable templates (to be created)
└── outline/                     # Course structure
```

---

## 🔍 Document Analysis

### Original Source Documents Reviewed
From the project files provided, identified relevant instructor guides:

1. **CSC-113 Instructor Operations Manual.md** (appeared 3 times)
   - Index 8, 17, 18 in project documents
   - Formal, professional format
   - Comprehensive operational guidance

2. **CSC-113 AI Fundamentals - Instructor Operations Manual (GameFAQs Style).md** (appeared 2 times)
   - Index 7, 16 in project documents  
   - Gaming-themed presentation
   - Same content, different tone

### Deduplication Strategy
- Multiple copies of same documents were consolidated
- Version with most complete content selected
- Both format styles preserved (formal and GameFAQs)

### Content Preservation
- No substantive content was altered
- Original pedagogical philosophy maintained
- All practical guidance preserved
- Assignment mappings clarified

---

## 🎓 Pedagogical Elements Preserved

### Core Mantras
- "Hello, Scholars!" - Respectful opening
- "Failure is just exercise. Delete the branch and try again."
- "The GitHub contribution graph IS your grade."
- "We're not teaching them to code. We're teaching them to learn."
- "Kevin from IT never judges your code."

### Critical Teaching Moments
- **Rate limits as pedagogy** - Not a bug, a feature
- **Non-programmers = equals** - Different methods, same rigor
- **GitHub disasters = learning** - Normalize mistakes
- **Community partners** - Real-world projects build confidence
- **Portfolio building** - Professional artifacts from day one

### Assessment Framework (4 categories)
1. AI Partnership Quality (25%)
2. Problem-Solving Process (25%)
3. Professional Communication (25%)
4. Critical Thinking & Ethics (25%)

---

## 📊 Metrics and Quick Stats

### Manual Coverage
- **Total weeks covered:** 16 (Pre-semester through post-semester)
- **Crisis protocols:** 4 major scenarios documented
- **Daily operations checklists:** 3 (morning, class, evening)
- **Assessment workflows:** GitHub-based portfolio evaluation
- **Time budgets:** Realistic estimates for all instructor tasks

### Assignment Integration
- **Fully mapped assignments:** 8+ weeks of specific guidance
- **Track differentiation:** Support for both Prompt Masters and Code Builders
- **Community integration:** Partner coordination and presentation management

---

## 🚀 Next Steps for Course Development

### Still Needed (per CLAUDE.md)
Based on repository analysis, these items remain to be created:

**Priority 1 - Instructor Materials:**
- [ ] assessment-rubrics.md - Detailed rubrics for all assignments
- [ ] example-submissions/ - A/B/C quality examples for each assignment
  
**Priority 2 - Student Support:**
- [ ] guides/github-survival-guide.md
- [ ] guides/ai-tools-getting-started.md
- [ ] guides/troubleshooting-faq.md

**Priority 3 - Templates:**
- [ ] templates/assignment-template.md
- [ ] templates/pr-template.md
- [ ] templates/reflection-template.md

**Priority 4 - Assignments:**
- [ ] Week 6: Holiday Shopping (needs creation)
- [ ] Week 8: No-Code AI Agent (Prompt Masters - needs creation)
- [ ] Week 9: Community Kickoff (needs student-facing materials)
- [ ] Week 10: Project Planning (needs creation)

---

## 💡 Usage Recommendations

### For Instructors

**First-time teaching this course:**
1. Read operations-manual.md or operations-manual-gamefaqs.md completely (your choice of format)
2. Follow pre-semester setup checklist 2 weeks before launch
3. Keep crisis protocols bookmarked
4. Reference assignment mapping for week-specific guidance

**Experienced with course:**
- Use as reference for specific situations
- Check crisis protocols for edge cases
- Review assessment frameworks when needed

### For Claude Code Instances

**When working on instructor materials:**
- Reference these manuals for pedagogical consistency
- Check assignment mapping to understand which operations guide which weeks
- Use manuals as templates for creating additional instructor resources
- Maintain the established tone and philosophy

**When creating student-facing assignments:**
- Ensure assignments align with operations manual expectations
- Consider what instructor support each assignment requires
- Map new assignments to appropriate manual sections

---

## 🔗 Related Documentation

### In This Repository
- `/CLAUDE.md` - Complete instructions for Claude Code development
- `/artifacts/` - Original course philosophy documents
- `/outline/` - 16-week course structure

### External References
As noted in project documents:
- AI4K12 framework (Five Big Ideas)
- Community college implementation examples (Maricopa, Houston)
- GitHub Education resources
- Gemini 2.5 model documentation

---

## ✨ Quality Assurance

### Verification Checklist
- [x] Both manual formats extracted and saved
- [x] Directory structure matches CLAUDE.md specifications
- [x] Assignment mapping documented
- [x] README created for navigation
- [x] Pedagogical philosophy preserved
- [x] All crisis protocols included
- [x] Assessment frameworks maintained
- [x] No content lost from original documents

### File Integrity
- operations-manual.md: ✅ Complete, formatted, ready to use
- operations-manual-gamefaqs.md: ✅ Complete, formatted, ready to use
- README.md: ✅ Navigation guide complete

---

## 📞 Support Information

### If You Find Issues
- Check against original documents in artifacts/
- Reference CLAUDE.md for intended structure
- Create GitHub Issue for clarification
- Document discrepancies for future updates

### If Adding New Content
- Follow patterns established in these manuals
- Maintain pedagogical philosophy consistency
- Update assignment mapping tables
- Cross-reference with CLAUDE.md standards

---

## 🎯 Success Criteria Met

✅ **Instructor guides extracted** from project documents  
✅ **Organized into proper directory** structure per CLAUDE.md  
✅ **Assignment mapping documented** for easy reference  
✅ **Both format styles preserved** (formal and GameFAQs)  
✅ **Navigation guide created** for directory orientation  
✅ **Pedagogical philosophy maintained** throughout  
✅ **Ready for Claude Code** to continue development work  

---

**Status:** Complete and ready for use  
**Location:** `/instructor/` directory in course template repository  
**Next Actions:** Use as reference for creating assessment rubrics and example submissions

---

*"Failure is just exercise. Delete the branch and try again."*
