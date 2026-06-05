# delhi-weather-analysis

Project: Weather Data Analyzer

Goal: Analyze historical weather data and answer questions such as:

* What was the average temperature?
* Which day was hottest?
* Which day was coldest?
* How many rainy days occurred?
* Which month had the most rainfall?
* Detect heatwave days.
* Compare yearly trends.

Dataset Source:

Mentioned in the notebook  


⸻

Phase 1: Load and Understand Data

Tasks:

1. Load CSV.
2. Inspect columns.
3. Check shape of data.
4. Find missing values.
5. Extract temperature column as NumPy array.

Expected NumPy concepts:

* np.array()
* shape
* ndim
* dtype
* df['column'].to_numpy()

⸻

Phase 2: Basic Statistics

Tasks:

1. Average temperature.
2. Maximum temperature.
3. Minimum temperature.
4. Standard deviation.
5. Median temperature.

Expected concepts:

* mean()
* max()
* min()
* median()
* std()

⸻

Phase 3: Temperature Analysis

Tasks:

1. Find hottest day.
2. Find coldest day.
3. Count days above 35°C.
4. Count days below 10°C.
5. Find top 10 hottest days.

Expected concepts:

* Boolean masking
* argmax()
* argmin()
* argsort()

⸻

Phase 4: Rainfall Analysis

Tasks:

1. Total rainfall in year 2023.
2. Average rainfall.
3. Rainiest day.
4. Percent rainy days.
5. Percent days with no rain.

Expected concepts:

* Conditional filtering
* Aggregation

⸻

Phase 5: Monthly Analysis

Tasks:

1. Extract month from date.
2. Calculate average temperature for each month.
3. Calculate total rainfall for each month.
4. Identify hottest month.
5. Identify wettest month.

Expected concepts:

* Looping with NumPy arrays
* Filtering by condition

⸻

Phase 6: Weather Events

Create your own definitions:

Heatwave:

* Temperature > 40°C

Cold Day:

* Temperature < 5°C

Heavy Rain:

* Rainfall > 50 mm

Tasks:

1. Count heatwave days.
2. Count cold days.
3. Count heavy rain days.
4. Find longest heatwave streak.

The streak problem is a very good NumPy exercise.

⸻

Phase 7: Visualization

Use Matplotlib.

Tasks:

1. Temperature vs Date line chart.
2. Rainfall vs Date chart.
3. Monthly average temperature bar chart.
4. Monthly rainfall bar chart.

⸻

Bonus Challenges

After finishing everything:

1. Find 7-day moving average temperature.
2. Detect unusual temperature spikes.
3. Compare two years of weather.
4. Predict tomorrow’s temperature using a simple rolling average.
5. Build a weather report generator.

Example output:

Weather Summary
Average Temperature: 28.3°C
Maximum Temperature: 43.1°C
Minimum Temperature: 7.8°C
Total Rainfall: 1042 mm
Hottest Day:
2023-06-15
Rainiest Day:
2023-08-21
Heatwave Days:
18
Heavy Rain Days:
24
