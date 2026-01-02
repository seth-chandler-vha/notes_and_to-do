# Instructions for User: Working with Perplexity AI

**Repository**: notes_and_to-do  
**System**: PARA Method (Building a Second Brain)  
**Last Updated**: 2026-01-02

---

## Overview

This document provides you with simple, natural language prompts to use with Perplexity (or other AI agents) to maintain your notes repository. The AI will automatically handle file placement, naming conventions, metadata, and organizational structure based on the PARA system documented in the README.

## Quick Start: The Basic Prompt Pattern

**General Format**:
```
Create a note about [TOPIC] for [CONTEXT/PURPOSE]
```

The AI will:
1. Ask clarifying questions if needed
2. Determine the correct PARA category
3. Suggest an appropriate filename
4. Create the file with proper metadata
5. Place it in the correct folder
6. Structure the content appropriately

---

## Scenario-Based Instructions

### Scenario 1: Starting a New Work Project

**When**: You're beginning a project with a specific goal and deadline

**What to Type**:
```
Create a project note for [project name] with deadline [date]
```

**Examples**:
- "Create a project note for Joint Commission survey preparation with deadline March 15, 2026"
- "Start a new project for Q1 provider recruitment ending March 31st"
- "Create a project note for the spring pasture renovation project"

**What Perplexity Will Do**:
- Place file in `/projects/`
- Name it using lowercase-hyphen format
- Add complete metadata (Created, Modified, Category: Project, Status: Active, DueDate)
- Create sections for: Next Actions, Overview, Key Milestones, Notes
- Ask for additional details if needed

---

### Scenario 2: Documenting an Ongoing Responsibility

**When**: You need to track something you're responsible for indefinitely

**What to Type**:
```
Create an area note for [responsibility name]
```

**Examples**:
- "Create an area note for staff management"
- "Start tracking property maintenance as an ongoing area"
- "Create an area for compliance monitoring"
- "I need an area note for my professional development"

**What Perplexity Will Do**:
- Place file in `/areas/`
- Name it descriptively (e.g., `staff-management.md`)
- Add metadata with Category: Area
- Create sections for: Responsibilities, Current Focus, Standards/Goals
- No deadline (ongoing nature)

---

### Scenario 3: Saving Reference Material

**When**: You find useful information you want to keep for future use

**What to Type**:
```
Create a resource note about [topic]
```

**Examples**:
- "Create a resource note about Joint Commission standards"
- "Save this as a resource about SQL query templates"
- "Create a resource for pasture management best practices"
- "I want to save these astrophotography equipment recommendations as a resource"

**What Perplexity Will Do**:
- Place file in `/resources/`
- Name it by topic (e.g., `sql-query-templates.md`)
- Add metadata with Category: Resource
- Organize as reference material, not active work
- Include sources, links, and key information

---

### Scenario 4: Creating a To-Do List

**When**: You need to track tasks or create a daily/weekly plan

**What to Type**:
```
Create a to-do list for [timeframe/purpose]
```

**Examples**:
- "Create my to-do list for today"
- "Start a weekly planning list for this week"
- "Create a task list for the Joint Commission project"
- "I need a someday-maybe list for future ideas"

**What Perplexity Will Do**:
- Place file in `/to-do/`
- Name appropriately (e.g., `daily-tasks-2026-01-02.md` or `weekly-planning.md`)
- Format with checkboxes and priority indicators
- Include due dates where applicable
- Organize by priority: 🔴 High, 🟡 Medium, 🟢 Low

---

### Scenario 5: Updating an Existing Note

**When**: You need to add information to a note or update it

**What to Type**:
```
Update [note name] with [new information]
```

**Examples**:
- "Update the Joint Commission prep note with today's meeting notes"
- "Add a new task to the staff management area"
- "Update my daily to-do list - mark items complete and add new ones"
- "Add this SQL query to my resources"

**What Perplexity Will Do**:
- Locate the existing file
- Update the Modified date in metadata
- Add your content in the appropriate section
- Maintain existing structure and formatting
- Update related links if needed

---

### Scenario 6: Completing a Project (Archiving)

**When**: A project is finished and you want to archive it

**What to Type**:
```
Archive [project name] - it's complete
```

**Examples**:
- "Archive the Q4 provider recruitment project - we hired everyone"
- "The Joint Commission survey is done - archive that project"
- "Move the pasture renovation project to archive - completed"

**What Perplexity Will Do**:
- Move file from `/projects/` to `/archive/projects/`
- Update Status to "Complete" or "Archived"
- Add completion date to filename if appropriate
- Update Modified date
- Preserve all content and links

---

### Scenario 7: Weekly Review and Maintenance

**When**: It's Friday and you want to clean up your workspace

**What to Type**:
```
Do my weekly PARA review
```

**What Perplexity Will Do**:
- Review all files in `/to-do/` and suggest cleanup
- Check project statuses and ask if any are complete
- Update Modified dates on active files
- Suggest items to archive
- Summarize active projects and areas
- Create a report of what needs attention

---

### Scenario 8: Meeting Notes

**When**: You need to capture notes from a meeting

**What to Type**:
```
Create meeting notes for [meeting name] on [date]
```

**Examples**:
- "Create meeting notes for staff meeting on January 2"
- "I need to document today's Joint Commission planning meeting"
- "Create notes from the property fence contractor meeting"

**What Perplexity Will Do**:
- Determine if it's project-related or an area responsibility
- Place in appropriate folder or subfolder
- Name with date: `staff-meeting-notes-2026-01-02.md`
- Create structure: Attendees, Topics, Decisions, Action Items
- Link to related project or area files

---

### Scenario 9: Research and Learning

**When**: You're researching a topic and want to capture findings

**What to Type**:
```
Create research notes about [topic]
```

**Examples**:
- "Create research notes about new Joint Commission standards"
- "I'm researching pasture grass species - create a note"
- "Document my research on astrophotography equipment"

**What Perplexity Will Do**:
- Place in `/resources/` (if reference material) or related project folder
- Include sources and links
- Organize findings logically
- Tag appropriately for future searching

---

### Scenario 10: Creating Templates

**When**: You want to create a reusable template for future notes

**What to Type**:
```
Create a template for [type of note]
```

**Examples**:
- "Create a template for project kickoff notes"
- "I need a template for staff meeting notes"
- "Create a weekly planning template"

**What Perplexity Will Do**:
- Place file in `/templates/`
- Name as `template-[type].md`
- Include placeholder sections and metadata
- Add instructions for use
- Make it easy to copy and customize

---

## Advanced Usage

### Multi-File Projects

**When**: A project needs multiple related files

**What to Type**:
```
Create a project folder for [project name] with files for [list files]
```

**Example**:
"Create a project folder for Joint Commission 2026 with files for preparation checklist, staff training plan, and document review"

**What Perplexity Will Do**:
- Create `/projects/joint-commission-2026/` subfolder
- Create README.md as overview
- Create each requested file
- Link files together
- Maintain consistent metadata

---

### Searching and Linking

**When**: You want to connect related notes

**What to Type**:
```
Show me all notes related to [topic] and link them together
```

**Example**:
"Show me all notes related to staff management and make sure they're linked"

**What Perplexity Will Do**:
- Search across all folders
- Identify related notes
- Add cross-references
- Update Related metadata fields
- Create a summary of connections

---

## Troubleshooting & Tips

### If Perplexity Asks Clarifying Questions

This is **good**! It means:
- The AI needs more context to place the file correctly
- It wants to ensure proper categorization
- It's following the PARA methodology

**Common Questions**:
- "Does this have a deadline?" → Helps determine Project vs. Area
- "Is this reference material or active work?" → Helps choose between Resource and Project/Area
- "What would you like to name this?" → Asking for your preference

**How to Respond**: Answer naturally and conversationally

---

### Being More Specific

The more context you provide, the better:

❌ **Vague**: "Create a note about work stuff"

✅ **Better**: "Create a note about work stuff" → AI asks questions → You clarify

✅ **Best**: "Create a project note for Q1 performance reviews with deadline March 31st"

---

### Checking the Structure

**What to Type**:
```
Show me the current structure of my notes repository
```

**What Perplexity Will Do**:
- List all active projects
- List all areas
- Show file counts
- Identify any misplaced files
- Suggest cleanup actions

---

## Command Reference: Quick Phrases

Here are simple, natural phrases you can use:

### Creating:
- "Create a [project/area/resource] note for..."
- "Start tracking..."
- "I need a note about..."
- "Document..."
- "Save this information about..."

### Updating:
- "Update [note name] with..."
- "Add to [note name]..."
- "Append to..."
- "Edit [note name]..."

### Organizing:
- "Archive [note name]"
- "Move [note name] to..."
- "This project is complete"
- "Clean up my to-do lists"
- "Do my weekly review"

### Finding:
- "Show me all [projects/areas/resources]"
- "Find notes about..."
- "What's related to..."
- "List my active projects"

---

## Real-World Examples

### Example 1: Healthcare Administrator

**Monday Morning**:
"Create my daily to-do list for today with priority items"

**Starting New Work**:
"Create a project note for Joint Commission survey preparation with deadline March 15, 2026"

**After a Meeting**:
"Create meeting notes for today's compliance committee meeting"

**Saving Information**:
"Create a resource note about the new CMS billing codes for 2026"

**End of Week**:
"Do my weekly PARA review and clean up completed tasks"

### Example 2: Property Owner

**Planning Improvement**:
"Create a project note for spring pasture renovation starting in March"

**Tracking Maintenance**:
"Create an area note for ongoing property maintenance"

**Saving Research**:
"Create a resource about best practices for pasture grass selection in Montana"

**Contractor Meeting**:
"Create meeting notes for the fence contractor consultation"

---

## Remember

1. **You don't need to know the file structure** - The AI handles it
2. **You don't need to remember naming conventions** - The AI follows them
3. **Just describe what you need naturally** - The AI understands context
4. **The AI will ask questions if unclear** - This is helpful, not annoying
5. **Review the README occasionally** - But you don't need to memorize it

---

## Getting Started Today

Try these three commands right now:

1. **"Create my daily to-do list for today"**  
   → See how the AI structures your tasks

2. **"Show me the current structure of my repository"**  
   → Understand what's already here

3. **"Create a project note for [something you're working on]"**  
   → Experience the full workflow

---

**Questions?** Just ask Perplexity: "How do I [what you want to do] in my notes repository?"

The AI has full context from the README and will guide you through any scenario.

---
*For technical details and AI agent workflows, see README.md*
