<h1>
  <span class="headline">Data Visualization with Pandas</span>
  <span class="subhead">Data Visualization Best Practices</span>
</h1>

**Learning objective:** By the end of this lesson, students will be able to evaluate and apply best practices for creating effective data visualizations using different chart types in Pandas.

| Lesson                            | Duration |
| --------------------------------- | -------- |
| Data Visualization Best Practices | 15 min   |

## What Is Data Visualization?

**"Use a picture. It’s worth a thousand words."**
— Tess Flanders, newspaper editor, 1911

**Data visualizations** are a quick way to convey insights from data sets.

Specifically, we can use visuals to:

- Identify outliers during exploratory data analysis.
- Describe patterns or trends in the data.
- Summarize the results of an analysis and communicate key insights.

Because of the way the human brain processes information, charts or graphs that visualize large amounts of complex data are easier to understand than spreadsheets or reports.

Data visualization is a quick, easy way to convey concepts in a universal manner, and you can experiment with different scenarios by making slight adjustments.

![Image Placeholder](TKTK)

## Criteria for Good Visualizations

1. **Simplified**
   - Distill your insight to its essential components.
2. **Easy to Interpret**
   - Use logical ordering and understandable metrics.
3. **Clearly Labeled**
   - Use clearly distinguishable colors and avoid cluttering text.

## Choosing the Right Chart Type

With so many chart types, it can be difficult to know how best to display your data.

When creating a visualization, first think about the **variables** you are displaying, the **volume** of data you’re showcasing, and the **central point you are hoping to communicate** through your visualization.

![Image Placeholder](TKTK)

- Choosing the wrong type of chart for a given data point can result in audience confusion or even be downright misleading.
- If you're unsure of which chart type to use, it may be that you don't have a clear enough point you're trying to make with the chart.

## Bar Charts

**Bar charts** are one of the most common ways of visualizing data. Why? Because they make it easy to **_compare information among categories_**, revealing highs and lows quickly and efficiently.

Bar charts are most effective when you have categorical data and want to explore counts of different categories.

When thinking about using a bar chart, consider:

- Will you use vertical or horizontal bars?
- How will you number your axis (it is always best to start at zero)?
- How will you order your bars?

![Image Placeholder](TKTK)

## Pie Charts

**Pie charts** are the most commonly misused chart type. If there are more than 2–3 categories involved, they can often mislead readers.

Pie charts should only be used to show **_relative proportions or percentages_** of information. If you want to compare data, leave it to bars or stacked bars.

When thinking about using a pie chart, consider:

- The more variables you have, as in the more slices of the pie you have, the more difficult your pie chart is to read.
- Area is very difficult for the eye to read, so if any of your wedges are similar in size, consider using a different chart type.
- If your viewer has to work hard to translate pie wedges into relevant data or compare pie charts to one another, the key points you're trying to convey might go unnoticed.

![Image Placeholder](TKTK)

## Line Charts

**Line charts** (or line graphs) are an excellent way to show **_change over time_**. They work best when you have one time variable and one set of data points to show.

While bar charts can also display time, they don’t show it in a continuous way.

![Image Placeholder](TKTK)

## Scatterplots

**Scatterplots** are great for giving viewers a sense of trends, concentrations, and outliers. They’re also useful for **_illustrating correlations_** between two variables, depending on whether the shape is clearly concentrated or scattered far apart.

This will provide a clear idea of what you may want to investigate further.

![Image Placeholder](TKTK)

<br>

<div class="activity knowledge-check">
  <h2 class="title">What graph should I use for...</h2>
  <span class="minutes">5 min</span>
</div>

### **Scenario:** Change in average income since 1960 for American adults.

<details>
<summary>✅ Click to see the answer: </summary>
<hr>

Answer: Line charts are ideal for expressing change over time.

</details>

### **Scenario:** Amount of sales per state.

<details>
<summary>✅ Click to see the answer: </summary>
<hr>

Answer: Bar charts are best for comparing numbers.

</details>

### **Scenario:** Determine if there's a correlation between book length and sales.

<details>
<summary>✅ Click to see the answer: </summary>
<hr>

Answer: Scatterplots can compare the relationship between two variables.

</details>
