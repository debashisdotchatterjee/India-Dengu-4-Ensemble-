# India-Dengu-4-Ensemble-
Reality-Reflecting Ensemble Outputs
==================================
Method:
 - Two-stage model: national total (Poisson GBM) × state share (logit-GBM).
 - Nonnegative-blended ensemble: {Nat×Share, Last-year naive, Nat-growth ratio}.
 - Split-conformal intervals (90%) on BLENDED predictions.
 - Rolling-origin by year (train < t, test = t), excluding provisional rows from training.

Key Tables:
 - evaluation_by_year.csv
 - predictions_all.csv
 - per_state_mae.csv

Key Figures:
 - 01_nat_cases_by_year.png
 - 02_heatmap_state_year.png
 - 03_obs_vs_pred_blended.png
 - 04_coverage_by_year.png
 - 05_mae_by_year.png
 - 06_traj_<STATE>.png  (top 12 states)
 - 07_error_vs_scale.png
 - 08_per_state_mae.png
