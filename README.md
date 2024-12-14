# Python-Data-Visualization

Link to Presentation: https://docs.google.com/presentation/d/1G-VPMlk76jdcX9YR4CSDI5KVv6gOvaMxvHlGJ50Y3C8/edit?usp=sharing

Techniques Used: Dimensionality Reduction, Geospatial Mapping, Preprocessing Pipeline.
College Scorecard Dataset Project
Overview

This project analyzes the College Scorecard dataset, which provides information on U.S. higher education institutions, including tuition, graduation rates, enrollment, and endowments. The dataset's diverse features allow for comprehensive analyses, including dimensionality reduction, geospatial mapping, and interactive visualizations.

Key Features

    Dimensionality Reduction: Visualized t-SNE results in 3D to explore relationships between institutions.
    Geospatial Mapping: Interactive Folium map showing college locations and graduation rates.
    Preprocessing Pipeline: Cleaned, standardized, and encoded data for accurate analysis.

Use Cases

    College Selection: Identify affordable colleges with high graduation rates.
    Policy Insights: Analyze regional disparities in educational outcomes.
    Geospatial Analysis: Visualize performance metrics across the U.S.

Project Result

![image](https://github.com/user-attachments/assets/012cc90d-f1ea-49ea-978a-d1b1e864cde8)
With this 3D t-SNE visualization we can explore how U.S. colleges compare based on multiple factors, such as graduation rates, tuition, and enrollment. Each dot represents a college, color-coded by its graduation rate group (e.g., High, Medium, or Low), allowing users to easily identify performance clusters. 

For example, the highlighted point shows the University of Houston-Downtown in the "Medium" group, with specific t-SNE dimensions and state details provided on hover which simplifies complex data, helping students, researchers, and policymakers spot patterns, compare institutions, and gain insights into how colleges group together based on shared characteristics.

The selected features for dimensionality reduction are:

    Average Net Price Tuition
    6-Yr Grad Rate
    Endowment in 2020
    Percent of Pell-Grant
    Tuition Out-of-State
    Undergrad Enrollment


![image](https://github.com/user-attachments/assets/6c255023-e16c-4942-868e-f3dbc05d34ec)
This interactive map offers an engaging way to explore colleges across the U.S., showcasing their geographic distribution and key details like graduation rates and locations. Each marker represents a college and reveals useful information, such as its name, 4-Year and 6-Year graduation rates, and city, when clicked. When we zoom out we can see the clusters along with the numbers. So the higher the number the more colleges are inn that region. By clustering markers, we can see  the map helps us to spot areas with many colleges or regions where they’re sparse. So it might be a useful tool for students looking for nearby options, policymakers working to improve access to education, and researchers studying how location influences college performance. The ability to zoom, explore clusters, and interact with specific institutions makes the map both informative and easy to use.
Project Building

![d1d4d413-f32d-4595-8553-900cd4584c91](https://github.com/user-attachments/assets/03c503ab-5c69-4244-a2c2-e32f161203f7)


How to Run

    Clone this repository.


Run the Jupyter notebook for analysis and visualization:

    jupyter notebook DataViz_Project.ipynb

    Open interactive_college_map.html for the interactive map.

Visualization Samples

    3D t-SNE Visualization: Explore relationships among institutions.
    Interactive Map: View college locations and graduation rates.
