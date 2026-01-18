


**Our World in Data – Energy Dataset (CSV)**
[https://github.com/owid/energy-data/blob/master/owid-energy-data.csv](https://github.com/owid/energy-data/blob/master/owid-energy-data.csv)

---

# PART I — DATA UNDERSTANDING (1–10)

1. How many **distinct countries** exist in the dataset after excluding aggregates like “World”, “Asia”, etc.?
2. What is the **earliest and latest year** recorded per country, and which countries have the longest continuous time series?
3. Which **columns have more than 30% missing values**, and how does missingness vary by year?
4. For a given year (e.g., 2019), what percentage of countries have **non-null renewable_share_energy**?
5. How many countries report **electricity generation data** but not **primary energy consumption**?
6. What is the distribution (min, max, median) of **energy_per_capita** globally for the latest year?
7. Which countries have **negative or zero values** in fields where that should not logically occur?
8. Are there years where **global aggregates** differ from the sum of country-level values?
9. Which variables are **highly correlated** (>0.8) with each other across all countries?
10. Which countries show **structural breaks** (sudden jumps >50%) in any energy variable year-over-year?

---

# PART II — ENERGY CONSUMPTION ANALYSIS (11–20)

11. Rank countries by **total primary energy consumption** in the most recent year.
12. Rank countries by **energy consumption per capita** and compare against total consumption rankings.
13. Which countries experienced the **highest CAGR** in energy consumption over the last 20 years?
14. Which countries saw **absolute declines** in total energy consumption over the last decade?
15. What is the global **energy consumption growth rate** pre- and post-2015?
16. Which countries contribute the **top 80% of global energy consumption**?
17. How does energy consumption volatility (std dev) differ between OECD vs non-OECD countries?
18. Which countries have **high per-capita energy use but low total energy use**?
19. Identify countries whose energy consumption growth **decouples** from population growth.
20. What proportion of global energy growth comes from the **top 10 consuming countries**?

---

# PART III — ELECTRICITY GENERATION MIX (21–30)

21. For each country, what is the **dominant electricity source** (coal, gas, hydro, nuclear, renewables)?
22. Which countries shifted their dominant electricity source between 2000 and latest year?
23. Rank countries by **coal dependency** (% of electricity from coal).
24. Which countries reduced coal electricity share by **more than 20 percentage points** since 2010?
25. What is the global trend of **coal vs renewables electricity generation** over time?
26. Identify countries where **renewables surpassed fossil fuels** in electricity generation.
27. How diversified is electricity generation by country (Herfindahl-Hirschman Index)?
28. Which countries have **nuclear power** and how has their nuclear share evolved?
29. What regions rely most heavily on **hydropower**?
30. Which countries show the **fastest solar + wind adoption rate**?

---

# PART IV — RENEWABLES & TRANSITION METRICS (31–40)

31. Rank countries by **renewable energy share** in total energy consumption.
32. Which countries improved renewable share the **fastest over the last 10 years**?
33. Which countries stagnated or regressed in renewable adoption despite global trends?
34. What is the average renewable share by **continent or region**?
35. How does renewable share correlate with **energy per capita**?
36. Identify countries where renewable growth is driven mainly by **hydro vs solar/wind**.
37. Which countries crossed **10%, 25%, 50% renewable share** first?
38. What is the distribution of renewable adoption lag (years behind global average)?
39. Which countries show **policy-like inflection points** in renewable adoption curves?
40. Are renewable gains associated with **absolute fossil fuel reductions** or just additive growth?

---

# PART V — ADVANCED ANALYTICS & TIME-SERIES (41–50)

41. Compute year-over-year **energy intensity change** per country (energy per GDP proxy if joined).
42. Which countries show **energy consumption plateauing** despite economic growth?
43. Identify countries with **U-shaped or inverted-U energy trajectories**.
44. What is the rolling 5-year average growth rate of renewables globally?
45. Which countries are **outliers** in energy transition speed relative to peers?
46. Cluster countries by **energy profile similarity** (fossil-heavy, renewable-heavy, mixed).
47. Detect anomalous years (e.g., 2020) and quantify their **global impact**.
48. Which countries are most sensitive to **global shocks** in energy demand?
49. Rank countries by **stability of energy mix** over time.
50. Using historical trends, which countries are **on track** to cross 50% renewables next?

---