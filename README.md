# 🏋️ Agent-Based Model for Gym Equipment Usage Prediction

## 📌 Project Overview

This project aims to simulate gym-goer behaviour using Agent-Based Modeling to predict peak equipment usage times and optimise gym layout and operations. By modelling individual agents (gym-goers) with different workout habits, preferences, and constraints, we can provide insights on:

- Optimal times to work out for minimal wait times.
- Gym layout optimisation (e.g., can we please add another smith machine?!)
- Impact of new equipment on gym flow and usage patterns.

## 📊 Data Sources

Plan to use multiple data sources to create an accurate simulation:
- Gym tracking data
- Google Trends 
- Weather data
- Seasonal data

## 🏃‍♂️ Agent-Based Modelling Approach

Each gym-goer is represented as an agent with:
- Workout Goal (Strength, Cardio, Functional Training)
- Equipment Preference (Free Weights, Machines, etc.)
- Time Constraints (Short vs. Long Workouts)
- Social Behaviour (Willing to wait vs. switching exercises if occupied)

The gym environment includes:
- Equipment Availability (Number of squat racks, benches, etc.)
- Peak vs. Off-Peak Hours
- Gym Rush Hour Patterns

## 🔧 Simulation Models
Will explore multiple simulation and machine learning models:
- Multi-Agent Systems (MAS) – Using Mesa in Python to simulate gym-goers.
- Reinforcement Learning (RL) – Optimising gym layout and predicting user flow.
- Queuing Theory – Modelling equipment wait times based on peak-hour congestion.

## 🏗️ Tech Stack

- Python (Mesa, SimPy, Pandas, Matplotlib)
- Machine Learning (Scikit-learn, TensorFlow for RL models)
- Data Collection & Processing (BeautifulSoup for web scraping, Google Trends API)
- Visualisation (Plotly, Seaborn, Geopandas for spatial analysis)


