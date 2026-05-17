# WC2026-ai-prediction


# 🏆 AI model for predicting FIFA World Cup 2026 results using Machine Learning.

*AI ASSISTED (Claude Code)*

## What the model uses
- ELO points (real, from baseline dataset)
- Squad market value (Transfermarkt)
- Recent form (last 15 months, temporally weighted)
- Head-to-head history
- Penalties for injuries to key players

## Datasets -- downloaded via Kaggle
- results.csv — 49k international matches
- Transfermarkt — 47k players with market values
- FIFA Ranking January 2026
- Baseline ELO predictions

## How to run
1. Open SP2026_AI_Prediction_V4.ipynb in Google Colab
2. Upload files from /data/ folder
3. Run all cells in order

## Results
The model predicts probabilities for all 48 teams through
all stages of the tournament — from group stage to final.
