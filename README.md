# rl-timeseries-fyp
FYP Demo
rl-timeseries-fyp/
├─ app/
│  ├─ streamlit_app.py          # (we’ll add next)
│  ├─ pipeline.py               # wrappers/helpers
│  ├─ charts.py                 # plotting helpers
│  └─ rl_core.py                # your notebook functions/classes
├─ data/
│  ├─ store_results_sales.json          # small, tracked
│  ├─ store_results_demand.json         # small, tracked
│  ├─ train_test_split_paths.json       # small map to CSVs (tracked)
│  └─ cleaned_daily_paths.json          # small map (tracked)
├─ models/                      # large (ignored or LFS)
├─ runs/                        # generated artifacts (ignored)
├─ requirements.txt
├─ .gitignore
└─ README.md
