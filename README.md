# HSC Exam Rescrutiny Result Analysis - 2019
This project provides an analytical dashboard to visualize the rescrutiny results of the HSC (Higher Secondary Certificate) Exam in 2019 of Bangladesh. The dashboard highlights various aspects of result changes post-rescrutiny, including grade distributions, subject-wise result changes, fail-to-pass conversions, and more

## Table of Contents

- [Overview](#overview)
- [Key Metrics](#Key)
- [Installation](#installation)
- [Data Sources](#source)
- [Insights](#insights)
- [Future Improvemnts](#future_improvements)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Overview

The dashboard includes several key insights and visualizations:

**Total Changed Results:** Displays the total number of changed results after rescrutiny.
**Groupwise Conversion:** A pie chart showing the distribution of result changes across different academic groups (Science, Business Studies, Arts and Compulsory).
**Grade Comparison:** A bar chart comparing the current and previous grades
**Fail Conversions:** A bar chart illustrating the specific changes from fail grades (F) to passing grades.
**Gradewise Conversion:** A pie chart showing the percentage breakdown of grade changes across different grades.
**Subject-wise Result Change:** A bar chart displaying the number of result changes per subject.
**Fail to Pass:** A donut chart indicating the percentage of students who moved from a failing grade to a passing grade.
**Achieved Golden:** A donut chart showing the percentage of students who achieved a Golden GPA after rescrutiny.
**Previous and Current Grades Table:** A table comparing the count of students in each grade before and after rescrutiny.

## Key Metrics

**Total Changed Results:** 1586
**Fail to Pass Percentage:** 23.71%
**Achieved Golden Percentage:** 8.58%

## Source

The data for this dashboard comes from the 2019 HSC rescrutiny results published by the Education Board of Bangladesh. This dataset includes information on students' previous and current grades across various subjects and groups.

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/tshihab/grade-analysis-report.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd grade-analysis-report
    ```
3. Set up your environment: Make sure you have Python installed, along with necessary libraries like Pandas and Matplotlib for data analysis. If using Power BI, upload the dataset to Power BI for visualization.

4. Load the Data: Load the data into your visualization tool and ensure the data fields align with the visualizations.

5. Run the Dashboard: If using Power BI, open the .pbix file to view and interact with the dashboard.

## Insights

- Groupwise Grade Change: The Science group has the highest number of grade changes.
- Grade Distributions: Significant improvements are seen in the A+, A, and B grades.
- Fail Conversion: There’s a notable improvement in students moving from a failing grade (F) to passing grades.
- Subject Analysis: English and Physics show the most significant number of grade changes.

## Improvements

- Adding more detailed analytics on grade improvements over multiple years.
- Incorporating machine learning to predict potential grade changes based on initial scores.
- Adding filtering options by region or demographic data.

## Contributing

Contributions are welcome! Please feel free to submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

Special thanks to the Education Board for providing the rescrutiny data and to all contributors to this project.
