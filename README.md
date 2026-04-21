# Data Visualization using Python (Matplotlib)

This project demonstrates fundamental and advanced data visualization techniques using Python libraries such as NumPy, Matplotlib, and Pandas. It covers a wide range of plots commonly used in data analysis and exploratory data science.

---

## Overview

The purpose of this project is to provide practical examples of creating different types of visualizations, including line plots, histograms, pie charts, polar plots, and contour plots. It also includes working with real-world datasets for analysis.

---

## Features

* Line plotting with custom styling
* Adding titles, labels, and grid control
* Multiple line plots in a single figure
* Horizontal and vertical subplots
* Histogram creation for synthetic and real datasets
* Pie chart and donut chart visualization
* Polar coordinate plotting
* Contour (surface) plotting
* Data visualization using a real-world dataset (Iris dataset)

---

## Technologies Used

* Python
* NumPy
* Matplotlib
* Pandas

---

## Code Highlights

### Line Plot

* Basic plotting using `plt.plot()`
* Customization using color, linestyle, and linewidth

### Subplots

* Horizontal layout using `plt.subplot(1,2,...)`
* Vertical layout using `plt.subplot(2,1,...)`

### Histogram

* Frequency distribution visualization
* Custom bin settings and colors

### Real Dataset Visualization

* Loaded Iris dataset using Pandas
* Plotted distributions of:

  * Sepal Length
  * Sepal Width
  * Petal Length
  * Petal Width

### Pie and Donut Charts

* Percentage-based visualization
* Donut chart created using layered pie charts

### Polar Plot

* Circular coordinate visualization using theta and radius

### Contour Plot

* 2D surface representation using mathematical functions
* Includes color bar for value mapping

---

## Project Structure

```bash id="u8n2kd"
data-visualization/
│── main.py
│── iris.csv
│── README.md
```

---

## How to Run

1. Install required libraries:

```bash id="3d2k9p"
pip install numpy matplotlib pandas
```

2. Run the script:

```bash id="g8q1zs"
python main.py
```

---

## Notes

* Ensure the dataset path is correctly set for the Iris dataset.
* Modify the file path in `pd.read_csv()` if running on a different system.
* The project can be extended by adding more datasets and visualization techniques.

---

## Future Improvements

* Add interactive visualizations using Plotly
* Integrate with Jupyter Notebook for better presentation
* Include more real-world datasets
* Enhance visual styling and themes

---

## License

This project is intended for educational purposes and can be used for learning and reference.
