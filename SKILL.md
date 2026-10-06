---
name: data-story-notebook
description: Explore a dataset, check its weak spots, and build a chart-led story that does not overclaim. Use when: A CSV or spreadsheet needs analysis and a clear explanation.
license: MIT
metadata:
  author: Edward Xiong
  version: 1.0.0
---

# Data Story Notebook

Explore a dataset, check its weak spots, and build a chart-led story that does not overclaim.

## When to use

A CSV or spreadsheet needs analysis and a clear explanation.

## Workflow

1. Inspect schema, missing values, units, and provenance.
2. Ask a question the data can actually answer.
3. Check one alternative explanation.
4. Pair each chart with a plain-language, bounded claim.

## Output

Return a usable result for the user’s actual task. State assumptions, evidence, and uncertainty where they affect the result. Keep the output format suited to the job: working HTML, a storyboard, a decision brief, a draft, code, or a short answer. Do not claim that a result was tested, published, or verified unless that action was completed.

## Starter prompt

> Analyze [dataset] to answer [question]. Start by inspecting columns, row count, missingness, units, duplicates, and likely collection bias. Show the exact transformations. Choose a chart that matches the data and audience. Check whether a subgroup or time window changes the result. Return a reproducible notebook or code, a short finding, chart captions, limitations, and the next data point that would reduce uncertainty. Never infer causation from correlation alone.

## Quality check

Before delivery, check that the result answers the stated need, follows the requested format, and makes any important limitation visible. Invite the user to adjust the result when taste or judgment belongs to them.
