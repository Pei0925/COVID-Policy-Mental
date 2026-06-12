# COVID-Policy-Mental
This repository contains the code used to produce the results of the COVID-Policy-Mental project.

## Files

- 20260612_excess_burden_ARIMA_ARIMA-LSTM_Combined.R -- This script generates the pandemic-related excess mental health burden estimates used as the outcome data. Three versions of the outcome were generated using ARIMA, ARIMA-LSTM, and the combined ARIMA + ARIMA-LSTM approach, respectively. The combined ARIMA + ARIMA-LSTM estimates were used in the main analysis, whereas the ARIMA-only and ARIMA-LSTM-only estimates were used for sensitivity analyses.
- 20260612_excess_burden_ITS.R -- This script generates pandemic-related excess mental health burden estimates using an interrupted time-series (ITS) approach. The resulting excess burden estimates were used as an alternative outcome dataset for sensitivity analysis.
- 20260612_policy_indices.R -- This script constructs the COVID-19 policy exposure indices used in the analysis. It processes OxCGRT policy indicators and generates domain-level policy indices, including containment and closure, economic support, health-system measures, and vaccination-related policies. The resulting policy indices were used as the main exposure variables in the association analyses.
- 20260612_excessburden_policyindex.R --
- 20260612_excessburden_policyindicator.R --
- 20260612_independentassociation_excessburden_policyindex.R --
- 20260612_interaction.R --
