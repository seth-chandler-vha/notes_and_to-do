# Notes and To-Do

Personal knowledge management system and task tracking repository using the PARA method from Building a Second Brain (BASB). This serves as a centralized workspace for project notes, task lists, and reference materials.

## Repository Structure

```
notes_and_to-do/
├── projects/          # Active project documentation
├── areas/             # Ongoing responsibilities and domains
├── resources/         # Reference materials and guides
├── archive/           # Completed or inactive items
├── templates/         # Note and document templates
└── to-do/            # Task lists and action items
```

## The PARA Method (Building a Second Brain)

### Overview
PARA is a universal system for organizing digital information, created by Tiago Forte. It stands for Projects, Areas, Resources, and Archive. This method emphasizes actionability and ensures that information is organized by when you need to use it, not where it came from.

### Core Principles

1. **Action-Oriented**: Information is organized by how actionable it is
2. **Project-Centric**: Active work is separated from long-term responsibilities
3. **Just-In-Time**: Resources are organized for when they're needed
4. **Regular Maintenance**: Completed work flows naturally to the archive

### The Four Categories Explained

#### 1. Projects (`/projects`)
**Definition**: A project is a series of tasks linked to a goal with a deadline.

**Characteristics**:
- Has a clear end date or completion state
- Requires multiple steps or sessions to complete
- Has a specific, measurable outcome
- Is currently active

**Examples**:
- `joint-commission-survey-prep-2026.md` - Preparing for upcoming accreditation survey
- `provider-recruitment-q1.md` - Hiring new physicians this quarter
- `pasture-renovation-spring-2026.md` - Property improvement project
- `performance-review-cycle-2026.md` - Annual staff evaluations

**When to Create**: When you start work on something with a specific end goal and timeline.

**When to Archive**: When the project is completed, cancelled, or put on indefinite hold.

#### 2. Areas (`/areas`)
**Definition**: An area of responsibility is a sphere of activity with a standard to maintain over time.

**Characteristics**:
- Has no end date (ongoing indefinitely)
- Requires regular attention and maintenance
- Has quality standards but not completion criteria
- Represents roles and responsibilities

**Examples**:
- `staff-management.md` - Ongoing supervisory duties
- `compliance-monitoring.md` - Continuous regulatory oversight
- `property-maintenance.md` - Ongoing land and equipment care
- `professional-development.md` - Career growth activities
- `health-wellness.md` - Personal health tracking

**When to Create**: When you have ongoing responsibilities that don't have an end date.

**When to Archive**: When a responsibility is no longer yours or no longer relevant.

#### 3. Resources (`/resources`)
**Definition**: A topic or theme of ongoing interest that supports projects and areas.

**Characteristics**:
- Reference material, not active work
- Organized by topic or subject matter
- Useful for multiple projects or areas
- Includes research, guides, and how-tos

**Examples**:
- `joint-commission-standards.md` - Reference documentation
- `sql-queries-reference.md` - Reusable code snippets
- `pasture-management-best-practices.md` - Agricultural research
- `astrophotography-equipment-guide.md` - Hobby reference
- `montana-genealogy-sources.md` - Research resources

**When to Create**: When you find information that might be useful in the future.

**When to Archive**: When the information becomes outdated or no longer relevant.

#### 4. Archive (`/archive`)
**Definition**: Inactive items from the other three categories.

**Characteristics**:
- No longer actively needed
- Preserved for reference and history
- Organized by original category (projects/, areas/, resources/)
- Maintains the same structure as active files

**Structure**:
```
archive/
├── projects/
│   └── 2025-q4-provider-recruitment.md
├── areas/
│   └── radiology-department-oversight.md
└── resources/
    └── old-sql-server-2012-guide.md
```

**When to Archive**: When projects complete, areas are no longer your responsibility, or resources become outdated.

### The To-Do Folder (`/to-do`)
While not part of the original PARA framework, the to-do folder serves as a central location for active task lists:

- `daily-tasks.md` - Today's priorities
- `weekly-planning.md` - Week-at-a-glance
- `project-specific-tasks.md` - Broken down by project
- `someday-maybe.md` - Future possibilities

## Naming Conventions

### File Naming Rules
**Format**: `category-descriptor-context.md`

**Rules**:
1. Use lowercase only
2. Use hyphens (not spaces or underscores)
3. Be descriptive but concise (3-5 words ideal)
4. Include context when helpful (dates, locations, versions)
5. Use consistent terminology

**Good Examples**:
- `joint-commission-prep-2026.md`
- `staff-meeting-notes-2026-01.md`
- `sql-provider-query-templates.md`
- `property-fence-repair-plan.md`

**Bad Examples**:
- `Notes.md` (too vague)
- `Joint Commission Stuff.md` (spaces, not descriptive)
- `JC_prep_FINAL_v2.md` (mixed case, underscores, version suffixes)

### Folder Naming (If Needed)
If a project or area requires multiple files, create a subfolder:

**Format**: `main-topic/`

**Example**:
```
projects/
└── joint-commission-2026/
    ├── README.md (overview)
    ├── preparation-checklist.md
    ├── staff-training-plan.md
    └── document-review.md
```

## Metadata Standards

Every note should include metadata at the top:

```markdown
---
Created: 2026-01-02
Modified: 2026-01-02
Category: Project | Area | Resource
Status: Active | On Hold | Complete | Archived
Tags: #healthcare #compliance #project
Related: [[other-note.md]], [[another-note.md]]
---

# Note Title

Content here...
```

### Required Fields:
- **Created**: Initial creation date (YYYY-MM-DD)
- **Modified**: Last update date (YYYY-MM-DD)
- **Category**: PARA category
- **Status**: Current state

### Optional Fields:
- **Tags**: For cross-referencing (#topic)
- **Related**: Links to related notes
- **Priority**: High, Medium, Low
- **DueDate**: For projects with deadlines
- **Owner**: For collaborative work

## Workflow for AI Agents

### When Creating New Content

**Step 1**: Determine PARA Category
Ask these questions:
1. Does it have a deadline or end goal? → **Project**
2. Is it an ongoing responsibility? → **Area**
3. Is it reference material for future use? → **Resource**
4. Is it completed or no longer active? → **Archive**

**Step 2**: Choose Appropriate Folder
- Place file in the correct top-level folder
- Create subfolder only if 3+ related files exist

**Step 3**: Name the File
- Use lowercase with hyphens
- Make it descriptive and specific
- Include temporal context if relevant

**Step 4**: Add Metadata
- Include all required fields
- Add relevant tags for cross-referencing
- Link to related notes

**Step 5**: Structure Content
- Use clear headings
- Include next actions at the top of projects
- Link to related notes and resources

### When Moving Content

**Projects → Archive**:
- When project is complete, cancelled, or on indefinite hold
- Move to `/archive/projects/` with date suffix
- Update status to "Complete" or "Archived"
- Example: `joint-commission-prep-2026.md` → `/archive/projects/joint-commission-prep-2026-completed.md`

**Areas → Archive**:
- When responsibility ends or changes hands
- Move to `/archive/areas/` with end date
- Update metadata to reflect transition

**Resources → Archive**:
- When information becomes outdated
- When better resources supersede old ones
- Preserve for historical reference

### Maintenance Schedule

**Weekly** (Every Friday):
1. Review `/to-do/daily-tasks.md`
2. Check project statuses
3. Update modified dates on active files
4. Archive completed items

**Monthly** (First of Month):
1. Review all projects for completion
2. Update area notes with monthly summaries
3. Clean up and organize to-do lists
4. Archive inactive resources

**Quarterly** (January, April, July, October):
1. Full PARA review
2. Reorganize misplaced files
3. Update tags and metadata
4. Purge unnecessary archive items

## Usage Guidelines

### Creating New Notes

1. Determine the appropriate PARA category
2. Use existing templates from `/templates` directory when applicable
3. Include metadata at the top of each note
4. Link related notes using relative file paths `[[note-name.md]]`
5. Add descriptive tags for cross-referencing

### Task Management

- Active tasks are tracked in `/to-do` directory
- Use clear, actionable language (start with verbs)
- Include priority levels: 🔴 High, 🟡 Medium, 🟢 Low
- Add due dates where applicable: `[2026-01-15]`
- Move completed tasks to archive with completion date

### Linking Notes

**Internal Links**: `[[filename.md]]` or `[[folder/filename.md]]`

**External Links**: `[Description](https://url.com)`

**Back-linking**: When referencing a note, add a back-link in the related note

## Examples

### Project Note Example
```markdown
---
Created: 2026-01-02
Modified: 2026-01-02  
Category: Project
Status: Active
Tags: #healthcare #compliance #accreditation
DueDate: 2026-03-15
Related: [[compliance-monitoring.md]], [[staff-training-plan.md]]
---

# Joint Commission Survey Preparation 2026

## Next Actions
- [ ] 🔴 Complete document review by 2026-01-10
- [ ] 🟡 Schedule staff training sessions
- [ ] 🟢 Update emergency procedures manual

## Overview
Preparation for the Joint Commission accreditation survey scheduled for March 2026.

## Key Milestones
- Jan 15: Document review complete
- Feb 1: Staff training complete
- Feb 15: Mock survey
- Mar 15: Actual survey

## Notes
...
```

### Area Note Example
```markdown
---
Created: 2026-01-02
Modified: 2026-01-02
Category: Area
Status: Active
Tags: #management #staff #supervision
Related: [[performance-review-cycle-2026.md]]
---

# Staff Management

## Responsibilities
- Supervise team of 12 clinical staff
- Conduct weekly team meetings
- Handle performance issues and coaching
- Approve time off and schedule adjustments

## Current Focus
- Q1 2026: Performance review preparation
- Ongoing: Staff development and training

## Team Members
...
```

## Tools

This repository is designed to work with:
- **Markdown editors**: Obsidian, VS Code, Typora, iA Writer
- **Version control**: Git for tracking changes and sync
- **Search tools**: grep, ripgrep, or built-in editor search
- **AI assistants**: Perplexity, ChatGPT, Claude (with context from this README)

## For AI Agents: Quick Reference

**When the user asks to create a note:**
1. Ask clarifying questions to determine PARA category if unclear
2. Suggest an appropriate filename following naming conventions
3. Create file with complete metadata
4. Structure content with clear headings and next actions

**When the user asks to organize or archive:**
1. Review file metadata and content
2. Determine if it should move categories
3. Update filename and path as needed
4. Update metadata (Modified date, Status)
5. Ensure links remain valid

**When uncertain:**
- Default to Project if there's a deadline
- Default to Area if it's ongoing without an endpoint  
- Default to Resource if it's reference material
- Ask the user if still unclear

---
*Last updated: 2026-01-02*
*PARA Method by Tiago Forte | Building a Second Brain*
