# vehicles_web_app
Vehicle Sales Data Visualization App

This project is a simple and interactive web application built with Streamlit, designed to visualize a dataset of used vehicle sales in the United States. The app allows users to explore the data by generating dynamic charts with just a few clicks.

Features

Histogram: Visualizes the distribution of vehicle mileage (odometer) using an interactive Plotly histogram.

Scatter Plot: Displays the relationship between mileage (odometer) and price (price) with a Plotly scatter plot.

Interactive UI: Users can enable or disable each visualization through checkboxes.

Instant Feedback: Charts update immediately based on user interaction.

Tech Stack

Python

Pandas for data loading and preprocessing

Plotly Express for interactive visualizations

Streamlit for the web interface

How It Works

The application loads the dataset vehicles_us.csv.

Users select one or both checkboxes:

Build Histogram

Build Scatter Plot

When selected, the app generates:

A histogram of vehicle odometer values

A scatter plot showing odometer vs. price

The results are displayed as interactive Plotly charts directly in the browser.

Purpose

This project serves as a beginner-friendly example of combining data analysis, interactive visualizations, and web app development using Streamlit. It's ideal for learning or demonstrating quick data exploration workflows.
