<h1>Welcome to the beginning of the "Space Race" in 1957! This notebook explores trends in space exploration, comparing the efforts of the USA, the Soviet Union, and modern commercial organizations like SpaceX.<h1></h1>

<p>Features & Analysis
The notebook performs detailed exploratory data analysis (EDA) and visualization to answer key questions about the history of space flight:

<li>Data Exploration: Analyzing the structure of the dataset, which contains over 4,300 mission records across 9 columns, including organization, location, date, and mission status.</li>

<li>Data Cleaning: Identifying and handling missing values (specifically in mission pricing) and verifying data integrity by checking for duplicates.</li>

<li>Descriptive Statistics: Providing a high-level statistical overview of the launch data.</li>

<li>Visualizations:
<ul>
      <li>Interactive bar charts using Plotly to visualize the number of launches per organization.</li>
      <li>Comparative analysis of historical vs. modern launch frequencies.</li>
    </ul>

<h1>Technologies Used</h1>
<li>Python 3.12</li>

<li>Pandas & NumPy: For data manipulation and preliminary exploration.</li>

<li>Plotly Express: For creating interactive data visualizations.</li>

<li>Matplotlib & Seaborn: For statistical plotting.</li>

<li>iso3166: For handling country codes and geographical data.</li>

<h1>Getting Started</h1>
<h2>Prerequisites</h2>
To run this notebook, you will need to install the following dependencies:
<li>pip install pandas numpy plotly matplotlib seaborn iso3166</li>

<h2>Installation</h2>
<ol>
  <li>Clone this repository: git clone https://github.com/yourusername/space-mission-analysis.git</li>
  <li>Ensure the dataset mission_launches.csv is in the same directory as the notebook.</li>
  <li>Open the .ipynb file in Google Colab or a local Jupyter environment.</li>
</ol>
<h1>Dataset</h1>
<p>The data includes every recorded space mission starting from the launch of Sputnik in 1957 through the current era. Key data points tracked include:

<ol>
  <li>Organisation: The company responsible for the launch</li>
  <li>Location: The launch site.</li>
  <li>Date: The timestamp of the mission.</li>
  <li>Mission_Status: Whether the mission was a success or failure.</li>
  <li>Price: The estimated cost of the mission (if available).</li>
</ol>

Developed as part of a data analysis exploration into historical space trends</p>
</p>
