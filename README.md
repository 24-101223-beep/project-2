[README.md](https://github.com/user-attachments/files/27531963/README.md)
# Study Environment vs Student Productivity

## Project Overview

This project analyzes how different study environments affect university students' productivity. The study uses survey data collected from 80 university students and explores the relationship between study location, comfort level, distractions, noise, and self-rated productivity.

The main research question is:

> How does the study environment affect students' productivity?

## Hypothesis

Students who study in structured and quiet environments, such as libraries or desks, tend to have higher productivity levels compared to students who study in more comfortable or distracting environments such as beds, noisy spaces, or highly distracting home settings.

## Dataset

The dataset was collected using an online survey distributed to university students through convenience sampling.

### Sample Size

- Total responses: **80 students**
- Target population: **University students**
- Sampling method: **Convenience sampling**

### Survey Topics

The survey collected information about:

- Age group
- Gender
- Usual study location
- Comfort level of study space
- Average study hours per day
- Frequency of changing study location
- Productivity rating when changing study environment
- Main sources of distraction
- Most productive environment
- Effect of noise on focus
- Most productive time of day
- Preference for studying alone or with others

## Files Included

| File | Description |
|---|---|
| `final (1).csv` | Raw survey dataset containing 80 student responses |
| `Project_2 (2) (1).ipynb` | Jupyter/Colab notebook used for data cleaning, descriptive statistics, and visualization |
| `Data Analysis report final (1).pdf` | Final written report summarizing the research question, hypothesis, analysis, charts, conclusion, and limitations |

## Tools and Libraries Used

The analysis was completed using Python.

Main libraries:

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
```

## Analysis Performed

The project includes the following analysis steps:

1. **Data Loading**
   - The CSV survey dataset was imported using pandas.

2. **Data Cleaning**
   - Empty rows were removed.
   - Missing numeric values were filled using the median.
   - Missing text values were filled with `Not Specified`.

3. **Descriptive Statistics**
   - Mean, median, and mode were calculated for numeric survey questions.

4. **Data Visualization**
   - Bar chart showing the distribution of productivity ratings.
   - Pie chart showing the main sources of distraction.
   - Bar chart comparing average productivity by study location.

## Key Results

### Comfort Level of Study Space

- Mean: **3.75**
- Median: **4.00**
- Mode: **3**

This suggests that students generally rated their study spaces as moderately comfortable.

### Productivity Rating When Changing Study Environment

- Mean: **3.41**
- Median: **3.00**
- Mode: **3**

Most students reported moderate productivity when changing their study environment.

### Noise Effect on Focus

- Mean: **3.42**
- Median: **4.00**
- Mode: **4**

Noise appears to have a noticeable effect on students' ability to focus.

## Main Findings

- Most students usually study at home.
- Students studying in libraries showed the highest average productivity rating.
- Mobile phones were the most common distraction.
- Lack of motivation, noise, and people were also major sources of distraction.
- Quiet and structured study environments appear to support better productivity.

## Conclusion

The analysis suggests that study environment has a noticeable relationship with student productivity. Students who study in quieter and more structured environments tend to report higher productivity levels. However, productivity is also affected by other factors such as personal habits, motivation, noise, and digital distractions.

## Limitations

Several limitations should be considered:

- The sample size was limited to 80 responses.
- Most respondents were aged 18–22, which may not fully represent all university students.
- The survey used convenience sampling, so the results may not be generalizable to all students.
- Productivity ratings were self-reported, which may introduce response bias.
- Some participants may have interpreted rating-scale questions differently.

## How to Run the Project

1. Open the notebook file:

```text
Project_2 (2) (1).ipynb
```

2. Upload or place the dataset in the same working directory:

```text
final (1).csv
```

3. Run the notebook cells in order.

4. The notebook will generate descriptive statistics and charts for the survey data.

## Suggested Improvements

Future versions of this project could include:

- A larger and more diverse sample.
- More balanced study locations, such as more library and café respondents.
- Objective productivity measurements instead of only self-reported ratings.
- Additional statistical tests to measure the strength of relationships between variables.
- Cleaner and more consistent column names in the dataset.

## Project Title

**The Analysis of the Performance of Data Analysis Students: Study Environment vs Productivity**
