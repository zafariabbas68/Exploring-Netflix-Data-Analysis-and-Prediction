
# Exploring Netflix Data Analysis and Prediction

This repository provides an in-depth exploration and analysis of Netflix data, covering various aspects like content types, genres, ratings, and trends. Additionally, it involves a machine learning model for predicting content ratings, offering insights into Netflix's global content distribution and its patterns over time.

## Project Overview

This project includes data cleaning, exploration, and visualization of the Netflix dataset. The analysis touches on several key features of the data, such as:

- Content types (Movies vs. TV Shows)
- Genres and their popularity over time
- Distribution of ratings and content based on countries
- Duration comparisons between TV Shows and Movies
- Seasonal trends in Netflix content releases
- Missing data analysis and correlation heatmaps

Additionally, this repository includes a predictive model built using machine learning techniques to forecast ratings based on features such as release year and duration.

## Technologies Used

- **Python** (For data analysis and visualization)
- **Pandas** (Data manipulation and analysis)
- **Matplotlib** (Plotting and data visualization)
- **Seaborn** (For statistical plots and enhanced visualizations)
- **WordCloud** (For generating word clouds from content titles)
- **Scikit-learn** (For machine learning models, regression, and evaluation)
- **Jupyter Notebook** (For interactive analysis)
  
## Project Structure

- **`data/`**: Contains the raw Netflix dataset (CSV) used for analysis.
- **`notebooks/`**: Jupyter notebooks for interactive data exploration and analysis.
- **`scripts/`**: Python scripts for data preprocessing, analysis, and model training.
- **`visualizations/`**: Folder containing saved visualizations in PNG format.
- **`README.md`**: This file, which outlines the project details.

## Key Analysis and Visualizations

### 1. **Content Type Distribution**
   - Analyzed the distribution of Movies and TV Shows on Netflix using a pie chart.
   - Visualized the proportion of Movies vs. TV Shows available on the platform.

### 2. **Top Genres**
   - Identified and visualized the top 10 most popular genres on Netflix.
   - Generated bar plots to show genre frequencies.

### 3. **Content Growth Over Time**
   - Analyzed Netflix's content growth by examining how the number of titles changed year by year.
   - Plotted the growth of Netflix content using a line graph.

### 4. **Movie vs. TV Show Duration Comparison**
   - Compared the duration of Movies and TV Shows using boxplots.
   - Visualized the differences in content length across content types.

### 5. **Top Countries Producing Content**
   - Analyzed and visualized the top countries producing Netflix content using a pie chart.

### 6. **Genre Popularity Over Time**
   - Examined how the popularity of genres has changed over time by year.
   - Used line plots with genre counts across different years.

### 7. **Ratings Distribution**
   - Visualized the distribution of Netflix content ratings using bar plots and heatmaps.
   - Analyzed the frequency of different ratings across Movies and TV Shows.

### 8. **Missing Data Analysis**
   - Identified columns with missing values and visualized the missing data with bar charts.

### 9. **Machine Learning: Rating Prediction**
   - Built a regression model to predict content ratings based on features like `release_year` and `duration`.
   - Evaluated the model using metrics such as Mean Squared Error (MSE).

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/zafariabbas68/Exploring-Netflix-Data-Analysis-and-Prediction.git
   ```

2. Navigate to the project directory:
   ```bash
   cd Exploring-Netflix-Data-Analysis-and-Prediction
   ```

3. Install the required libraries using `requirements.txt`:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Jupyter notebooks or Python scripts for data analysis and visualization:
   ```bash
   jupyter notebook
   ```

5. To run the machine learning model for predicting ratings, use the script in the `scripts/` folder.

## Visualizations

All visualizations (plots, charts, etc.) generated during the analysis are saved in the **`visualizations/`** folder as PNG files. For example, to save a plot:

```python
plt.savefig("visualizations/content_growth.png", format="png")
```

## Future Work

- **Further Model Development**: Test additional machine learning models to improve rating predictions.
- **Enhanced Visualizations**: Create interactive visualizations using tools like Plotly or Dash.
- **Data Enrichment**: Combine Netflix data with additional datasets (e.g., user ratings or reviews) to provide more detailed insights.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- [Netflix Dataset](https://www.kaggle.com/datasets) for providing the raw data
- Libraries such as `Pandas`, `Matplotlib`, `Seaborn`, and `Scikit-learn` for their powerful data analysis and visualization capabilities
- The open-source community for their contributions and support

---

