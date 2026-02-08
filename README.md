# Vehicle Theft Intensity Across Indian States (2001)

This project analyzes vehicle theft patterns across Indian states using
population-normalized metrics instead of raw theft counts.

## Motivation
Raw crime numbers are misleading for cross-state comparison due to large
population differences. This analysis normalizes theft and recovery data
using census population and registered vehicle counts to surface true
outliers and enforcement gaps.

## Data Sources
- Census of India (2001)
- State-wise vehicle registration data (2001)
- Reported vehicle theft and recovery data (2001)

All datasets are constrained to the year 2001 to avoid temporal mismatch.

## Methodology
- Data cleaning and state-name harmonization
- Theft per capita and recovery per capita computation
- Z-score normalization to detect statistical outliers
- Comparative analysis across population and vehicle density

## Key Findings
- Some states with moderate absolute theft numbers emerge as extreme
  outliers after normalization.
- Vehicle density alone does not fully explain theft intensity.
- Recovery performance varies significantly even among states with
  similar theft levels.

## Limitations
- Analysis is limited to a single year (2001).
- Policing quality, urbanization, and socioeconomic factors are not modeled.
- State-level aggregation hides intra-state variation.

## Future Work
- Multi-year panel analysis
- Regression-based modeling
- District-level breakdowns

