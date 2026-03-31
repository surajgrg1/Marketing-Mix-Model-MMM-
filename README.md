# Meridian Marketing Mix Model

This project applies Google's Meridian Marketing Mix Model to estimate media contribution, compare channel efficiency, and recommend a better budget allocation.

## Main Outcomes

- Baseline demand explained most of total revenue: about 84.3% ($1.11B).
- Marketing contributed about 15.7% of total revenue: about $206M.
- The largest marketing revenue drivers were `Channel_3` ($57M, 4.3%) and `Channel_0` ($37M, 2.8%).
- `Channel_2` was the most efficient paid channel, with the highest ROI at about 2.02, the highest marginal ROI at about 1.14, and the lowest CPIK at about $0.01.

## Budget Optimization Result

Using a fixed $220M budget with channel-level spend constraints of -30% to +30% versus historical spend:

- Non-optimized ROI: `0.7`
- Optimized ROI: `0.8`
- Non-optimized incremental revenue: `$164M`
- Optimized incremental revenue: `$169M`
- Estimated lift from reallocation: about `+$4M`

Recommended budget shifts:

- Increase spend on `Channel_0` by about `$8.8M`
- Increase spend on `Channel_3` by about `$5.9M`
- Increase spend on `Channel_2` by about `$3.6M`
- Reduce spend on `Channel_4` by about `$14.3M`
- Reduce spend on `Channel_1` by about `$4.0M`

Optimized budget mix:

- `Channel_3`: 43%
- `Channel_0`: 22%
- `Channel_4`: 15%
- `Channel_1`: 12%
- `Channel_2`: 7%

## Files

- [Meridian Marketing Mix Model.ipynb](./Meridian%20Marketing%20Mix%20Model.ipynb): notebook used for model fitting and analysis
- [summary_output.html](./summary_output.html): model summary report
- [optimization_output.html](./optimization_output.html): budget optimization report
