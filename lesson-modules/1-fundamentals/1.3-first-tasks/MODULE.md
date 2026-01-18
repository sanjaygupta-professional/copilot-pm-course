# Module 1.3: Your First PM Tasks with Copilot

**Duration:** 30 minutes
**Prerequisites:** Modules 1.1-1.2 completed

---

## What You'll Learn

By the end of this module, you will:
1. Process messy meeting notes into clear action items
2. Synthesize multiple user interview transcripts
3. Transform the same content for different audiences
4. Analyze design mockups and provide feedback
5. Perform rapid web research

These are the **core PM skills** that will save you hours every week!

---

## Scenario: A Day at TaskFlow

It's Monday morning at TaskFlow. As Senior PM for Activation & Onboarding, you have:

- 📝 Messy meeting notes from 3 different meetings
- 🎤 8 user interview transcripts that need synthesis
- 📧 An update that needs to go to 3 different audiences
- 🎨 A design mockup that needs PM feedback
- 🔍 Research needed for a competitor feature

Let's tackle each one with Copilot!

---

## Task 1: Meeting Notes → Action Items

**Time without Copilot:** 30 minutes
**Time with Copilot:** 2 minutes

### The Problem

You have raw, messy meeting notes. You need:
- Clear action items with owners
- Key decisions documented
- Follow-up items flagged

### Step-by-Step

1. **Upload the meeting notes file**
   - Use the 📎 button or drag and drop
   - Upload: `meeting-notes-raw.md` from the sample files

2. **Use this prompt:**

```
Please analyze these meeting notes and create a structured summary:

## Action Items
- List each action item
- Assign owner (based on context clues)
- Note deadline if mentioned

## Decisions Made
- List any decisions that were finalized

## Open Questions
- List items that need follow-up or clarification

## Key Discussion Points
- Brief summary of main topics discussed

Format as clean markdown that I can paste into Notion.
```

3. **Review and refine**
   - Copilot extracts the structure
   - You verify owners and deadlines
   - Copy to your task management system

### Try It Now!

Use this sample meeting notes content if you don't have the file:

```
meeting 3/5 - product sync
talked about the onboarding flow, sarah mentioned enterprise customers
are getting stuck at step 3, need to look into that
mike says its a API issue but we should check with eng
alex wants a dashboard by end of month - is this realistic?
decision: we're going with option B for the navigation (the one with sidebar)
TODO: sarah to send the error logs
TODO: check with legal about the new privacy stuff
also discussed Q2 planning briefly, more on that thursday
reminder: sprint review is friday 2pm
```

---

## Task 2: Synthesize User Interviews

**Time without Copilot:** 2-3 hours
**Time with Copilot:** 5 minutes

### The Problem

You have 8 user interview transcripts. You need to find:
- Common pain points
- Feature requests that appear multiple times
- Quotes that support key insights

### Step-by-Step

**Important:** Copilot can analyze up to 5 files at once. For 8 files, do this:

1. **Batch 1: Upload first 5 interviews**
   - Upload files together
   - Use this prompt:

```
Analyze these 5 user interview transcripts. I'm looking for patterns.

Please identify:
1. **Common Pain Points** - Issues mentioned by 2+ users
2. **Feature Requests** - Specific features users asked for
3. **Positive Feedback** - What users love about the product
4. **Surprising Insights** - Anything unexpected

For each finding, note which interviews mentioned it (e.g., "Interview 1, 3, 5").
Include a compelling quote for each key finding.
```

2. **Batch 2: Upload remaining 3 interviews**
   - Ask Copilot to analyze these using the same format

3. **Combine findings**
   - Ask Copilot to merge the two analyses:

```
Here are findings from two batches of user interviews.
Please merge these into a single, prioritized synthesis.
Rank pain points by frequency (most common first).
```

### Alternative: Use Researcher Agent

For complex synthesis, try the Researcher agent:

1. Upload all files first
2. Click on "Researcher" in the left panel
3. Ask: "Analyze these user interviews and create a comprehensive research synthesis report"

Researcher takes longer (5-10 min) but produces more thorough analysis.

---

## Task 3: Communication Transformation

**Time without Copilot:** 45 minutes
**Time with Copilot:** 3 minutes

### The Problem

You have ONE update about a new feature. You need to communicate it to:
- **The team** (Slack - casual, brief)
- **Executives** (Email - strategic, metrics-focused)
- **The wiki** (Notion - detailed, reference-style)

### Step-by-Step

1. **Start with your core message:**

```
I need to communicate this update to three different audiences.

THE UPDATE:
We're launching a new onboarding wizard that reduced time-to-first-task
from 15 minutes to 3 minutes in beta testing. It includes guided tooltips,
a progress tracker, and personalized task suggestions based on user role.
Beta users showed 40% higher activation rates.

Please create three versions:

1. **SLACK MESSAGE** (for the product team)
   - Casual, celebratory tone
   - 3-4 sentences max
   - Include an emoji

2. **EXECUTIVE EMAIL** (for leadership)
   - Professional tone
   - Lead with business impact
   - Include metrics
   - 2 short paragraphs

3. **NOTION DOC** (for the wiki)
   - Detailed and structured
   - Include: Overview, Key Features, Metrics, Next Steps
   - Use headers and bullet points
```

2. **Review each version**
   - Copilot adapts tone and detail level
   - Each version serves its audience perfectly

### The Power of Style Templates

For recurring communication needs, save your style instructions. We've included templates in the `communication-styles/` folder:

- `style-slack-update.md` - Template for Slack messages
- `style-executive-email.md` - Template for exec communications
- `style-notion-doc.md` - Template for wiki documentation

**Pro tip:** Upload a style template and ask Copilot to "Write in this style."

---

## Task 4: Design Mockup Feedback

**Time without Copilot:** 20 minutes
**Time with Copilot:** 2 minutes

### The Problem

Design sent you a mockup. You need to provide structured PM feedback covering usability, alignment with personas, and business concerns.

### Step-by-Step

1. **Upload the design image**
   - Drag & drop the mockup image
   - Or use 📎 to attach

2. **Use this prompt:**

```
Analyze this design mockup from a Product Manager perspective.

Context: This is for TaskFlow, a project management tool for remote teams.
Our users are: Sarah (Enterprise Admin), Mike (IC Engineer), Alex (Team Lead).

Please provide feedback on:

1. **Usability** - Is it intuitive? Any confusion points?
2. **Persona Fit** - How well does it serve each user type?
3. **Information Hierarchy** - Is the most important info prominent?
4. **Accessibility** - Any obvious concerns?
5. **Questions for Design** - What should I ask the designer?

Be constructive and specific.
```

3. **Copilot analyzes the visual**
   - It can read text in images
   - It understands UI patterns
   - It provides structured feedback

### Sample Mockup Exercise

If you don't have a mockup, describe one to Copilot:

```
Imagine a dashboard mockup with:
- Left sidebar with navigation
- Main area showing project cards
- Top bar with search and profile
- Cards show project name, progress %, and team members

Analyze this from a PM perspective for TaskFlow.
```

---

## Task 5: Quick Web Research

**Time without Copilot:** 45 minutes
**Time with Copilot:** 2 minutes (basic) or 10 minutes (deep)

### The Problem

A competitor just launched a new feature. You need to understand it quickly for a meeting in 1 hour.

### Option A: Quick Research (2 min)

Use regular Copilot Chat:

```
What do you know about Linear's recent "Triage" feature?
I'm a PM at a competing project management tool and need to understand:
1. What it does
2. Who it's for
3. How it's different from traditional inbox views
4. What users are saying about it
```

Copilot uses its knowledge + web grounding to answer.

### Option B: Deep Research (5-10 min)

Use the **Researcher** agent for comprehensive analysis:

1. Click "Researcher" in the left panel
2. Enter this prompt:

```
Research Linear's new Triage feature. I need a competitive analysis including:
- Feature overview and capabilities
- Target users and use cases
- User reception (reviews, social media sentiment)
- How it compares to similar features in Asana, Jira, Monday.com
- Implications for our product roadmap

Create a report I can share with my team.
```

3. Researcher works for 5-10 minutes
4. Returns a comprehensive, cited report

---

## Your Time Savings Summary

| Task | Old Way | With Copilot | Saved |
|------|---------|--------------|-------|
| Meeting notes | 30 min | 2 min | 28 min |
| 8 interviews | 2-3 hours | 5 min | ~2.5 hrs |
| 3 communications | 45 min | 3 min | 42 min |
| Design feedback | 20 min | 2 min | 18 min |
| Research | 45 min | 5 min | 40 min |
| **TOTAL** | **~5 hours** | **~17 min** | **~4.5 hours** |

**That's almost a full workday saved on just these 5 tasks!**

---

## Practice Exercise: End-of-Day Processing

Let's put it all together. Imagine it's end of day and you need to:

1. Upload the meeting notes from today
2. Extract action items and send to the team
3. Summarize key decisions for your manager

**Try this prompt:**

```
I just finished a day of meetings. Here are my notes:
[Paste or upload your notes]

Please help me with end-of-day processing:

1. **Action Items** - Extract all todos with owners
2. **My Personal Tasks** - What do I need to do specifically?
3. **Decisions Made** - What was finalized?
4. **Executive Summary** - 3 sentences for my manager
5. **Tomorrow's Priorities** - What should I focus on first?
```

---

## Module Complete!

You now know how to:
- ✅ Process meeting notes into structured action items
- ✅ Synthesize multiple user interviews (in batches)
- ✅ Transform content for different audiences
- ✅ Analyze design mockups with PM perspective
- ✅ Perform quick and deep web research

---

## Next Steps

Continue to **Module 1.4: Using Researcher & Analyst Agents**

In Module 1.4, you'll discover Copilot's built-in specialized agents:
- **Researcher** - For deep, multi-step research
- **Analyst** - For data analysis and reasoning
- **Workflows** - For automation

These agents take Copilot to the next level!

---

## Quick Reference: Prompts from This Module

### Meeting Notes
```
Analyze these meeting notes and extract: action items, decisions,
open questions, and key points. Format as markdown.
```

### User Interview Synthesis
```
Analyze these interviews for: common pain points, feature requests,
positive feedback, and surprising insights. Include quotes.
```

### Multi-Audience Communication
```
Transform this update into 3 versions: Slack (casual),
Executive email (metrics-focused), Notion doc (detailed).
```

### Design Feedback
```
Analyze this mockup from PM perspective: usability, persona fit,
information hierarchy, accessibility, questions for designer.
```

### Competitive Research
```
Research [competitor feature]. Provide: overview, target users,
user reception, competitive comparison, product implications.
```

---

**Great work! Ready for the agents? Let's go to Module 1.4!**
