Data Extraction Code

This folder contains Python scripts and Jupyter Notebooks used to extract Formula 1 data for the **F1 Power BI Dashboard** project.

Overview
- **IDE Used**: Jupyter Notebook  
- **Data Source**: FastF1 Python library  
- **Purpose**: Automates downloading and saving of F1 session data (Race, Sprint, Qualifying, etc.) for analysis and visualization in Power BI.  

## Features
- Extracts data for:
  - Race results and lap times  
  - Sprint results and lap times  
  - Qualifying results and lap times  
  - Weather data  
  - Starting grid positions  
  - Session metadata  
- **Note**: By changing the `season` and `session` parameter in the code, data can be downloaded for any year and race session supported by FastF1 (not limited to 2024 & 2025).  

## Why Multiple Scripts Instead of One?
- Each script focuses on a specific dataset (e.g., Race Results, Qualifying Lap Times, Weather Data).  
- This approach allows:
  - Quick debugging  
  - Independent updates to specific data types  
  - Faster re-runs when only one dataset needs updating(eg: for weekends with no sprint races, run only code which downlods race data)  
  - Reduced risk of a single error stopping the entire extraction process  

## Output
- Data is saved in the corresponding season folder with subfolders for:
  - `Results/`
  - `LapTimes/`
  - `SprintResults/`
  - `SprintLapTimes/`
  - `QualiResults/`
  - `QualiLapTimes/`
  - `Weather/`
  - `Session_Metadata_Full.csv`  

## Dependencies
- Python 3.9+
- Jupyter Notebook
- FastF1
- Pandas
- Numpy

 ## Notes and Acknowlegements
- All timestamps are standardized during cleaning for Power BI compatibility.
- Data is organized per season to allow multi-season analysis in the dashboard.
- Parts of the Python code logic were developed with the assistance of ChatGPT (OpenAI) for code structuring, optimization, and troubleshooting.

Install all dependencies via:
```bash
pip install fastf1 pandas numpy jupyter



