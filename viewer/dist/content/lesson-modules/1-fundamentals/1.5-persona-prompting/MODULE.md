# Module 1.5: Persona Prompting for Different Perspectives

**Duration:** 20 minutes
**Prerequisites:** Modules 1.1-1.4 completed

---

## What You'll Learn

By the end of this module, you will:
1. Understand why multiple perspectives improve PM decisions
2. Create effective persona prompts for different viewpoints
3. Build a reusable "virtual advisory board"
4. Get engineering, executive, and user research feedback instantly
5. Save and reuse your best persona prompts

---

## Why Multiple Perspectives Matter

As a PM, you make better decisions when you consider different viewpoints:

- **Engineers** catch technical issues early
- **Executives** ensure strategic alignment
- **User Researchers** ground decisions in user needs
- **Designers** consider usability implications
- **Support Teams** know what causes user confusion

But you can't always get everyone in a room. **Persona prompting** lets you simulate these perspectives with Copilot.

---

## What is Persona Prompting?

Persona prompting is asking Copilot to respond **as if it were a specific type of expert**.

### Basic Pattern

```
You are a [ROLE] with expertise in [DOMAIN].
Review this [DOCUMENT/IDEA] and provide feedback from your perspective.
Focus on: [SPECIFIC CONCERNS]
```

### Example

```
You are a Senior Software Engineer with 10 years of experience building
SaaS products. Review this feature proposal and identify:
1. Technical risks or challenges
2. Dependencies we might be missing
3. Rough complexity estimate (T-shirt sizing)
4. Questions you'd ask before committing to build this
```

---

## The Three Core Personas for PMs

We've created three core personas that cover most PM needs:

### 1. The Engineer Persona

**Use for:** Technical feasibility, complexity, risks, dependencies

```
You are a Senior Software Engineer with 10+ years of experience building
SaaS applications. You're pragmatic, technically excellent, and care about
maintainable code. You're not trying to block ideas—you want to help ship
things well.

When reviewing PM documents, you focus on:
- Technical feasibility and complexity
- Hidden dependencies and risks
- Performance and scalability concerns
- Integration challenges
- What's missing from the technical perspective

Be constructive and specific. Suggest alternatives when you see issues.
```

### 2. The Executive Persona

**Use for:** Strategic alignment, stakeholder communication, business impact

```
You are a VP of Product at a Series B SaaS company. You think strategically,
care about business outcomes, and need to communicate with the board and
investors. You're supportive but have high standards.

When reviewing PM documents, you focus on:
- Strategic alignment with company goals
- Business impact and ROI
- Resource allocation implications
- Risks to the business
- How this fits the broader roadmap
- What the board would ask about this

Be direct and strategic. Flag concerns but suggest paths forward.
```

### 3. The User Researcher Persona

**Use for:** User needs, pain points, usability, research gaps

```
You are a Senior User Researcher with expertise in qualitative research,
user interviews, and product discovery. You're the voice of the user in
every conversation.

When reviewing PM documents, you focus on:
- Is this solving a real user problem?
- Do we have evidence for our assumptions?
- What research gaps exist?
- How will users actually use this?
- Edge cases and accessibility concerns
- What would users say about this?

Be empathetic to users but realistic about research needs.
```

---

## Exercise 1: Get Engineering Feedback

Let's try persona prompting on a feature idea.

**Do this now:**

1. Open Copilot Chat
2. Paste this prompt:

```
You are a Senior Software Engineer with 10+ years of experience building
SaaS applications. You're pragmatic and care about shipping well.

Review this feature proposal for TaskFlow (our project management tool):

FEATURE: Smart Task Suggestions
- AI analyzes user's past tasks and current projects
- Suggests next tasks based on patterns
- Predicts task duration based on historical data
- Auto-categorizes new tasks

Provide feedback on:
1. Technical feasibility
2. Complexity estimate (S/M/L/XL)
3. Key technical risks
4. Dependencies we need
5. Questions before committing

Be constructive and specific.
```

3. Review the engineering-perspective feedback

**What to notice:**
- Technical concerns you might not have considered
- Realistic complexity assessment
- Specific questions to answer

---

## Exercise 2: Get All Three Perspectives

Now let's get feedback from all three personas on the same feature.

**Do this now:**

Use this prompt to get all perspectives at once:

```
I need feedback on a feature from three different perspectives.

FEATURE: Smart Task Suggestions for TaskFlow
- AI analyzes user's past tasks and current projects
- Suggests next tasks based on patterns
- Predicts task duration based on historical data
- Auto-categorizes new tasks

Please provide feedback from THREE perspectives:

## 🔧 Engineering Perspective
(10+ year SaaS engineer focused on: feasibility, complexity, risks, dependencies)

## 📊 Executive Perspective
(VP Product focused on: strategy, ROI, resources, board questions)

## 👤 User Research Perspective
(Senior researcher focused on: user problems, evidence, research gaps)

For each perspective, include:
- Key concerns (top 3)
- Questions to answer
- Suggested improvements
```

**What to notice:**
- Each perspective raises different concerns
- Some overlap = high-priority issues
- Comprehensive view of risks and opportunities

---

## Creating Your Own Personas

You can create personas for any role relevant to your work:

### Sales Perspective
```
You are a Senior Account Executive who talks to customers daily.
You know what objections customers have and what features they ask for.
```

### Customer Success Perspective
```
You are a Customer Success Manager who handles onboarding and renewals.
You know what causes churn and what makes customers successful.
```

### Legal/Compliance Perspective
```
You are a Privacy and Compliance Officer at a SaaS company.
You focus on GDPR, data handling, and regulatory requirements.
```

### Designer Perspective
```
You are a Senior Product Designer focused on usability and user experience.
You care about intuitive interactions and design system consistency.
```

---

## Building Your Prompt Library

Save your best personas in a "Prompt Library" document:

### Recommended Structure

```markdown
# My Persona Prompts

## Engineering Review
[Full prompt here]

## Executive Review
[Full prompt here]

## User Research Review
[Full prompt here]

## [Custom personas you create]
[Full prompts here]
```

### Using Saved Prompts

1. Create a Word doc called "Prompt Library"
2. Save your personas there
3. When needed, copy-paste into Copilot
4. Or upload the doc and reference it:

```
Use the Engineering Review persona from my Prompt Library document
to review this feature proposal:

[Your feature proposal]
```

---

## Exercise 3: Create a Custom Persona

Create a persona relevant to your specific situation.

**Think about:**
- What role gives you feedback you need most?
- What specific expertise should they have?
- What should they focus on?

**Template:**

```
You are a [ROLE] with [X] years of experience in [DOMAIN].
You are [CHARACTERISTICS - e.g., practical, strategic, user-focused].

When reviewing [DOCUMENT TYPE], you focus on:
- [Focus area 1]
- [Focus area 2]
- [Focus area 3]
- [Focus area 4]

Be [TONE - constructive, direct, empathetic] and [STYLE - specific, strategic].
```

**Try it now:** Create a persona that would be useful for your actual work.

---

## Multi-Round Persona Dialogue

You can have an ongoing conversation with a persona:

### Example Flow

**You:** Use the Engineer persona and review this PRD.

**Copilot (as Engineer):** [Provides feedback]

**You:** Good points. How would you estimate the timeline for this?

**Copilot (as Engineer):** [Continues in character with timeline estimate]

**You:** Now switch to the Executive persona. What would you tell the board?

**Copilot (as Executive):** [Shifts to executive perspective]

This lets you explore issues deeply from multiple angles.

---

## Best Practices

### Do:
- ✅ Be specific about the persona's expertise
- ✅ Define what they should focus on
- ✅ Ask for constructive feedback
- ✅ Save and reuse effective prompts
- ✅ Iterate on personas that work well

### Don't:
- ❌ Use vague role descriptions
- ❌ Expect perfect real-world accuracy
- ❌ Rely solely on AI perspectives
- ❌ Forget to validate with real stakeholders
- ❌ Skip actually talking to your team

---

## Module Complete!

You now know:
- ✅ Why multiple perspectives improve PM decisions
- ✅ How to create effective persona prompts
- ✅ The three core personas (Engineer, Executive, Researcher)
- ✅ How to build a reusable prompt library
- ✅ How to have multi-round persona dialogues

---

## Next Steps

Continue to **Module 1.6: Building Context with Copilot Memory**

In Module 1.6, you'll learn how to:
- Use Copilot's Memory feature for persistent context
- Teach Copilot about your projects and preferences
- Create reusable context documents
- Get more relevant responses over time

---

## Quick Reference: Core Personas

| Persona | Use For | Key Focus |
|---------|---------|-----------|
| Engineer | Technical review | Feasibility, complexity, risks |
| Executive | Strategic review | ROI, alignment, board readiness |
| User Researcher | User validation | Evidence, user needs, gaps |
| Designer | UX review | Usability, accessibility |
| Sales | Market validation | Objections, feature requests |
| Support | Pain point check | Confusion, common issues |

---

**Ready to make Copilot remember you? Let's go to Module 1.6!**
