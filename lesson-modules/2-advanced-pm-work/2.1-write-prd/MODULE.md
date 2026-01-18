# Module 2.1: Writing PRDs with Copilot

**Duration:** 35 minutes
**Prerequisites:** Level 1 completed

---

## What You'll Learn

By the end of this module, you will:
1. Use Copilot as a thinking partner (not ghostwriter) for PRDs
2. Leverage templates and context for better PRDs
3. Generate multiple strategic approaches
4. Get multi-perspective feedback using persona prompts
5. Create a complete PRD from research to final draft

---

## The Right Mindset: Thinking Partner, Not Ghostwriter

**Important:** Copilot should help you think through your PRD, not write it for you.

### Why This Matters

- PRDs require YOUR judgment and product intuition
- Copilot doesn't know your users like you do
- The thinking process is as valuable as the output
- Stakeholders need YOUR perspective, not AI's

### The Right Approach

| Don't Do This | Do This Instead |
|---------------|-----------------|
| "Write a PRD for feature X" | "Help me think through the problem space for feature X" |
| "Create requirements for me" | "What questions should I answer before defining requirements?" |
| "Generate the full document" | "Let's structure this section by section" |

---

## The PRD Writing Workflow

### Phase 1: Research & Discovery
- Gather context (user research, data, competitive info)
- Define the problem clearly
- Explore the solution space

### Phase 2: Strategic Thinking
- Generate multiple approaches
- Evaluate tradeoffs
- Choose direction

### Phase 3: Document Structure
- Use a proven template
- Fill sections iteratively
- Get multi-perspective feedback

### Phase 4: Refinement
- Tighten language
- Address gaps
- Prepare for stakeholder review

---

## Phase 1: Research & Discovery

Before writing, gather your inputs.

### Step 1: Upload Context

Upload these files to Copilot:
- User research findings
- Data analysis results
- Competitive research
- Previous related PRDs

### Step 2: Problem Definition

Use this prompt to clarify the problem:

```
I'm writing a PRD for TaskFlow's onboarding improvement.

Here's what I know:
- Current signup-to-active rate: 35%
- Target: 45%
- Main drop-off: After creating first project, before inviting team
- User feedback: "I didn't know what to do next"

Help me articulate:
1. The core problem we're solving
2. Who experiences this problem most acutely
3. The impact of NOT solving this
4. How we'll know if we've succeeded

Ask me clarifying questions if needed.
```

### Step 3: Explore Solution Space

```
Based on this problem, help me brainstorm potential solutions.

For each solution idea, note:
- What it would involve
- Pros and cons
- Rough complexity (S/M/L)
- Who it helps most

Don't filter yet - let's get ideas on the table first.
```

---

## Phase 2: Strategic Thinking

Now evaluate approaches and choose direction.

### Generate Multiple Approaches

```
Let's develop 3 distinct strategic approaches for solving the
onboarding drop-off problem:

**Approach A: Guided Wizard**
(Step-by-step guided experience)

**Approach B: Contextual Hints**
(In-context tooltips and suggestions)

**Approach C: Personalized Paths**
(Role-based onboarding flows)

For each approach, outline:
1. What it involves
2. Key features
3. Success metrics
4. Estimated effort
5. Risks
6. Best for which personas
```

### Evaluate Tradeoffs

```
Compare these 3 approaches using a decision matrix:

Criteria (rate 1-5):
- Impact on activation rate
- Implementation complexity
- Time to launch
- Scalability
- User research support
- Alignment with Q1 goals

Create a table and recommend which approach (or combination)
we should pursue, with reasoning.
```

---

## Phase 3: Document Structure

Now structure your PRD using a proven template.

### Using PRD Templates

We've included two templates in the course:
- **Lenny's PRD Template** - Popular, comprehensive
- **Carl's PRD Template** - Focused, startup-friendly

### Step 1: Upload Your Template

Upload your preferred PRD template to Copilot.

### Step 2: Fill Section by Section

**Don't ask Copilot to write the whole thing.** Instead, work section by section:

```
Let's work through the PRD template section by section.

Start with the PROBLEM STATEMENT section.

Based on our earlier discussion, draft this section. I'll review
and refine before we move to the next section.
```

### Section-by-Section Prompts

**For Problem Statement:**
```
Draft the Problem Statement section. Include:
- The user problem in their words
- Data supporting the problem
- Impact of not solving it
Keep it concise - 3-4 sentences max.
```

**For Goals & Success Metrics:**
```
Draft the Goals section with:
- Primary goal (1 sentence)
- 3-4 measurable success metrics
- How we'll measure each
- Target values

Base these on our 35% → 45% activation goal.
```

**For Solution Overview:**
```
Draft the Solution Overview section:
- High-level description of our approach
- Key features (bullet points)
- How it addresses each user persona's needs
- What's explicitly NOT in scope
```

**For User Stories:**
```
Create user stories for our 3 personas:

For each persona (Sarah, Mike, Alex):
- As a [persona], I want [feature] so that [benefit]
- Include 2-3 user stories each
- Focus on the onboarding experience
```

---

## Phase 4: Multi-Perspective Review

Before finalizing, get feedback from different perspectives.

### Use Your Persona Prompts

```
Review this PRD draft from THREE perspectives:

## As Senior Engineer (David)
- Technical feasibility concerns?
- Missing technical requirements?
- Dependencies or risks?

## As VP Product (Jennifer)
- Strategic alignment?
- Resource implications?
- What will the board ask?

## As User Researcher (Maria)
- Evidence gaps?
- User assumption risks?
- Research we should do first?

PRD DRAFT:
[Paste your draft here]
```

### Address Feedback

```
Based on this feedback, help me identify:
1. Critical gaps I need to address
2. Sections that need strengthening
3. Questions I should answer before sharing

Then help me revise the weak sections.
```

---

## Exercise: Complete PRD Workflow

Let's practice the full workflow.

**Scenario:** Create a PRD for TaskFlow's new onboarding wizard.

### Step 1: Context Setup (5 min)

```
I'm writing a PRD for TaskFlow's Onboarding Wizard feature.

Context:
- Company: TaskFlow, project management SaaS
- Current activation rate: 35% (target: 45%)
- Main drop-off: After first project, before team invite
- Users: Sarah (Admin), Mike (Engineer), Alex (Team Lead)
- Timeline: Q1 launch

Help me structure my thinking for this PRD.
What key questions should I answer first?
```

### Step 2: Problem & Solution (10 min)

Work through problem definition and solution exploration.

### Step 3: Draft Sections (15 min)

Draft 3-4 key sections of the PRD.

### Step 4: Review (5 min)

Get multi-perspective feedback and identify gaps.

---

## PRD Quality Checklist

Before considering your PRD done:

### Clarity
- [ ] Problem is clearly stated
- [ ] Solution is understandable without prior context
- [ ] Success metrics are measurable
- [ ] Scope is explicitly defined

### Completeness
- [ ] All personas addressed
- [ ] Technical considerations included
- [ ] Risks identified
- [ ] Timeline realistic

### Stakeholder Ready
- [ ] Engineering can estimate from this
- [ ] Design knows the user problems
- [ ] Leadership sees strategic alignment
- [ ] No jargon or unclear acronyms

---

## Module Complete!

You now know:
- ✅ How to use Copilot as a thinking partner
- ✅ How to work through PRDs section by section
- ✅ How to get multi-perspective feedback
- ✅ The complete PRD writing workflow
- ✅ Quality checks before sharing

---

## Next Steps

Continue to **Module 2.2: Analyzing Product Data with Copilot**

In Module 2.2, you'll learn:
- Uploading and analyzing data files
- Using Excel Copilot for spreadsheet analysis
- Funnel analysis and A/B test interpretation
- The Analyst agent for complex data reasoning

---

## Quick Reference: PRD Prompts

| Phase | Prompt Starter |
|-------|----------------|
| Problem Definition | "Help me articulate the problem..." |
| Solution Exploration | "Brainstorm potential solutions..." |
| Strategic Options | "Develop 3 distinct approaches..." |
| Section Draft | "Draft the [X] section based on..." |
| Multi-Review | "Review this from 3 perspectives..." |

---

**Ready for data analysis? Let's go to Module 2.2!**
