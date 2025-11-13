# Garmin Swim Data API

Last updated: 2025-11-13 22:44:13 UTC

## API Endpoints

### Summary Data
```
https://raw.githubusercontent.com/kleinxxx/garmin-swim-data/main/swim_summary.csv
```

### Interval Data
```
https://raw.githubusercontent.com/kleinxxx/garmin-swim-data/main/swim_intervals.csv
```

## Usage Example

```python
import pandas as pd

# Read summary data
summary_df = pd.read_csv("https://raw.githubusercontent.com/kleinxxx/garmin-swim-data/main/swim_summary.csv")
print(summary_df.head())

# Read interval data
intervals_df = pd.read_csv("https://raw.githubusercontent.com/kleinxxx/garmin-swim-data/main/swim_intervals.csv")
print(intervals_df.head())
```

## Data Fields

### Summary
- activity_id, date, distance_m, duration_min, avg_hr, swolf, pace_per_100m, calories, avg_stroke_rate

### Intervals
- activity_id, date, interval, swim_stroke, lengths, distance_m, time_sec, cumulative_time_sec, avg_pace, avg_swolf, avg_hr, max_hr, total_strokes, calories

---
*Auto-updated by Garmin Sync Script*
