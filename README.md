# Space Missions Analysis

## Overview

This project provides a comprehensive analysis of space missions from the inception of the Space Race in 1957 to the present. Using data scraped from [NextSpaceFlight](https://nextspaceflight.com/launches/past/?page=1), this analysis delves into the frequency, success rates, and trends of space missions across different countries and organizations.

![Space Missions](https://i.imgur.com/9hLRsjZ.jpg)

## Features

- **Historical Analysis**: Explore space missions across decades, highlighting key milestones.
- **Data Visualizations**: Graphical representations of mission counts, success rates, and the distribution of missions by country and organization.
- **Trend Analysis**: Insights into the growth and focus of space exploration over time.

## Data Description

The dataset includes the following fields:

- **Date**: The launch date of the mission.
- **Mission**: The name or description of the mission.
- **Vehicle**: The launch vehicle used.
- **Location**: The launch site.
- **LSP**: Launch service provider, the organization responsible for the launch.
- **Mission Outcome**: The result of the mission (e.g., success, failure).
- **Country**: The country associated with the mission.

## Installation

To run the analysis locally, you need to install the necessary Python packages.

1. Install the `iso3166` package:

    ```bash
    pip install iso3166
    ```

2. If you're using Google Colab, you may need to upgrade `plotly`:

    ```bash
    pip install --upgrade plotly
    ```

## Usage

1. **Clone the Repository**:

    ```bash
    git clone https://github.com/yourusername/space-missions-analysis.git
    ```

2. **Navigate to the Project Directory**:

    ```bash
    cd space-missions-analysis
    ```

3. **Open the Notebook**:

    Launch Jupyter Notebook or Google Colab and open `Space_Missions_Analysis.ipynb`.

4. **Run the Cells**:

    Execute the cells in the notebook to perform the analysis and generate visualizations.

## Results

Key findings from the analysis include:

- **Mission Frequency**: A significant increase in the number of space missions over time, with notable spikes during the 1960s and 2010s.
- **Country Contributions**: The USA and Russia (formerly the Soviet Union) have been the most active in space exploration, with increasing contributions from private companies like SpaceX.
- **Success Rates**: The overall mission success rate has improved over time, reflecting advancements in technology and experience.

## Acknowledgments

- Data sourced from [NextSpaceFlight](https://nextspaceflight.com/launches/past/?page=1).
- Visualization tools and techniques were implemented using `plotly` and other Python libraries.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contributing

Contributions are welcome! Feel free to fork the repository, make your changes, and submit a pull request.

## Contact

For any questions or inquiries, you can reach me at: mori.py.data@gmail.com
