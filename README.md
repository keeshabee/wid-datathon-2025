# Space Situational Awareness - WiD Datathon 2025

## Team Members
- Keisha Bolaji
- Izabella Wyne
- Ianne Anthony Coleman
- Linda Choong
- Deborah Hemingway
  

## Project Overview
Analyzing satellite collision risk for geo locations including Philadelphia and Rio de Janeiro using TLE data.

## Quick Start
1. Install dependencies: `pip install -r requirements.txt`
2. Run the opensource API coneection to pull the live TLE data for the specific locations: `TLE_Data.ipynb`
3. Run the main notebook: `SateliteDataModel.ipynb`

## Data Sources
- CelesTrak: Active satellite TLE data
- Space-Track.org: Additional orbital parameters

## Key Files
- `src/tle_parser.py` - Extracts risk metrics from TLE
- `src/risk_calculator.py` - Calculates debris and collision scores


## Results
- Philadelphia Risk Score: 6/10
- Rio de Janeiro Risk Score: 5/10
