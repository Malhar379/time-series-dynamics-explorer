# Time-Series Dynamics Explorer

Exploration of temporal systems through simulation and statistical analysis.

## Topics Covered

- Stable, noisy, and regime-shifting (transition) systems
- Rolling mean and rolling standard deviation
- Pearson correlation
- Multi-lag autocorrelation (ACF)
- Random walks
- Mean reversion
- Stochastically-forced oscillatory systems

## Key Findings

- **Autocorrelation clearly separates memoryless noise from structural persistence**: noisy series decayed to near-zero autocorrelation within 1 lag, while regime-shifting series retained autocorrelation above 0.6 through 25 lags.
- **Continuous stochastic forcing prevents full convergence** in a mean-reverting oscillator: despite restoring dynamics, the system did not settle within ±1 of equilibrium across 200 simulation steps.

See `notebooks/time_series_behavior.ipynb` for full analysis and plots.

## Tools

- Python
- NumPy
- Pandas
- Matplotlib
- Statsmodels

## Project Structure

```text
time-series-dynamics-explorer/
│
├── notebooks/
│     time_series_behavior.ipynb
│
├── images/
│
├── README.md
│
└── requirements.txt
```

## Concepts Explored

- State evolution
- Memory effects and persistence
- Randomness vs. structure
- Feedback loops and mean reversion