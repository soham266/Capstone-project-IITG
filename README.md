# Capstone-project-IITG
A Brief Overview of the Project

This project is part of the Summer Analytics 2025 Capstone and focuses on building a foundational linear model for dynamic pricing in urban parking lots. By leveraging historical pricing and occupancy data, the model predicts optimal prices to balance demand and availability, helping city planners and operators manage urban mobility more efficiently.

The Tech Stacks Used

To develop this model, we used the following technologies:

-Python: Core programming language

-NumPy: For numerical operations

-Pandas: For handling and analyzing data

-Matplotlib: For plotting static visualizations

-Bokeh & Panel: To create interactive dashboards

-Pathway: For real-time data streaming and transformations


Project Architecture Diagram (Conceptual)

Here's how the workflow is structured conceptually:

1. Data is sourced (e.g., CSV files)

2. Processed using Pandas and NumPy

3. A baseline Linear Regression model is trained

4. Model outputs are visualized with Bokeh and Matplotlib

5. Pathway enables potential real-time stream handling

Project report 

Tools like Mermaid Live Editor can be used to visualize this pipeline interactively.

Detailed Project Architecture and Workflow

1. "Data Collection & Preparation": We begin by importing datasets into Pandas DataFrames and converting relevant columns such as timestamps.

2. "Feature Engineering: Features are derived from raw data using NumPy for improved model accuracy.

3. ""Model Building"": A simple Linear Regression model is implemented to predict parking prices based on historical data.

4. "Evaluation & Visualization": Model outputs are plotted using Matplotlib, and interactive views are built using Bokeh.

5. ""Real-Time Integration": While not fully implemented, Pathway is used for setting up stream-processing capabilities.
