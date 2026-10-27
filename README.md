# Projects-On-Data-Types
Exploring Different Types of Data
Overview
This repository contains a Jupyter Notebook exploring different types of data and simple ways to represent, inspect, and analyze them using Python.
Tasks Included
1. Graph-Based Data
Represents people as nodes and their relationships as edges in a sample network.
2. Image, Audio, and Video Metadata
Uses Python's Pillow library to inspect image metadata, including file format, size, width, and height. The notebook expects an image file named nature.jpg.
3. Streaming Data
Simulates temperature readings, prints the current time for each reading, and displays an alert when a reading exceeds 35°C.
4. Structured Data
Uses Pandas to create a customer DataFrame, inspect its shape and first rows, and filter customers whose monthly spending is above 500 and whose account type is Premium.
5. Unstructured and Natural Language Data
Checks sample customer feedback for positive and negative keywords and attempts to count sentiment categories.
6. Machine-Generated Data
Organizes IoT temperature sensor readings in a Pandas DataFrame and identifies readings above 75°C as anomalies.
Tools and Libraries
- Python
- Jupyter Notebook
- Pandas
- Pillow (PIL)
- Python standard library: time and datetime
Setup
1. Clone or download this repository.
2. Install the required libraries:
   pip install -r requirements.txt
3. Open project2--github.ipynb in Jupyter Notebook or Google Colab.
4. Run the notebook cells.
Note
The image metadata task uses the path /content/nature.jpg, which is commonly used in Google Colab. Upload nature.jpg to your Colab session or update the path to match your image location.

The notebook is preserved as provided. Review the sentiment-analysis cell's indentation and keyword spellings if you want to improve its results.
Learning Outcomes
- Recognize graph-based, structured, unstructured, streaming, and machine-generated data.
- Represent relationships with nodes and edges.
- Inspect image metadata with Python.
- Simulate a basic data stream and threshold alert.
- Create and filter Pandas DataFrames.
- Explore simple keyword-based sentiment analysis.
- Identify unusual sensor readings using a threshold.
