# Meeting Notes Processing Template

## Basic Prompt

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

Format as clean markdown that I can paste into Notion/Confluence.
```

## Enhanced Version (with context)

```
I'm a PM at TaskFlow. Analyze these meeting notes from our 
[meeting type] meeting.

Participants: [names if relevant]
Context: [any relevant context]

Extract:
1. **Action Items** (with owners and deadlines)
2. **Decisions** (what was finalized)
3. **Open Questions** (needs follow-up)
4. **Key Points** (main topics summary)
5. **My Action Items** (specifically for me)

Format for: [Notion/Slack/Email]
```

## Quick Version

```
Extract action items with owners and deadlines from these notes:
[paste notes]
```
