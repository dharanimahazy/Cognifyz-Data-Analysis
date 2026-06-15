# Cognifyz Technologies - Data Analysis Internship
## Submitted by: DHARANI M

---

## Dataset
- **File:** Dataset_.csv
- **Total Restaurants:** 9,551
- **Columns:** Restaurant ID, Name, Country Code, City, Address, Cuisines, Price Range, Aggregate Rating, Votes, Online Delivery, Table Booking, Latitude, Longitude, etc.

---

## Level 1

### Task 1 - Top Cuisines
**Objective:** Determine the top 3 most common cuisines and calculate the percentage of restaurants serving each.

**Files:** `top_cuisines.py`, `plot1_top3_cuisines_pie.png`, `plot2_top10_cuisines_bar.png`

**Key Findings:**
- North Indian: 3,960 restaurants (41.46%)
- Chinese: 2,735 restaurants (28.64%)
- Fast Food: 1,986 restaurants (20.79%)

---

### Task 2 - City Analysis
**Objective:** Identify the city with the highest number of restaurants, calculate average rating per city, and determine the city with the highest average rating.

**Files:** `city_analysis.py`, `plot1_top15_cities_by_count.png`, `plot2_avg_rating_per_city.png`, `plot3_top10_highest_rated_cities.png`

**Key Findings:**
- City with most restaurants: New Delhi (5,473)
- City with highest average rating: Inner City (4.9)
- Among major cities, Lucknow has the highest average rating (4.20)

---

### Task 3 - Price Range Distribution
**Objective:** Visualize the distribution of price ranges and calculate the percentage of restaurants in each category.

**Files:** `price_range_distribution.py`, `plot1_price_range_bar.png`, `plot2_price_range_pie.png`

**Key Findings:**
- Price Range 1 (Low): 4,444 restaurants (46.53%)
- Price Range 2 (Medium): 3,113 restaurants (32.59%)
- Price Range 3 (High): 1,408 restaurants (14.74%)
- Price Range 4 (Very High): 586 restaurants (6.14%)

---

### Task 4 - Online Delivery
**Objective:** Determine the percentage of restaurants offering online delivery and compare average ratings with/without delivery.

**Files:** `online_delivery.py`, `plot1_delivery_pie.png`, `plot2_avg_rating_comparison.png`, `plot3_rating_distribution_boxplot.png`

**Key Findings:**
- With Online Delivery: 2,451 restaurants (25.66%) — Avg Rating: 3.25
- Without Online Delivery: 7,100 restaurants (74.34%) — Avg Rating: 2.47
- Restaurants with online delivery have a 0.78 higher average rating

---

## Level 2

### Task 1 - Restaurant Ratings
**Objective:** Analyze the distribution of aggregate ratings, determine the most common rating range, and calculate average votes.

**Files:** `restaurant_ratings.py`, `plot1_rating_histogram.png`, `plot2_rating_range_bar.png`, `plot3_votes_distribution.png`

**Key Findings:**
- Most common rating range: 3.0–3.5 (2,502 restaurants, 26.20%)
- Average votes per restaurant: 156.91
- Median votes: 31 (heavily right-skewed distribution)

---

### Task 2 - Cuisine Combination
**Objective:** Identify the most common cuisine combinations and determine if certain combinations tend to have higher ratings.

**Files:** `cuisine_combination.py`, `plot1_top10_combos_count.png`, `plot2_top10_combos_rating.png`, `plot3_combo_scatter.png`

**Key Findings:**
- Most common combination: Chinese + North Indian (1,784 restaurants, Avg Rating: 2.70)
- Highest rated combination (min 50 restaurants): Cafe + Desserts (Avg Rating: 3.89)
- Western/Cafe-style combinations consistently rate higher than popular Indian combinations

---

### Task 3 - Geographic Analysis
**Objective:** Plot restaurant locations on a map using coordinates and identify patterns or clusters.

**Files:** `geographic_analysis.py`, `plot1_global_map.png`, `plot2_india_cluster.png`, `plot3_density_heatmap.png`

**Key Findings:**
- 9,052 restaurants have valid coordinates
- India (Country Code 1) dominates with 8,156 restaurants (90%+)
- Major clusters: New Delhi, Gurgaon, Noida region
- Secondary clusters in UAE, Sri Lanka, and Philippines

---

### Task 4 - Restaurant Chains
**Objective:** Identify restaurant chains in the dataset and analyze their ratings and popularity.

**Files:** `restaurant_chains.py`, `plot1_top10_chains_outlets.png`, `plot2_top10_chains_rating.png`, `plot3_outlets_vs_rating_scatter.png`, `plot4_top10_chains_votes.png`

**Key Findings:**
- 734 chains identified covering 2,839 restaurants
- Largest chain: Cafe Coffee Day (83 outlets, Avg Rating: 2.42)
- Highest rated chain (min 5 outlets): Chili's (Avg Rating: 4.58)
- Most popular by votes: Barbeque Nation (28,142 total votes, Avg Rating: 4.35)
- Larger chains tend to have lower ratings; smaller premium chains score higher

---

## Tools & Libraries Used
- Python 3
- pandas
- matplotlib
- seaborn
- itertools

---

## Contact
**Cognifyz Technologies**
- Email: contact@cognifyz.com
- Website: www.cognifyz.com
- LinkedIn: @cognifyz-Technologies
