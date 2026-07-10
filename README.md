# Electricity Market Research Skills

This repository contains reusable AI skills for electricity market research. It is designed as a portable skill library that can be used by ChatGPT, Claude, Gemini, DeepSeek, Doubao, Copilot, and other AI assistants.

The goal is to turn repeated research tasks into structured workflows. Each skill describes when it should be used, what inputs are needed, what steps the AI should follow, what outputs should be produced, and what quality checks are required.

## How to Use This Repository

When using this repository with an AI assistant, start with the following instruction:

```text
Please read the README.md of this repository first. Then choose the most relevant skill according to my task, read the corresponding SKILL.md, and complete the task strictly following that workflow.
```

## AI Routing Instruction

When an AI assistant uses this repository, it must first read this README and then select the most relevant skill according to the user's task.

After selecting a skill, the assistant must read the corresponding `SKILL.md` before answering.

If multiple skills are relevant, the assistant should combine them in this order:

1. `research_planning`
2. `literature_review`
3. `policy_analysis`
4. `power_system_background`
5. `market_data_processing`
6. `market_mechanism_modeling`
7. `electricity_price_forecasting`
8. `visualization`
9. `academic_writing`
10. `paper_review_and_rebuttal`

If the assistant cannot access the folder automatically, it should ask the user to provide the raw link or content of the relevant `SKILL.md`.

## Skill Catalog

### 1. Research Planning Skill

Folder: `skills/research_planning/`

This skill helps decompose broad electricity market research topics into concrete research questions, technical routes, data needs, model choices, and writing plans.

Use this skill when the task involves:

1. Choosing a research direction.
2. Turning an idea into a research plan.
3. Designing a paper structure or thesis chapter.
4. Planning literature reading.
5. Comparing possible methods and feasibility.

Typical outputs:

1. Research roadmap.
2. Task decomposition.
3. Paper outline.
4. Method selection table.
5. Risk and feasibility analysis.

### 2. Literature Review Skill

Folder: `skills/literature_review/`

This skill helps search, classify, compare, and synthesize academic literature related to electricity markets, power systems, energy economics, renewable integration, demand response, and market design.

Use this skill when the task involves:

1. Finding papers on a specific electricity market topic.
2. Summarizing one or more papers.
3. Comparing methods across papers.
4. Identifying research gaps.
5. Building a literature review section.

Typical outputs:

1. Literature table.
2. Research trend summary.
3. Method comparison.
4. Research gap analysis.
5. Review style paragraphs.

### 3. Policy Analysis Skill

Folder: `skills/policy_analysis/`

This skill helps analyze electricity market policies, market rules, regulatory documents, reform plans, and institutional designs.

Use this skill when the task involves:

1. Interpreting electricity market policies.
2. Comparing market rules across regions.
3. Analyzing spot market, ancillary service market, capacity market, or green certificate rules.
4. Extracting policy logic from official documents.
5. Evaluating policy impact on market participants.

Typical outputs:

1. Policy summary.
2. Rule comparison table.
3. Mechanism flowchart.
4. Stakeholder impact analysis.
5. Policy logic explanation.

### 4. Power System Background Skill

Folder: `skills/power_system_background/`

This skill explains core power system and electricity market concepts in a research oriented way.

Use this skill when the task involves:

1. Locational marginal pricing.
2. Economic dispatch.
3. Unit commitment.
4. Congestion management.
5. Frequency regulation and reserve.
6. Day ahead market and real time market.
7. Market clearing and settlement.
8. Renewable integration and grid constraints.

Typical outputs:

1. Concept explanation.
2. Formula derivation.
3. Example calculation.
4. Diagram style explanation.
5. Relationship between physical grid operation and market rules.

### 5. Market Data Processing Skill

Folder: `skills/market_data_processing/`

This skill helps clean, merge, inspect, and structure electricity market datasets.

Use this skill when the task involves:

1. Electricity price data.
2. Load data.
3. Renewable generation data.
4. Generator bidding data.
5. Transaction data.
6. Missing values and outliers.
7. Time alignment.
8. Dataset construction for modeling.

Typical outputs:

1. Cleaned dataset.
2. Data quality report.
3. Processing code.
4. Descriptive statistics.
5. Time series alignment method.

### 6. Electricity Price Forecasting Skill

Folder: `skills/electricity_price_forecasting/`

This skill helps design and evaluate forecasting workflows for electricity prices, load, renewable output, and market volatility.

Use this skill when the task involves:

1. Day ahead price forecasting.
2. Real time price forecasting.
3. Price spike prediction.
4. Load forecasting.
5. Renewable generation forecasting.
6. Time series modeling.
7. Machine learning or deep learning forecasting.

Typical outputs:

1. Forecasting pipeline.
2. Feature engineering plan.
3. Model comparison table.
4. Evaluation metric explanation.
5. Reproducible code framework.

### 7. Market Mechanism Modeling Skill

Folder: `skills/market_mechanism_modeling/`

This skill helps build mathematical models for electricity market mechanisms and participant behavior.

Use this skill when the task involves:

1. Market clearing model.
2. Economic dispatch model.
3. Unit commitment model.
4. Bidding strategy.
5. Game theory model.
6. Congestion pricing.
7. Ancillary service mechanism.
8. Capacity mechanism.
9. Demand response mechanism.

Typical outputs:

1. Mathematical formulation.
2. Variable and parameter table.
3. Objective function and constraints.
4. Mechanism explanation.
5. Simulation design.

### 8. Visualization Skill

Folder: `skills/visualization/`

This skill helps create publication quality figures, flowcharts, data plots, and conceptual diagrams for electricity market research.

Use this skill when the task involves:

1. Plotting market prices.
2. Showing load and renewable curves.
3. Drawing market clearing diagrams.
4. Designing mechanism flowcharts.
5. Improving figures for papers or presentations.
6. Creating comparison charts.

Typical outputs:

1. Figure design plan.
2. Python or MATLAB plotting code.
3. Paper style chart.
4. Diagram layout.
5. Caption draft.

### 9. Academic Writing Skill

Folder: `skills/academic_writing/`

This skill helps write and revise academic text for electricity market research.

Use this skill when the task involves:

1. Writing abstract.
2. Writing introduction.
3. Writing literature review.
4. Writing methodology.
5. Writing results and discussion.
6. Improving academic logic.
7. Translating Chinese research ideas into English academic writing.

Typical outputs:

1. Paper section draft.
2. Revised paragraph.
3. Logical structure improvement.
4. Academic expression polishing.
5. Title and abstract alternatives.

### 10. Paper Review and Rebuttal Skill

Folder: `skills/paper_review_and_rebuttal/`

This skill helps review manuscripts, identify weaknesses, and prepare responses to reviewers.

Use this skill when the task involves:

1. Checking manuscript novelty.
2. Finding logical gaps.
3. Reviewing method validity.
4. Drafting reviewer comments.
5. Writing rebuttal letters.
6. Planning revisions after peer review.

Typical outputs:

1. Manuscript weakness checklist.
2. Reviewer style comments.
3. Response to reviewers.
4. Revision plan.
5. Improved manuscript text.
