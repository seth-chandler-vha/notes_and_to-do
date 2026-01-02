# User Instructions: Working with AI Agents in PARA

This guide explains how to interact with Perplexity and other AI agents to maintain your notes_and_to-do repository without having to provide explicit folder paths or organization instructions each time.

## Overview

Your repository follows the PARA method (Projects, Areas, Resources, Archive). AI agents have been trained to automatically organize your content into the correct folders based on simple, natural language requests. You don't need to specify folder paths or category names - just describe what you want to do.

## Basic Principles

**You provide**:
- What you want to do (create, update, find, move)
- The content or topic
- Optional context (deadline, status, related items)

**The AI agent handles**:
- Determining the correct PARA category
- Applying naming conventions
- Adding metadata
- Creating links between related notes
- Suggesting when items should move categories

## 11 Common Scenarios
### Scenario 1: Starting a New Project

**What you say**:
- "I'm starting a website redesign project due in Q2 2025"
- "Create notes for my kitchen renovation project, completion target summer"
- "Start tracking the annual review process, due March 15"

**What the AI does**:
- Creates file in `/projects` folder
- Names it appropriately (e.g., `website-redesign-notes.md`)
- Adds metadata with deadline
- Links to related resources if they exist

**You don't need to say**:
- "Create a file in the projects folder called..."
- "This is a project because it has a deadline"
- "Use the project template"

### Scenario 2: Documenting Ongoing Responsibilities

**What you say**:
- "Take notes on my professional development activities"
- "I need to track health and fitness"
- "Create an overview for home maintenance tasks"

**What the AI does**:
- Creates file in `/areas` folder
- Uses format: `area-name-overview.md`
- Adds metadata for ongoing responsibility
- Suggests periodic review schedule

**You don't need to say**:
- "This should go in areas because it's ongoing"
- "Make it an area-type file"

### Scenario 3: Saving Reference Material

**What you say**:
- "Save these SQL query examples for future reference"
- "I want to keep this astrophotography equipment guide"
- "Store this information about BASB methodology"

**What the AI does**:
- Creates file in `/resources` folder
- Organizes by topic
- Names as: `topic-reference.md` or `topic-guide.md`
- Tags for easy retrieval

**You don't need to say**:
- "Put this in resources"
- "This is reference material"

### Scenario 4: Completing a Project

**What you say**:
- "The website redesign is complete"
- "I finished the kitchen renovation project"
- "Mark the annual review as done"

**What the AI does**:
- Moves file from `/projects` to `/archive`
- Updates metadata with completion date
- Maintains links to related files
- Suggests cleanup of related tasks

**You don't need to say**:
- "Move this from projects to archive"
- "Update the status metadata"

### Scenario 5: Adding Tasks

**What you say**:
- "Add 'finalize budget' to my website redesign tasks"
- "I need to schedule dentist appointment this month"
- "Create a high-priority task to review Q3 numbers by Friday"

**What the AI does**:
- Adds task to `/to-do` folder
- Links to parent project or area
- Formats with priority and due date
- Uses correct task syntax

**You don't need to say**:
- "Create a task in the to-do folder"
- "Link it to the project file"
- "Use the task format"

### Scenario 6: Meeting Notes

**What you say**:
- "Take notes on today's quarterly planning meeting"
- "Document the team standup from this morning"
- "Record notes from my 1-on-1 with manager"

**What the AI does**:
- Creates file in appropriate location (project or area)
- Uses meeting notes template
- Adds date and attendees
- Links to relevant project/area

**You don't need to say**:
- "Use the meeting notes template"
- "Figure out if this is a project or area meeting"

### Scenario 7: Research and Planning

**What you say**:
- "Research options for new project management tools"
- "Collect information about Montana property taxes"
- "Compare astrophotography telescope options"

**What the AI does**:
- Creates file in `/resources` if general research
- Or in `/projects` if tied to active project
- Organizes findings logically
- Links to related notes

**You don't need to say**:
- "Decide if this is a resource or project"
- "Create appropriate file structure"

### Scenario 8: Reviewing and Updating

**What you say**:
- "Update my professional development goals"
- "Review the home maintenance area"
- "Check progress on website redesign"

**What the AI does**:
- Finds existing file in correct category
- Opens for editing
- Suggests creating review entry
- Updates last-modified metadata

**You don't need to say**:
- "Find the file in the areas folder"
- "Open professional-development-overview.md"

### Scenario 9: Searching and Retrieving

**What you say**:
- "Find my notes about SQL queries"
- "Show me all active projects"
- "What resources do I have about healthcare compliance?"

**What the AI does**:
- Searches across appropriate categories
- Returns relevant files
- Shows recent updates
- Suggests related content

**You don't need to say**:
- "Search in the resources folder"
- "Look for files matching..."

### Scenario 10: Managing Inactive Items

**What you say**:
- "The graduate school area is no longer relevant"
- "Archive old 2020 tax planning resources"
- "I'm no longer working on the garden shed project"

**What the AI does**:
- Moves to `/archive` folder
- Preserves structure and links
- Updates metadata
- Suggests periodic cleanup

**You don't need to say**:
- "Move this to archive"
- "Mark it as inactive"
- 
### Scenario 11: Transcribing Handwritten Notes from iPhone Photos

**What you say**:
- "I took a picture of my meeting notes, transcribe them and update the website project file"
- "Here's a photo of my handwritten to-do list, add these tasks to the appropriate files"
- "Transcribe this handwritten note and save it in my professional development area"
- "I photographed my brainstorming notes for the kitchen renovation, organize them in the project"

**What the AI does**:
- Uses OCR/vision capabilities to read the handwritten text from your iPhone photo
- Transcribes the content accurately
- Determines the appropriate PARA category based on content and your description
- Updates existing file or creates new one as needed
- Commits changes to the GitHub repository (work or personal account as specified)
- Maintains proper formatting and structure

**You don't need to say**:
- "Use OCR to extract the text"
- "Parse the handwriting"
- "Determine which repo to use"
- "Commit the changes to GitHub"

**How to do this**:

1. **Take the photo**: Use your iPhone camera to photograph your handwritten notes
   - Ensure good lighting and the text is clearly visible
   - Photo can be from Camera app or screenshot from Notes app

2. **Share with Perplexity**: 
   - Open Perplexity on your iPhone
   - Tap the camera/attachment icon
   - Select your photo
   - Add your natural language instruction

3. **Specify the context**:
   - What the notes are about
   - Which project/area they relate to  
   - Whether it's for work (VHA repo) or personal (cainlayder repo)
   - Any specific organization preferences

**Example interactions**:

**Example 1 - Meeting Notes**:
"Here's a photo of my handwritten notes from today's project kickoff meeting. Transcribe these and add them to the website redesign project file. This is for my personal repo."

**Example 2 - Task List**:
"I wrote down some tasks on paper. [attach photo] These are all related to home maintenance. Add them to my to-do folder with appropriate priorities based on the notes. Personal account."

**Example 3 - Research Notes**:
"[attach photo] These are my handwritten research notes about SQL optimization techniques. Create a new resource file for this and save it in my work repository."

**Example 4 - Quick Capture**:
"Transcribe this sticky note [attach photo] - it's ideas for the Q1 planning. Add to my work projects for the strategic planning project."

**What repository?**:
- **Work/VHA account** (seth-chandler-vha/notes_and_to_do): Specify "work repo", "VHA account", or "work"
- **Personal account** (cainlayder/notes_and_to-do): Specify "personal repo", "personal account", or "personal"
- If not specified, AI will ask which repository to use

**The AI handles all the technical details**:
- Reading and transcribing your handwriting
- Understanding context from the photo (diagrams, arrows, highlighting)
- Organizing the content logically
- Applying proper markdown formatting
- Navigating to the correct GitHub repository
- Finding or creating the appropriate file
- Updating the file with transcribed content
- Committing and pushing changes

**Tips for best results**:
- ✅ Write clearly and legibly
- ✅ Use good lighting when photographing
- ✅ Mention the project/area name in your instruction
- ✅ Specify work vs. personal repository
- ✅ Include any important context ("these are high priority", "this is for next week", etc.)
- ✅ If you have multiple pages, you can attach multiple photos

## Pro Tips for Natural Interaction

### Be Conversational
✅ **Good**: "I'm starting a project to renovate the kitchen, should be done by summer"
❌ **Unnecessary**: "Create project file kitchen-renovation in projects folder with completion date summer 2025"

### Provide Context, Not Structure
✅ **Good**: "Take notes on the budget meeting for the website project"
❌ **Unnecessary**: "Create meeting-notes file in projects/website-redesign/ folder"

### Use Natural Time References
✅ **Good**: "This is due next Friday"
✅ **Good**: "Target completion Q2"
✅ **Good**: "By end of month"

### Let the AI Ask for Clarity
If the AI needs more information to categorize correctly, it will ask:
- "Is this an ongoing responsibility or a specific project with a deadline?"
- "Is this reference material or something you're actively working on?"

### Trust the System
The AI has been trained on the PARA method specifically for your repository. It understands:
- Projects have deadlines
- Areas are ongoing
- Resources are for reference
- Archive is for completed/inactive items

## What to Specify (and When)

### Always Specify:
- **Deadlines** for projects: "due March 15", "by Q2", "next Friday"
- **Priority** for tasks: "high priority", "urgent", "when I have time"
- **Relationships**: "related to the website project", "part of professional development"

### Sometimes Specify:
- **Status**: "in progress", "blocked", "on hold" (useful for updates)
- **Tags**: "VA-related", "personal", "work" (helps with organization)
- **Review frequency**: "review monthly", "quarterly check-in" (for areas)

### Never Need to Specify:
- Folder names or paths
- File naming conventions
- Metadata structure
- Template to use
- Link formatting

## Examples of Complex Requests

The AI can handle multi-step requests:

**Example 1**:
"I'm starting a new project to implement a data dashboard for our team. It's due by end of Q1. Create the project notes and also add a high-priority task to draft requirements this week. Link it to my ongoing team management responsibilities."

**What happens**:
1. Creates project file in `/projects`
2. Adds task to `/to-do` with priority and deadline
3. Links project to existing area file
4. Sets up metadata with Q1 deadline

**Example 2**:
"The kitchen renovation is complete. Archive the project and create a new home maintenance area note about annual kitchen deep cleaning."

**What happens**:
1. Moves project from `/projects` to `/archive`
2. Creates new area file in `/areas`
3. Links archive project to new area for reference
4. Updates all metadata

## Troubleshooting

### If the AI Creates Something in the Wrong Place
Just say: "Actually, this should be [description]" and it will move and reorganize.

Example:
- You: "Track my reading list"
- AI: Creates in `/projects`
- You: "Actually, this is ongoing, not a one-time project"
- AI: Moves to `/areas` and adjusts

### If You're Unsure Where Something Goes
The AI will use the decision tree from the README to figure it out. But you can also ask:
- "Should my reading list be a project or area?"
- "Where should I keep SQL examples?"

### If You Want to Override the AI's Decision
You can always be explicit:
- "Create this as a resource even though it sounds like a project"
- "I want this in projects, not areas"

## Remember

The goal of this system is to reduce cognitive load. You should be thinking about your work, not about file organization. The AI handles the structure so you can focus on content.

**Think**: "What do I need to capture?"
**Not**: "Where should I file this?"

The more naturally you interact, the better the system works. Trust the PARA method and the AI's training to keep everything organized correctly.
