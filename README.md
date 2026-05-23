# Trupeer AI Churn & Stickiness Analysis

An interactive product strategy report analyzing how Trupeer AI can reduce churn, improve repeat usage, and build stronger platform stickiness.

## Suggested GitHub Description

Interactive product strategy report on Trupeer AI churn prevention, repeat-cycle journeys, and stickiness.

## Overview

This project was created as part of a Trupeer AI product assignment. It explores why users may stop returning after creating their first video or documentation asset, and proposes journeys and product improvements that can turn one-time creation into repeat usage.

The analysis focuses on:

- User segments and their goals
- The Trupeer user journey
- A repeat-cycle definition of churn
- Churn risks by segment
- Creator-focused churn prevention recommendations
- Churn-reducing journeys
- A stickiness feature concept: **Trupeer Memory + Freshness Engine**

## Key Idea

The report defines churn as:

> A user or organization completes the Trupeer journey once, but does not enter a repeat cycle.

This shifts the analysis away from only onboarding drop-off and toward a deeper product question:

> How can Trupeer turn one successful video or document into a repeatable knowledge workflow?

## Project Structure

```text
.
├── index.html                 # Interactive static web report
├── trupeer-churn-analysis.md  # Markdown research backup
└── README.md                  # Project documentation
```

## Local Preview

Run a local static server:

```bash
python3 -m http.server 8123
```

Then open:

```text
http://localhost:8123/index.html
```

## Deployment

This is a static site and can be deployed on Vercel, Netlify, GitHub Pages, or any static hosting provider. No build step is required.

For Vercel, import the GitHub repository and use the default static deployment settings.
