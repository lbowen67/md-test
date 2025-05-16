The **statistics library** in Python is a built-in module that provides functions for calculating mathematical statistics of numeric data. It's included in the Python Standard Library (no installation required) and is useful for basic statistical operations.

**Common Functions in statistics:**
- **mean(data)** - Returns the arithmetic average (mean) of the data.
- **median(data)** - Returns the median (middle value) of the data.
- **mode(data)** - Returns the most common data point.

You have to import the libray before you use it.
```
import statistics
```

Example:
```python3.run
import statistics

# Sample data
data = [12, 12, 12, 15, 20, 20, 25, 30, 35]

# Mean
mean_value = statistics.mean(data)
print("Mean:", mean_value)

# Median
median_value = statistics.median(data)
print("Median:", median_value)

# Mode
mode_value = statistics.mode(data)
print("Mode:", mode_value)
```
```