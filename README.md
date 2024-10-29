# Player Analysis Dashboard | Modern Data Engineering GCP Project

## Introduction
This project is focused on building a Player Analysis Dashboard to profile soccer players based on in-game metrics, leveraging modern data engineering practices on Google Cloud Platform (GCP). The dashboard enables analysis of key performance indicators (KPIs) for various player positions (forwards, midfielders, defenders) to aid coaches and analysts in assessing and enhancing player performance.

We’ll use Mage.ai to build an ETL pipeline, BigQuery as the data warehouse, Looker Studio for dashboard visualization, and Cloud Storage for data management.

## Business Requirements
The Player Analysis Dashboard will provide:
1. **Player Profiles** – Show key metrics for each player and comparison across matches.
2. **Position-Specific Insights**:
   - **Forwards**: Proximity to defenders, shot creation.
   - **Midfielders**: Ball-carrying zones, interceptions, and tackles.
   - **Defenders**: Success rates for defensive actions, positioning of defensive lines.

3. **Metrics per Match**:
   - Pass types and zones, shots, duels won with placement.
   - Metrics unique to each player position, enhancing targeted analysis.

## Architecture
![Project Architecture](architecture.jpg)

## Technology Used
1. **Programming Language** - Python
2. **Scripting Language** - SQL
3. **Google Cloud Platform**
   - BigQuery for warehousing player and match data
   - Cloud Storage for data ingestion and storage
   - Looker Studio for creating the analysis dashboard
   - Compute Engine for data processing
## Dataset Used

## Data Model
![Data model image](data_model.jpeg)

## Scripts for Project
1. [Extract Script](mage-files/extract.py)
2. [Transform Script](mage-files/transform.py)
3. [Load Script](mage-files/load.py)

## Complete Video Tutorial
Video Link - *(Placeholder)*
