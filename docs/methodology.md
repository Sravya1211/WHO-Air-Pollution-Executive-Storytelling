# Methodology & Analytical Approach

## 1. Data Understanding

This project uses the WHO Global Air Pollution dataset containing monitored air quality measurements across global locations.

The dataset includes:
- AQI values
- PM2.5 concentrations
- Other pollutant indicators

It excludes unmonitored regions, meaning results reflect monitored urban coverage rather than a full census of all air quality worldwide.

---

## 2. Data Cleaning

- Standardized country and city naming
- Removed incomplete records where necessary
- Checked for missing values and outliers
- Aggregated data using mean values

---

## 3. Statistical Considerations

### Why Mean Was Used
Mean PM2.5 and AQI values were calculated to provide benchmark comparisons across regions and countries.

However:
- Air pollution data is often right-skewed
- Extreme pollution events can inflate averages
- Median values may sometimes provide a more robust central tendency

Mean was selected to align with benchmarking and ranking objectives.

---

## 4. Multi-Level Drill-Down Logic

Initial country-level comparisons did not fully clarify exposure patterns.

Therefore, analysis moved to:
- City-level distribution
- AQI category segmentation

This drill-down approach helped uncover concentrated pollution clusters that were not obvious in aggregated national averages.

---

## 5. Interpretation Guidelines

- Higher AQI = Higher health risk
- Concentration values represent intensity, not counts
- Correlation observed in geographic clustering does not imply causation
- Policy, industrial, and environmental factors likely influence regional disparities

---

## 6. Limitations

- Uneven geographic monitoring coverage
- Potential sensor inconsistencies
- Mean values sensitive to outliers
- No causal claims made

This project is intended for analytical storytelling and high-level benchmarking, not epidemiological conclusions.
