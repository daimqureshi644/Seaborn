# Seaborn Plotting Examples

This notebook provides a collection of examples demonstrating various data visualization techniques using the Seaborn and Matplotlib libraries in Python. It covers common plot types and their customization options.

## Table of Contents

- [Line Plot](#line-plot)
- [Histogram Plot](#histogram-plot)
- [Bar Plot](#bar-plot)
- [Scatter Plot](#scatter-plot)
- [Heatmap Plot](#heatmap-plot)
- [Count Plot](#count-plot)
- [Violin Plot](#violin-plot)
- [Pair Plot](#pair-plot)
- [Strip Plot](#strip-plot)
- [Box Plot](#box-plot)
- [Factor Plot (catplot)](#factor-plot-catplot)
- [Styling Plots](#styling-plots)

## Overview

Each section focuses on a specific type of plot, showcasing how to load data (primarily using Seaborn's built-in datasets like 'penguins' and 'tips'), generate the plot, and apply various customizations such as:

-   **Data Loading**: Demonstrates loading datasets using `sns.load_dataset()` and creating sample data with NumPy and Pandas.
-   **Basic Plotting**: Shows the fundamental syntax for each plot type.
-   **Customization**: Examples of adding hues, styles, markers, palettes, titles, labels, and adjusting plot aesthetics.
-   **Figure Management**: Usage of `plt.show()` and `plt.figure()`.

## Plot Types Covered

### Line Plot
Illustrates how to visualize trends and relationships between two continuous variables using `plt.plot()` and `sns.lineplot()`.

### Histogram Plot
Shows the distribution of a single numerical variable using `sns.displot()` with options for KDE (Kernel Density Estimate) and rugs.

### Bar Plot
Demonstrates comparing categorical data with numerical data using `sns.barplot()`, including ordering categories, setting colors, and error bars.

### Scatter Plot
Explores the relationship between two numerical variables using `sns.scatterplot()`, with customizations for hue, style, size, and transparency.

### Heatmap Plot
Visualizes matrix data using `sns.heatmap()`, with examples of custom colormaps, annotations, line properties, and axis labels.

### Count Plot
Shows the counts of observations in each category using `sns.countplot()`, useful for displaying the distribution of categorical variables.

### Violin Plot
Combines aspects of box plots and kernel density plots to show the distribution of data across categories using `sns.violinplot()`, with options for splitting by hue and controlling inner elements.

### Pair Plot
Creates a grid of pairwise relationships in a dataset using `sns.pairplot()`, allowing for different plot types on the diagonal and off-diagonal, and hue mapping.

### Strip Plot
Displays individual observations over a categorical axis using `sns.stripplot()`, often used to show the spread of data points and avoid overplotting.

### Box Plot
Provides a summary of the distribution of a numerical variable across different categories using `sns.boxplot()`, including quartiles, medians, and outliers, with mean visualization options.

### Factor Plot (catplot)
A unified interface to plot categorical data across different types (`'point'`, `'box'`, `'violin'`, `'bar'`, etc.) using `sns.catplot()`, facilitating the creation of faceted plots.

### Styling Plots
Demonstrates how to apply different Seaborn styles (`sns.set_style()`) and adjust figure properties (`plt.figure()`, `sns.despine()`) to enhance plot aesthetics.
