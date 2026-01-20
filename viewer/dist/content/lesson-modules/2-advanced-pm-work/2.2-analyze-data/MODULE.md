# Module 2.2: Analyzing Product Data with Copilot

**Duration:** 30 minutes
**Prerequisites:** Module 2.1 completed

---

## What You'll Learn

By the end of this module, you will:
1. Upload and analyze CSV/Excel data in Copilot
2. Use Excel Copilot for in-spreadsheet analysis
3. Perform funnel analysis and find drop-offs
4. Interpret A/B test results
5. Use the Analyst agent for complex data reasoning

---

## Why PMs Need Data Analysis Skills

Data informs almost every PM decision:

- **Discovery:** What problems exist?
- **Prioritization:** Which has biggest impact?
- **Validation:** Did our solution work?
- **Roadmap:** Where should we invest?

Copilot makes data analysis accessible without needing SQL or Python.

---

## Three Ways to Analyze Data

| Method | Best For | How |
|--------|----------|-----|
| **Copilot Chat** | Quick analysis, summaries | Upload file to chat |
| **Excel Copilot** | Spreadsheet work, formulas | Alt+I in Excel |
| **Analyst Agent** | Complex reasoning, statistics | Left panel → Analyst |

---

## Method 1: Data Analysis in Copilot Chat

### Uploading Data

1. Go to Copilot Chat (copilot.microsoft.com)
2. Click the 📎 attachment icon
3. Select your CSV or Excel file
4. Copilot processes the data

### Supported Formats
- CSV files
- Excel (.xlsx)
- Google Sheets (export as CSV first)

### Basic Analysis Prompts

**Summarize the data:**
```
Analyze this data file and give me:
1. What data is included (columns, rows)
2. Key summary statistics
3. Any patterns you notice
4. Data quality issues (missing values, outliers)
```

**Ask specific questions:**
```
From this data:
- What's the average conversion rate?
- Which user segment has highest retention?
- What's the trend over the last 6 months?
```

---

## Exercise 1: Funnel Analysis

Let's analyze TaskFlow's activation funnel.

**Sample Data (copy this if you don't have a file):**

```
Stage,Users,Conversion_Rate
Signup Started,10000,100%
Signup Completed,7500,75%
First Project Created,4500,60%
First Task Created,3150,70%
Invited Team Member,1260,40%
Active at Day 7,756,60%
```

**Do this now:**

1. Create a CSV file with this data (or paste directly)
2. Upload to Copilot Chat
3. Use this prompt:

```
Analyze this activation funnel data for TaskFlow.

Please provide:

1. **Funnel Visualization**
   - Show the funnel with drop-off percentages

2. **Biggest Problems**
   - Where are the biggest drop-offs?
   - What's the overall signup-to-active rate?

3. **Benchmarking**
   - How do these compare to typical SaaS benchmarks?
   - Which stages are underperforming?

4. **Opportunity Analysis**
   - If we improved "Invited Team Member" from 40% to 50%, 
     what would be the impact on Day 7 active users?
   - Which improvement would have the biggest ROI?

5. **Hypotheses**
   - What might be causing each major drop-off?
   - What would you investigate first?
```

---

## Method 2: Excel Copilot

For working within spreadsheets, use Copilot directly in Excel.

### How to Access

1. Open your data file in Excel
2. Press **Alt+I** to open Copilot panel
3. Or click the Copilot icon in the ribbon

### What Excel Copilot Can Do

| Task | Example Prompt |
|------|----------------|
| Add formulas | "Add a column calculating conversion rate" |
| Create charts | "Create a chart showing the funnel" |
| Highlight patterns | "Highlight rows where conversion < 50%" |
| Create pivot tables | "Create a pivot table by month and segment" |
| Clean data | "Remove duplicate rows" |
| Sort & filter | "Sort by conversion rate, lowest first" |

### Exercise 2: Excel Copilot

**Do this now:**

1. Open the funnel data in Excel
2. Press Alt+I to open Copilot
3. Try these prompts:

```
Add a column showing the cumulative drop-off from signup
```

```
Create a funnel chart visualizing the conversion at each stage
```

```
Highlight the stages where conversion rate is below 60%
```

---

## Method 3: Analyst Agent for Complex Analysis

For multi-step reasoning and statistical analysis, use the Analyst agent.

### When to Use Analyst

- Complex calculations
- Statistical significance testing
- Multi-variable analysis
- Forecasting and projections
- "What if" scenarios

### Exercise 3: A/B Test Analysis with Analyst

**Scenario:** We ran an A/B test on the onboarding flow.

**Sample Data:**

```
Variant,Users,Completed_Onboarding,Conversion_Rate
Control,5000,1750,35%
New_Wizard,5000,2150,43%
```

**Do this now:**

1. Click **Analyst** in the left panel
2. Enter this prompt:

```
Analyze this A/B test result for TaskFlow's onboarding:

Control: 5000 users, 35% conversion (1750 completions)
New Wizard: 5000 users, 43% conversion (2150 completions)

Please provide:

1. **Statistical Significance**
   - Is this result statistically significant? (95% confidence)
   - What's the p-value?
   - Show your calculation

2. **Effect Size**
   - What's the absolute lift?
   - What's the relative lift?

3. **Business Impact**
   - If we get 10,000 signups/month, how many more 
     activations would we get with New Wizard?
   - Annualized impact?

4. **Recommendation**
   - Should we ship this?
   - Any caveats or concerns?

Show your reasoning step by step.
```

---

## Common PM Data Analysis Scenarios

### Scenario 1: User Segmentation

```
Analyze this user data and identify distinct segments based on:
- Usage patterns
- Feature adoption
- Engagement levels

For each segment:
- Name and describe the segment
- Size (% of users)
- Key characteristics
- PM implications (what to build for them)
```

### Scenario 2: Feature Usage Analysis

```
Analyze feature usage data:
- Which features have highest adoption?
- Which features have low adoption but high satisfaction?
- Which features have high adoption but low satisfaction?
- What does this suggest for our roadmap?
```

### Scenario 3: Retention Analysis

```
Analyze this retention cohort data:
- What's our 30/60/90 day retention?
- Which cohorts retain best?
- What's the typical churn point?
- How does retention correlate with feature usage?
```

### Scenario 4: Survey Analysis

```
Analyze these survey responses:
- What are the top themes?
- Sentiment breakdown (positive/negative/neutral)
- Correlation between satisfaction and specific answers
- Key quotes for each theme
```

---

## Data Analysis Workflow for PMs

### Step 1: Define Your Question
Before analyzing, be clear:
- What decision am I trying to make?
- What would change my mind?
- What data would answer this?

### Step 2: Get the Data
- Export from your analytics tool
- Clean if necessary
- Upload to Copilot

### Step 3: Explore First
```
Summarize this data. What patterns do you see?
What's interesting or surprising?
```

### Step 4: Answer Specific Questions
```
Based on this data, [specific question]?
```

### Step 5: Validate
- Do the numbers make sense?
- Cross-check with other sources
- Consider what's NOT in the data

### Step 6: Decide
- What does this mean for my decision?
- What's the recommended action?

---

## Best Practices

### Do:
- ✅ Start with clear questions
- ✅ Use Analyst for complex reasoning
- ✅ Ask Copilot to show its work
- ✅ Validate surprising findings
- ✅ Consider sample sizes and significance

### Don't:
- ❌ Trust numbers without validation
- ❌ Skip statistical significance for A/B tests
- ❌ Ignore what's NOT in the data
- ❌ Over-complicate simple analyses
- ❌ Make decisions on tiny sample sizes

---

## Module Complete!

You now know:
- ✅ How to upload and analyze data in Copilot Chat
- ✅ How to use Excel Copilot for spreadsheet analysis
- ✅ How to perform funnel analysis
- ✅ How to interpret A/B test results with Analyst
- ✅ The data analysis workflow for PMs

---

## Next Steps

Continue to **Module 2.3: Product Strategy with Copilot**

In Module 2.3, you'll learn:
- Strategic frameworks (SWOT, Porter's, etc.)
- Competitive positioning analysis
- Roadmap prioritization
- Stakeholder communication of strategy

---

## Quick Reference

| Analysis Type | Tool | Example Prompt |
|---------------|------|----------------|
| Quick summary | Copilot Chat | "Summarize this data" |
| Formulas/charts | Excel Copilot | "Create a pivot table by..." |
| Statistical analysis | Analyst | "Is this A/B test significant?" |
| Complex reasoning | Analyst | "What's driving this trend?" |

---

**Ready for strategy? Let's go to Module 2.3!**
