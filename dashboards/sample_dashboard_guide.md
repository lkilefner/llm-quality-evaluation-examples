# Quick Guide: Turning `evaluations.csv` into a Simple Dashboard

**Goal:** Monitor consistency, regressions, and coverage over time.

1) Import `datasets/evaluations.csv` into Sheets/Excel.  
2) Add conditional formatting for scores < 4.  
3) Create visuals:
   - Average score by criterion (line chart, weekly trend)
   - % of prompts meeting threshold (>=4) by criterion
   - Top failure modes (count “notes” keywords: “jargon”, “off-level”, “constraint-miss”)
4) Add a “release” column if testing model versions (v1.0, v1.1) to track regressions.
5) Add a pivot by **grade band** or **task type** (explanation vs feedback) to ensure coverage.
