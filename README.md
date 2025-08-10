# F1 Dashboard Project

An interactive Power BI dashboard delivering **insights** into Formula 1 racing, built with Python for automated data extraction and cleaning, and powered by rich visuals in Power BI.

The dashboard currently covers the **2024 season** and the ongoing **2025 season** with automatic updates.  
This is an **active, multi-phase project** designed to evolve into a comprehensive analytics platform for Formula 1.

---

##  Current Status – Phase 1 Completed
- Fully functional dashboard for the 2024 season and live-updating 2025 season.
- Clean, decluttered visuals for race results, qualifying, sprints etc.
- Interactive features for filtering by driver, team, race, and event type.
- Automated Python-based data extraction pipeline using [FastF1].

**Dashboard Overview:**  

<img width="894" height="767" alt="Season Summary Page" src="https://github.com/user-attachments/assets/3246bed2-b62d-4a3f-921c-f5ab5f3508df" />

---

##  Planned Development Roadmap

### **Phase 2 – Historical Data Expansion**
- Integrate results for the **2022 and 2023 seasons**.
- Explore **PostgreSQL** for hosting historical data, improving scalability and query performance.

### **Phase 3 – Advanced Analytics**
- Introduce **telemetry data** for:
- Detailed weather conditions
- Pit stop strategy analysis
- In-depth technical performance and driver behavior breakdowns

### **Phase 4 – AI Integration**
- Build a natural language interface to **answer fan questions** about races, drivers, and events using the dataset.

---

##  Tech Stack
- **Data Extraction & Processing:** Python, FastF1, Pandas, Jupyter Notebooks
- **Visualization:** Microsoft Power BI
- **Hosting:** GitHub
- *(Planned)* PostgreSQL for historical data management
- *(Planned)* AI/LLM for natural language analytics


## Development Notes

- Python scripts developed using [FastF1](https://theoehrly.github.io/Fast-F1/) for extracting official race weekend timing and result data.  
- Data processing performed with **Pandas** and exported to CSV for use in Power BI.  
- ChatGPT was used as a coding assistant for:
  - Drafting and optimizing **DAX measures** for Power BI visuals.
  - Suggesting improvements in Python code structure and debugging.
- All scripts and transformations were manually reviewed, debugged, and tested before use.

---

##  Repository Structure

```
  F1-Dashboard-Project/
  │
  ├── Data extraction code/ # Python scripts for extracting season-wise datasets
  ├── Sample Data/ # Clean datasets used in Power BI (no raw PBIX file)
  ├── Dashboard Images/ # Screenshots & videos for demo purposes
  └── README.md # Main repository documentation

```


---

##  Visuals

### **Dashboard Pages**


<img width="894" height="767" alt="Season Summary Page" src="https://github.com/user-attachments/assets/679edeed-5c96-4bd1-9c9a-25847ff8a03b" />
                                                                   
                                                    Season Summary
<img width="1277" height="721" alt="Qualifying Results" src="https://github.com/user-attachments/assets/d1e818d8-011d-409c-a8f3-263e94c8d50e" />

                                                    Qualifying Results
<img width="1279" height="720" alt="Race Results" src="https://github.com/user-attachments/assets/f0507448-8175-41fd-812a-20387c9e9a00" />

                                                    Race Results
<img width="1281" height="715" alt="Race Pace" src="https://github.com/user-attachments/assets/0117e0e3-4b01-4902-8d7d-f313c7f327bb" />

                                                    Race Pace
<img width="1281" height="720" alt="Constructor Standings" src="https://github.com/user-attachments/assets/8e4fb955-5a8e-4cca-87cd-2241bcf3b40d" />

                                                    Constructor Standings
<img width="1283" height="721" alt="Constructor Stats" src="https://github.com/user-attachments/assets/83f95f5f-6a97-4e8b-ad53-980b42c1d4a4" />

                                                    Constructor Statistics
<img width="1284" height="721" alt="Driver Standings" src="https://github.com/user-attachments/assets/bc077835-0b19-46df-9888-d0177d691c45" />

                                                     Driver Standings
<img width="1314" height="741" alt="Driver Stats" src="https://github.com/user-attachments/assets/c3eead8b-65a3-45bb-83a4-da25b952185a" />

                                                     Driver Statistics
<img width="1317" height="565" alt="Rookie Season 2025" src="https://github.com/user-attachments/assets/39c59e4f-56d6-48de-a457-8f273e8dbc04" />

                                                      Rookie Season 2025
<img width="1282" height="720" alt="Sprint Shootout" src="https://github.com/user-attachments/assets/a5fddcbe-afc6-4918-843e-15365ee3d6e0" />
                                                  
                                                      Sprint Shootout
<img width="1277" height="722" alt="Sprint Results" src="https://github.com/user-attachments/assets/44a45b05-62b1-4fc4-9276-9f0714e910a3" />

                                                      Sprint Results
---
                                                    
## Getting Started
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/F1-Dashboard-Project.git
2. Navigate to the Python scripts and run them to update data
3. Load the processed datasets into Power BI.

## Notes
- The .pbix file is not included in this repository.
- All screenshots saved are for demonstration purposes only.
- Data is sourced from publicly available contents and the FastF1 library.

## Project Timeline
- Phase 1:  Completed — 2024 & 2025 seasons live.
- Phase 2:  Planned — Add 2022 & 2023 seasons, PostgreSQL backend.
- Phase 3:  Planned — Telemetry, pit stops, weather analytics.
- Phase 4:  Planned — AI-driven Q&A on F1 data.

## Contact
For feedback or technical discussions: [Sreekesh](https://www.linkedin.com/in/sreekesh-j-75b74015)

## Disclaimer
This is an unofficial, personal project and is not associated with Formula 1, FIA, or any teams/drivers.
All data and images used are publicly available from external sources.
No ownership is claimed over any third-party data, images, or logos.
The data is provided as-is with no guarantee of accuracy, and should not be used for commercial purposes.
