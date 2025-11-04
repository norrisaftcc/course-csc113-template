# CSC-113 AI Fundamentals: Instructor Operations Manual
## "Failure is Just Exercise" - The GitHub-First Course Implementation Guide

### Manual Overview
This is your practical handbook for running CSC-113. Everything you need to set up, manage, and troubleshoot the course. When things break (and they will), this is your playbook.

---

## Pre-Semester Setup (2 weeks before)

### Week -2: GitHub Infrastructure Setup

**Day 1: Create GitHub Organization**
```bash
# Actions Required:
□ Create GitHub organization: "csc113-[semester]-[year]"
□ Enable GitHub Education benefits
□ Set organization visibility to Private
□ Configure member permissions: Write access for students
□ Enable Issues, Discussions, and Projects for all repos
```

**Day 2: Template Repository Creation**
```bash
# Create these template repositories:
1. "student-portfolio-template"
2. "dual-assistant-template" 
3. "weekly-retrospective-template"
4. "peer-review-template"

# Each template needs:
□ README with clear instructions
□ Issue templates for common tasks
□ PR template with required sections
□ .gitignore for common files
□ Basic folder structure
```

**Day 3: Protection Rules Setup**
```bash
# For ALL repositories in organization:
□ Protect main branch (require PR reviews)
□ Require up-to-date branches before merging
□ Require Issue linking for PRs
□ Enable automatic branch deletion after merge
□ Set up basic status checks
```

### Week -1: Course Materials & Backups

**Day 1: AI Tool Account Setup**
```bash
□ Test Gemini Flash access and rate limits
□ Create "Kevin from IT" prompt templates
□ Set up backup AI tools (Claude, ChatGPT accounts)
□ Document API keys and access methods
□ Create instructor prompt library
```

**Day 2: Community Partner Outreach**
```bash
□ Contact 3-5 local businesses/nonprofits
□ Explain student project timeline (Weeks 7-8)
□ Get written agreement for collaboration
□ Create partner contact spreadsheet
□ Schedule Week 6 guest speaker sessions
```

**Day 3: Survival Guide Deployment**
```bash
□ Host survivors guide on GitHub Pages
□ Test all links and functionality
□ Share link in course materials
□ Create bookmark-friendly short URL
□ Set up analytics to track usage
```

---

## Week 1: Launch Operations

### Day 1: "Hello, Scholars!" Setup
**Morning Class (Setup Focus)**
```bash
# Your Actions:
□ GitHub organization invites sent to all students
□ Live demo: Creating first repository
□ Walk through Issue creation process
□ Show branch creation and basic workflow
□ Distribute GitHub username collection sheet

# Student Actions Checklist:
□ Accept GitHub organization invite
□ Create first repository: "my-ai-assistants"
□ Create Issue #1: "Feature: Administrative Assistant"
□ Create branch: "1-admin-assistant"
□ Edit README with personal introduction
```

**Your Monitoring Dashboard:**
- Check organization member count (all students joined?)
- Monitor first Issues created (are they following template?)
- Watch for early blockers in GitHub Discussions

### Day 2-3: Daily Standup Routine
**Every Class Starts With (5 minutes):**
```bash
# Instructor-Led Standup Format:
"Quick check-in, 30 seconds each:
- What did you complete since last class?
- What are you working on today?
- Any blockers or confusion?"

# Your Notes Template:
Student | Completed | Working On | Blockers
--------|-----------|------------|----------
[Name]  | [task]    | [task]     | [issue]
```

**Your Intervention Triggers:**
- Student reports same blocker 2 days in a row → Direct help
- No commits for 24+ hours → Check in privately  
- Generic/vague reports → Ask for specifics
- Multiple students same blocker → Address in class

### Day 4: First PR Reviews
**Your Role in Review Process:**
```bash
# Before Class:
□ Review all submitted PRs for completion
□ Check that PRs link to Issues properly
□ Note common problems for class discussion
□ Prepare examples of good vs poor documentation

# During Class:
□ Assign peer review pairs randomly
□ Walk through review checklist together
□ Monitor review quality and helpfulness
□ Address any review conflicts or confusion

# After Class:
□ Approve PRs that meet basic standards
□ Leave specific feedback on incomplete work
□ Update grade tracking with completion status
```

---

## Week 2: Deep Assistant & Comparison

### Your Quality Assurance Process
**Daily Monitoring Routine:**
```bash
# GitHub Organization Dashboard Check:
□ How many active branches today?
□ Any broken or abandoned branches? (Delete them)
□ PR queue length and review status
□ Issue completion rates by student
□ Commit message quality trends

# Red Flags to Watch For:
- Empty commits or "fix" messages
- No test results documented
- PRs without linked Issues
- Students not participating in reviews
```

### Crisis Intervention Protocols
**When Students Break Things:**
```bash
# Standard Response: "Let's Start Fresh"
1. "Don't panic - this happens to everyone"
2. "Let's delete that branch and try again"
3. "What did you learn from what broke?"
4. Help them create new branch from main
5. Document the learning in retrospective

# Never Say:
- "You should have been more careful"
- "Git is complicated" 
- "This is why we have backups"

# Always Say:
- "This is normal in professional development"
- "Failure is just exercise - let's iterate"
- "What would you do differently next time?"
```

---

## Weeks 3-6: Path Specialization Management

### Track Management System
**Your Organization Strategy:**
```bash
# Create Path-Specific Resources:
□ "prompt-masters" team in GitHub org
□ "code-builders" team in GitHub org  
□ Separate Slack/Discord channels per path
□ Path-specific office hours schedule
□ Cross-pollination project assignment matrix

# Weekly Path Check-ins:
- Monday: Prompt Masters progress review
- Wednesday: Code Builders technical support
- Friday: Cross-path collaboration planning
```

### Community Partner Coordination
**Your Project Management Role:**
```bash
# Week 4: Partner Matching
□ Student team formation based on interests
□ Partner needs assessment and matching
□ Initial stakeholder meeting scheduling
□ Project scope definition workshops

# Week 5: Progress Monitoring  
□ Weekly partner check-in calls
□ Student progress reports via GitHub Issues
□ Scope creep intervention as needed
□ Mid-project pivot support if required

# Week 6: Delivery Preparation
□ Final demo format planning
□ Partner presentation logistics
□ Student presentation coaching
□ Backup plans for technical difficulties
```

---

## Weeks 7-8: Capstone & Assessment

### Portfolio Review Process
**Your Assessment Workflow:**
```bash
# GitHub Portfolio Evaluation:
□ README professionalism and clarity
□ Commit history showing consistent progress
□ Issue tracking demonstrating project management
□ PR reviews showing collaborative skills
□ Documentation quality throughout projects

# Rubric Application Process:
1. Open student's GitHub profile
2. Review pinned repositories
3. Check contribution activity graph
4. Read through key PRs and Issues
5. Assess against 4-category framework
6. Provide specific feedback with examples
```

### Final Presentation Management
**Your Event Coordination:**
```bash
# Week Before Presentations:
□ Confirm community partner attendance
□ Test all demo technology setups
□ Create presentation order and timing
□ Prepare backup internet/equipment
□ Brief partners on evaluation process

# Presentation Day:
□ 10-minute tech checks before class
□ Introduce partners and evaluation process
□ Maintain strict 7-minute presentation limit
□ Facilitate Q&A and networking time
□ Collect partner feedback forms
□ Document outstanding student work
```

---

## Daily Operations Playbook

### Morning Routine (15 minutes)
```bash
□ Check GitHub notification feed
□ Review overnight commit activity
□ Scan for new Issues or blocked students
□ Prepare daily standup agenda
□ Update intervention tracking spreadsheet
```

### Class Period Management
```bash
# First 5 minutes: Standup
# Next 20 minutes: Concept/Demo
# Remaining time: Student work with circulation
# Last 5 minutes: Next class preview

# During Student Work Time:
- Circulate every 10 minutes
- Check GitHub activity on your phone
- Intervene before frustration builds
- Connect students with similar challenges
```

### End-of-Day Wrap (10 minutes)
```bash
□ Review and approve completed PRs
□ Leave feedback on incomplete work
□ Update student progress tracking
□ Note successful patterns and problems
□ Plan tomorrow's focus areas
```

---

## Crisis Management Protocols

### Technology Failure Responses

**GitHub Down/Slow:**
```bash
# Immediate Actions:
1. Check status.github.com for official updates
2. Switch to local Git demo if possible
3. Use downtime for prompt engineering workshop
4. Document work in alternative format
5. Resume GitHub work when service returns

# Never Panic - Students Follow Your Lead
```

**AI Service Interruptions:**
```bash
# Gemini Flash Issues:
1. Switch to backup AI service (Claude/ChatGPT)
2. Demonstrate prompt adaptation across platforms
3. Turn into "tool flexibility" learning moment
4. Update Kevin prompts for alternative service
5. Continue with adjusted workflow
```

**Student Device/Internet Problems:**
```bash
# Immediate Support:
1. Pair student with working setup
2. Use phone hotspot if available
3. Switch to pen-and-paper planning
4. Assign note-taking/documentation role
5. Follow up with technical support referral
```

### Academic Resistance Management

**"This Isn't Real Learning" Complaints:**
```bash
# Your Response Framework:
1. Show GitHub portfolios from previous students
2. Share employer feedback on graduate preparedness  
3. Demonstrate transferable skills development
4. Connect to industry workflow practices
5. Invite skeptic to observe student presentations

# Document Everything - Build Evidence Base
```

**Student Resistance to Process:**
```bash
# "Can't I just skip GitHub and submit normally?"
Response: "GitHub IS how professionals submit work. 
We're learning industry standards, not academic exercises."

# "This is too much overhead for simple assignments"
Response: "Simple assignments become complex in teams. 
We're building collaboration skills that scale."
```

---

## Assessment Operations

### GitHub-Based Grading Workflow
```bash
# Weekly Assessment Routine:
□ Review all student repositories
□ Check Issue completion and quality
□ Evaluate commit message progression
□ Assess PR review participation
□ Update competency tracking spreadsheet

# Evidence Collection:
- Screenshot key GitHub activities
- Save exemplar student work
- Document learning progression
- Track collaboration quality metrics
```

### Peer Review Quality Control
```bash
# Your Monitoring Process:
□ Read all peer review comments
□ Identify helpful vs unhelpful feedback patterns
□ Coach students on constructive review techniques
□ Address any inappropriate or mean comments
□ Recognize excellent reviewers publicly

# Intervention Triggers:
- Generic "looks good" reviews → Review training
- Harsh or unconstructive criticism → Private coaching
- No review participation → Direct requirement
```

---

## Weekly Instructor Checklist

### Sunday Planning (30 minutes)
```bash
□ Review upcoming week's learning objectives
□ Check GitHub activity from previous week
□ Identify students needing extra support
□ Prepare community partner communications
□ Update course materials based on student feedback
```

### Wednesday Progress Check (20 minutes)
```bash
□ Mid-week GitHub repository review
□ Student progress vs timeline assessment
□ Upcoming assignment preparation review
□ Community partner project status check
□ Adjust week 2 plans based on student needs
```

### Friday Wrap-Up (25 minutes)
```bash
□ Week completion assessment
□ Student retrospective review and synthesis
□ Plan weekend GitHub monitoring
□ Prepare next week's materials
□ Update semester progress tracking
```

---

## Troubleshooting Quick Reference

### Common Student Problems & Solutions

**"I can't find my branch"**
```bash
Solution: Check GitHub web interface → branches tab
If still missing: create new branch, start fresh
Learning moment: why branches matter
```

**"My PR won't merge"**
```bash
Check: Is main branch updated?
Check: Are there merge conflicts?
Solution: Delete branch, start from current main
Teaching moment: why we sync frequently
```

**"Kevin from IT isn't helping"**
```bash
Check: Are they using the proper handoff format?
Solution: Show them the note template again
Advanced: Try different AI service
Meta-moment: AI tool flexibility
```

**"My assistant isn't working"**
```bash
Diagnosis: Check their prompt iterations
Solution: Pair them with successful student
Process: Document what they tried
Learning: Iteration is the key skill
```

---

## Success Metrics & Tracking

### Daily Indicators
```bash
□ GitHub commit activity levels
□ Issue creation and completion rates
□ Student help-seeking patterns
□ Peer review participation quality
□ Class engagement and attendance
```

### Weekly Outcomes
```bash
□ Feature completion percentages
□ Portfolio quality progression
□ Collaboration skill development
□ Professional communication improvement
□ AI literacy demonstration
```

### Semester Goals
```bash
□ 100% students with professional GitHub portfolios
□ Successful community partner project completion
□ Demonstrated AI collaboration competency
□ Transferable professional workflow skills
□ Industry-ready presentation abilities
```

---

## Emergency Contacts & Resources

### Technical Support Chain
```bash
1. Kevin from IT (GitHub Copilot)
2. Campus IT Help Desk
3. GitHub Education Support
4. Instructor peer network
5. Course designer/consultant
```

### Community Partner Issues
```bash
1. Direct partner communication
2. Alternative partner activation
3. Pivot to internal project
4. Cross-team collaboration
5. Individual capstone option
```

### Student Crisis Support
```bash
1. Academic advisor referral
2. Counseling services
3. Financial aid office
4. Accessibility services
5. Student success center
```

---

## End-of-Semester Operations

### Portfolio Archival Process
```bash
□ Export all student repositories
□ Create course completion certificates
□ Document best practices and lessons learned
□ Collect employer feedback on graduates
□ Prepare materials for next semester iteration
```

### Continuous Improvement Cycle
```bash
□ Student feedback synthesis
□ Community partner evaluation
□ Instructor reflection documentation
□ Technology tool assessment
□ Curriculum refinement planning
```

---

**Remember:** Your job isn't to be the Git expert or AI specialist. Your job is to facilitate professional learning experiences where failure becomes iteration and students develop genuine competency through authentic practice.

**When in doubt:** Delete the branch and start again. Failure is just exercise.

---

## Assignment Mapping

This operations manual supports the following assignments:

- **Week 1: Hello GitHub** - Pre-semester setup, Day 1 launch, GitHub infrastructure
- **Week 2: Meet Kevin & SAGE** - Daily standup routine, AI tool setup, quality assurance
- **Week 3: AI Timeline Research** - Progress monitoring, peer review protocols
- **Weeks 4-6: Bot Development & Specialization** - Track management, differentiation support
- **Weeks 7-8: Community Projects** - Partner coordination, capstone management
- **Weeks 9-16: Project Sprints** - Ongoing operations, assessment, final presentations

---

*Version: 1.0*  
*Last Updated: November 4, 2025*  
*Related Documents: operations-manual-gamefaqs.md, assessment-rubrics.md*
