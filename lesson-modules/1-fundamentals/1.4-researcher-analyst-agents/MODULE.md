# Module 1.4: Using Researcher & Analyst Agents

**Duration:** 20 minutes
**Prerequisites:** Modules 1.1-1.3 completed

---

## What You'll Learn

By the end of this module, you will:
1. Understand what Copilot agents are and how they differ from regular chat
2. Use the **Researcher** agent for deep, multi-step research
3. Use the **Analyst** agent for complex data analysis
4. Know when to use agents vs regular Copilot Chat
5. Leverage the **Workflows** agent for automation

---

## What Are Copilot Agents?

Agents are **specialized AI assistants** built into Microsoft 365 Copilot. They're designed for specific types of complex tasks.

### Regular Copilot Chat vs Agents

| Regular Copilot Chat | Agents |
|---------------------|--------|
| Quick Q&A | Multi-step reasoning |
| Single-turn tasks | Extended workflows |
| Immediate responses | Takes 5-10 minutes |
| General purpose | Specialized tasks |
| Uses GPT-5 | Uses reasoning models (o3) |

### Available Agents in M365 Copilot

1. **Researcher** - Deep research across web and work data
2. **Analyst** - Complex data analysis and reasoning
3. **Workflows** - Automation across M365 apps

**Note:** You get 25 combined Researcher + Analyst queries per month with M365 Copilot license.

---

## Accessing Agents

To access agents in Copilot:

1. Go to **copilot.microsoft.com**
2. Look at the **left panel**
3. You'll see agents listed (Researcher, Analyst, etc.)
4. Click an agent to start a specialized session

Alternatively, in the chat:
- Type **@Researcher** followed by your question
- Type **@Analyst** followed by your data analysis request

---

## The Researcher Agent

Researcher is your **AI research assistant**. It performs deep, multi-step research and produces comprehensive reports.

### What Researcher Does

1. Breaks your question into sub-questions
2. Searches across web AND your work data
3. Evaluates multiple sources
4. Synthesizes findings
5. Produces a cited report

### When to Use Researcher

| Use Researcher For | Don't Use For |
|-------------------|---------------|
| Competitive analysis | Quick facts |
| Market research | Simple questions |
| Multi-source synthesis | Single document analysis |
| Trend analysis | Real-time data |
| Strategic reports | Basic summaries |

### Researcher Example: Competitive Analysis

**Prompt:**

```
Research how our competitors (Asana, Linear, Monday.com, Jira) handle
user onboarding. I need to understand:

1. What does their onboarding flow look like?
2. How long does it take for a new user to complete onboarding?
3. What personalization do they offer?
4. What are users saying about their onboarding (positive and negative)?
5. What best practices can we learn from?

I'm the PM for onboarding at TaskFlow, a competing project management tool.
Create a comprehensive report I can share with my team.
```

**What happens:**
- Researcher shows its "thinking" as it works
- Takes 5-10 minutes
- Produces a multi-page report with citations
- You can export to Word

---

## Exercise 1: Use Researcher

Let's try a research task relevant to your TaskFlow PM role.

**Do this now:**

1. Click on **Researcher** in the left panel
2. Enter this prompt:

```
Research best practices for improving SaaS activation rates.
I'm a PM at a project management tool and our activation rate
(users who complete first task within 24 hours) is 35%.

I need:
1. Industry benchmarks for activation rates
2. Top strategies companies use to improve activation
3. Case studies of companies that significantly improved activation
4. Specific tactics we could implement
5. Metrics we should track

Create a strategic report with actionable recommendations.
```

3. Watch Researcher work (notice the "thinking" display)
4. Review the final report

**What to notice:**
- The depth of analysis
- Citations and sources
- Structured, actionable output
- Takes longer but more thorough

---

## The Analyst Agent

Analyst is your **AI data scientist**. It uses reasoning models to solve complex analytical problems.

### What Analyst Does

1. Understands your data analysis question
2. Applies multi-step reasoning
3. Performs calculations and analysis
4. Explains its methodology
5. Provides insights and recommendations

### When to Use Analyst

| Use Analyst For | Don't Use For |
|----------------|---------------|
| Complex data interpretation | Simple sums/averages |
| Statistical analysis | Basic charts |
| Multi-variable problems | Quick calculations |
| Predictive insights | Real-time dashboards |
| Hypothesis testing | Data cleaning |

### Analyst Example: Cohort Analysis

**Prompt:**

```
I'm analyzing our user cohorts. Here's the data:

January cohort: 500 signups, 175 activated (35%), 87 retained at 30 days
February cohort: 550 signups, 220 activated (40%), 110 retained at 30 days
March cohort: 600 signups, 270 activated (45%), 148 retained at 30 days

Analyze this data and help me understand:
1. What's the trend in activation and retention?
2. Is the improvement statistically significant?
3. What might be driving the improvement?
4. What should we project for April if the trend continues?
5. What risks should I flag to leadership?
```

**What Analyst provides:**
- Statistical analysis of trends
- Significance calculations
- Projections with confidence levels
- Risk assessment
- Clear explanation of methodology

---

## Exercise 2: Use Analyst

Let's try a data analysis task.

**Do this now:**

1. Click on **Analyst** in the left panel
2. Enter this prompt:

```
Help me analyze this A/B test result:

Control group (old onboarding):
- 1,000 users
- 320 completed onboarding (32%)
- 160 performed first action (16%)
- 80 retained at day 7 (8%)

Test group (new onboarding):
- 1,000 users
- 420 completed onboarding (42%)
- 252 performed first action (25.2%)
- 126 retained at day 7 (12.6%)

Questions:
1. Is this result statistically significant?
2. What's the confidence level?
3. Should we ship this to 100% of users?
4. What additional data would strengthen this decision?
5. Write a brief recommendation for my manager.
```

3. Review Analyst's methodology and conclusions

**What to notice:**
- Step-by-step reasoning
- Statistical rigor
- Clear recommendations
- Explains the "why" behind conclusions

---

## The Workflows Agent

Workflows is your **automation assistant**. It helps you create automated flows across M365 apps.

### What Workflows Can Do

1. Send automated emails and reminders
2. Create calendar events based on triggers
3. Post updates to Teams channels
4. Manage SharePoint files
5. Connect to Planner and other M365 services

### Example Workflow: Weekly Report

**Prompt:**

```
Create a workflow that:
1. Every Friday at 4pm
2. Sends me an email reminder to write my weekly update
3. Then on Monday at 9am
4. Posts my update (once I've written it) to the Product team channel in Teams
```

Workflows builds this automation without you needing to use Power Automate directly.

---

## When to Use Each Tool

Here's a decision framework:

```
Is it a quick question?
├── YES → Use regular Copilot Chat
└── NO → Does it require deep research?
    ├── YES → Use Researcher (5-10 min)
    └── NO → Does it require complex analysis?
        ├── YES → Use Analyst
        └── NO → Does it need automation?
            ├── YES → Use Workflows
            └── NO → Use regular Copilot Chat
```

### Quick Reference

| Task Type | Use This |
|-----------|----------|
| "What is X?" | Copilot Chat |
| "Summarize this doc" | Copilot Chat |
| "Research the market for X" | Researcher |
| "Analyze our competitors' Y" | Researcher |
| "Is this A/B test significant?" | Analyst |
| "What does this data tell us?" | Analyst |
| "Remind me every Friday to..." | Workflows |
| "Post updates to Teams when..." | Workflows |

---

## Agent Limits & Best Practices

### Monthly Limits
- **25 queries** for Researcher + Analyst combined
- No limit on Workflows
- No limit on regular Copilot Chat

### Best Practices

1. **Save complex work for agents** - Don't waste queries on simple tasks
2. **Be specific** - Better prompts = better results
3. **Export important outputs** - Save to Word/OneDrive
4. **Iterate in chat first** - Refine your question before using an agent
5. **Track your usage** - 25 queries/month isn't many for power users

---

## Module Complete!

You now know:
- ✅ What Copilot agents are and how they differ from chat
- ✅ How to use Researcher for deep research
- ✅ How to use Analyst for complex data analysis
- ✅ When to use each tool (chat vs agents)
- ✅ How Workflows automates M365 tasks

---

## Next Steps

Continue to **Module 1.5: Persona Prompting for Different Perspectives**

In Module 1.5, you'll learn how to:
- Get feedback from different "perspectives" (engineer, exec, researcher)
- Create reusable persona prompts
- Use Copilot as your virtual advisory board

---

## Quick Reference: Agent Access

| Agent | Access | Best For |
|-------|--------|----------|
| Researcher | Left panel or @Researcher | Deep research, reports |
| Analyst | Left panel or @Analyst | Data analysis, statistics |
| Workflows | Left panel | M365 automation |

---

**Ready to get multiple perspectives? Let's go to Module 1.5!**
