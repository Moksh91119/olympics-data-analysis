# Olympic Data Analysis

This project is a web-based data analysis application that provides comprehensive insights into the historical data of the Olympics. Built using Streamlit, this app allows users to explore Olympic data through visualizations and statistical summaries, including medal tallies, country and athlete-specific analyses, and trends over time.

## Features

- **Medal Tally**: Displays the medal tally for selected years and countries, providing insights into each country's performance.
- **Overall Analysis**:
  - **Statistics**: Shows the number of editions, host cities, sports, events, athletes, and nations.
  - **Trend Analysis**: Visualizations showing the growth of nations, events, and athlete participation over time.
  - **Heatmap**: A heatmap of events across different sports over the years.
  - **Top Athletes**: Lists the most successful athletes, filtered by selected sport.
- **Country-wise Analysis**:
  - **Medal Tally Over the Years**: Line chart showing a selected country’s performance over time.
  - **Sport Specialization**: Heatmap showing the country’s most successful sports over time.
  - **Top Athletes**: Lists the top athletes of a selected country.
- **Athlete-wise Analysis**:
  - **Age Distribution**: Distribution of age for all athletes and medalists by medal type.
  - **Age Distribution by Sport**: Age distribution of gold medalists by sport.
  - **Height vs. Weight**: Scatter plot of height and weight of athletes, segmented by medals and gender.
  - **Participation of Men vs. Women**: Line chart showing male and female participation over the years.

## Project Structure

- **app.py**: Main application file that runs the Streamlit app.
- **helper.py**: Contains various helper functions for data processing and analysis.
- **preprocessor.py**: Preprocesses the Olympic data for analysis.

## Datasets

The project uses two datasets:
- **Athlete Events Dataset**: Contains records of athletes and their Olympic achievements.
- **NOC Regions Dataset**: Maps National Olympic Committees (NOC) codes to countries and regions.

Dataset link: [120 Years of Olympic History: Athletes and Results](https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results)

## Getting Started

To set up and run the project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/Moksh91119/olympics-data-analysis.git
    ```

2. **Navigate to the project directory**:
    ```bash
    cd olympics-data-analysis
    ```

3. **Install dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run the application**:
    ```bash
    streamlit run app.py
    ```

## Usage

1. **Medal Tally**: Select a year and country to view the medal tally. Choosing "Overall" will show cumulative results.
2. **Overall Analysis**: Explore top statistics, historical trends, and the most successful athletes by sport.
3. **Country-wise Analysis**: Select a country to view its medal history, top sports, and best athletes.
4. **Athlete-wise Analysis**: View the age distribution, height vs. weight stats, and gender participation trends.

## Contact

For questions or feedback, feel free to reach out:

- **Email**: [jainmoksh03@gmail.com](mailto:jainmoksh03@gmail.com)
- **Portfolio**: [itsmemoksh.in](https://itsmemoksh.in/) - Check out my other projects!

---

Contributions and feedback are welcome! Please open an issue or submit a pull request.
