# Independently reconstructed baseline (not original code)

Music-plus-age demonstration only. Concurrent symptom ratings are deliberately excluded.

This is a newly authored, leakage-aware **logistic regression reference implementation** for a user-supplied, approved CSV. It is not a reproduction of the manuscript's full model comparison, tuning, calibration or SHAP workflow, and it has not been run against the study data.

Expected target: `depression_high`.

Run: `python analysis/baseline.py --data /secure/path/approved.csv`

Install: `pip install -r analysis/requirements.txt`

Before use: audit the dataset schema, target definition, temporal leakage, feature eligibility and permissions. Report metrics only after independent validation. Do not commit the data.
