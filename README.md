# Review Reliability Scoring

## Overview
This repository implements a methodology to evaluate the reliability and truthfulness of user reviews. The scoring is based on metrics such as helpfulness votes, review recency, and reviewer ranking. The dataset used is the **Amazon 500ECE dataset**.

### Key Features
- **Helpfulness Score**: Calculated using the ratio of helpful votes to total votes, weighted by their squared value.
- **Reliability Score**: Assessed using two approaches:
  1. **Most Recent Reviewer**: Prioritizes the recency of reviews.
  2. **Top-Ranking Reviewer**: Prioritizes highly ranked reviewers.
- **Truthfulness Score**: Combines helpfulness and reliability scores.

## Methodology
The methodology follows the formulas outlined below:
### Helpfulness Score
For a review by user `uᵢ` on item `pⱼ`, the helpfulness score is computed as:
