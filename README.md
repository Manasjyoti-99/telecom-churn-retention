# Keeping customers before they leave
Churn-risk retention proposal for Company A, a telecom operator
(GCI World 2026 September final assignment).

## What this does
- Ranks 100,000 customers by churn risk with a random forest
  (ROC-AUC 0.661 on 20,000 held-out customers).
- Finds two patterns: steep voice-usage decline predicts churn
  (61% vs 49.6% overall), and churn peaks at 10-12 months of tenure (58%).
- Estimates impact under stated assumptions: about 14,600 net benefit
  per 100,000 customers in one month at 0.50 cost per contact.

## Files
- `<name>.ipynb`: full analysis (EDA, features, models, risk ranking, impact)
- `<name>.pdf`: 15-slide proposal deck

## Data
Client.csv and Record.csv are course material from GCI World and are not
included here.
