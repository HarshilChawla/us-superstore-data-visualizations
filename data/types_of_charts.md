# Types of Charts

A comprehensive guide to common chart types, their ideal use cases, and when to avoid them.

---

## 1. Bar Chart (Horizontal)

**What it shows:** Each bar is a category, bar length is value.  
**Example:** Average rating of products (Product A, B, C). Bar length tells us how much higher/lower one product’s rating is compared to others.  
**When to use:** Comparing categories, especially when category names are long (horizontal space helps).  
**When not to use:** If you have time-based data -> better to use a line/column chart; if too many categories (>15) -> becomes cluttered.

---

## 2. Column Chart (Vertical Bars)

**What it shows:** Each bar = category, bar height = value.  
**Example:** Monthly sales Jan–Dec. Each bar’s height shows total sales that month.  
**When to use:** Comparing discrete categories across time or a few options.  
**When not to use:** Don’t use if the trend is most important (line chart is better for continuous trends).

---

## 3. Grouped Bar Chart (Clustered Bar/Column)

**What it shows:** Bars grouped by main category; each group has multiple subcategories.  
**Example:** Sales by Region, grouped by Product type (Region = group, Products = bars). Bars show direct comparison between products within the same region.  
**When to use:** Compare subcategories side by side.  
**When not to use:** More than 3–4 subcategories -> too busy.

---

## 4. Stacked Bar Chart

**What it shows:** Each bar = total value; colored segments = breakdown.  
**Example:** Marketing spend by quarter (bar = total spend, segments = channels like Social, Search, Email).  
**When to use:** Show total + contribution of parts.  
**When not to use:** If comparing individual parts across categories -> hard because only the first segment aligns to a baseline.

---

## 5. Line Chart

**What it shows:** Dots/points connected by lines = values over continuous time.  
**Example:** Website traffic daily for 12 months. The line slope shows increases or decreases.  
**When to use:** Trends, patterns, seasonality.  
**When not to use:** Don’t use for discrete or categorical comparisons (bars are better).

---

## 6. Pie Chart

**What it shows:** Circle cut into slices = proportion of a whole (slice size = % share).  
**Example:** Market share of 4 smartphone brands. Each slice shows relative share of 100%.  
**When to use:** Small number of categories (2–5) that sum to 100%.  
**When not to use:** More than 6 slices, or if exact comparison is needed (bars are clearer).

---

## 7. Area Chart

**What it shows:** Like a line chart, but the area under the line is filled -> emphasizes magnitude over time.  
**Example:** Cumulative users over time; shaded area shows growth visually.  
**When to use:** Show volume/magnitude of a trend.  
**When not to use:** If multiple series overlap -> areas hide each other (use line instead).

---

## 8. Histogram

**What it shows:** Bars = frequency of values in intervals (bins).  
**Example:** Distribution of exam scores (0–10, 11–20, …). Each bar’s height = number of students in that score range.  
**When to use:** Show shape of a distribution.  
**When not to use:** Don’t confuse with bar chart (histogram bins are continuous intervals, not categories).

---

## 9. Line Histogram (Frequency Polygon)

**What it shows:** Same as histogram, but bars replaced by a line connecting midpoints of bins.  
**Example:** Compare Free vs Premium user session durations by overlaying two frequency polygons.  
**When to use:** Overlay multiple distributions clearly.  
**When not to use:** If audience isn’t familiar -> may look like a line chart (clarify axes).

---

## 10. Scatter Plot

**What it shows:** Each dot = one observation (x, y coordinates).  
**Example:** Ad spend (x-axis) vs Revenue (y-axis). Pattern of dots shows correlation.  
**When to use:** Relationship between two numeric variables.  
**When not to use:** Very large datasets with overlapping points (use hexbin or add transparency).

---

## 11. Bubble Plot

**What it shows:** Scatter plot + bubble size = third variable.  
**Example:** Countries: GDP per capita (x), Life expectancy (y), Population size (bubble size). Bigger bubbles = bigger population.  
**When to use:** Compare three numeric variables at once.  
**When not to use:** Too many bubbles overlap -> unreadable.

---

## 12. Box Plot

**What it shows:** Summarizes distribution (median, quartiles, whiskers, outliers).  
**Example:** Delivery times per city: box center = median, box edges = 25th & 75th percentile, whiskers = spread, dots = outliers.  
**When to use:** Compare distributions across groups.  
**When not to use:** If your audience doesn’t understand quartiles -> may need extra explanation.

---

## 13. Waterfall Chart

**What it shows:** Starts from an initial value -> adds positives and negatives -> ends at final total. Bars float up/down showing contributions.  
**Example:** Profit bridge: Revenue -> -COGS -> -Expenses -> +Other income -> Net profit.  
**When to use:** Explain how components build up to a final result.  
**When not to use:** If contributions aren’t sequential (better use stacked bar).

---

## 14. Venn Diagram

**What it shows:** Overlaps of sets.  
**Example:** Customers who bought Electronics, Clothing, Both. Overlapping area shows people in both groups.  
**When to use:** Small number of sets (2–3).  
**When not to use:** More than 3 sets -> unreadable. Use UpSet plot instead.

---

## 15. Tree Map

**What it shows:** Hierarchy shown as nested rectangles; area size = value.  
**Example:** Company revenue: top-level = region, inside rectangles = products. Bigger rectangles = more revenue.  
**When to use:** Show part-to-whole with many categories.  
**When not to use:** If exact comparisons matter (bar chart is clearer).

---

## 16. Marginal Plots

**What it shows:** Scatter plot in center + histograms/densities on axes showing variable distributions.  
**Example:** Height vs Weight scatter, with height distribution (histogram) on top and weight distribution on the side.  
**When to use:** Show both relationship and individual distributions.  
**When not to use:** If only relationship matters -> plain scatter is cleaner.

---

## 17. Subplots (Small Multiples)

**What it shows:** Same chart repeated across categories.  
**Example:** Line charts of monthly revenue, one subplot per region. Each subplot shows pattern in its region.  
**When to use:** Compare many groups while keeping scale consistent.  
**When not to use:** If too many groups (≥20) -> overwhelming.

---
