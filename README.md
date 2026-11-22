# SmartSwach — Community Waste Management and Green-Space Mapping

SmartSwach is a community-focused waste management platform designed to help residents report civic issues, track complaint resolution, and explore green spaces in Mumbai. The project combines a mobile-friendly reporting experience, an administrative dashboard, and geospatial mapping.

## Problem Statement

Civic issues such as garbage accumulation, clogged drains, and water shortages need a clear reporting and follow-up process. SmartSwach provides a digital workflow for submitting reports, tracking their status, and helping administrators monitor resolution progress.

## Key Features

### 1. Citizen Issue Reporting
- Submit reports for garbage pile-ups, clogged drains, and water shortages.
- Capture the user's location when submitting a complaint.
- Attach photographs to provide context for reported issues.
- Track complaint status, including pending, in progress, and resolved.

### 2. Administration Dashboard
- Separate administrative access for complaint management.
- Review submitted complaints and update resolution status.
- Monitor total, pending, and resolved complaints.

### 3. Green-Space Discovery
- Display mapped green spaces using geospatial visualizations.
- Use OpenStreetMap data to explore parks, forests, and recreational grounds.
- Highlight locations that may need further review or conservation.

## Technology Stack

| Area | Technologies |
|---|---|
| Backend | Python, Flask, FastAPI |
| Frontend | React, Next.js |
| Database | PostgreSQL |
| Machine Learning / Image Processing | TensorFlow, OpenCV |
| Geospatial Mapping | GeoPandas, Folium, Pyrosm |
| Map Data | OpenStreetMap |

The repository may contain multiple application components; check the source folders and dependency files for the exact setup of each component.

## Local Development

### Prerequisites
- Python 3.8 or later
- Node.js and npm
- PostgreSQL

### Backend

```bash
git clone https://github.com/priyanshukannaujiya/SiliconMafia_Bytecamp2025.git
cd SiliconMafia_Bytecamp2025
pip install -r requirements.txt
python app.py
```

### Frontend

If the frontend is in the `frontend` directory:

```bash
cd frontend
npm install
npm start
```

Check the project configuration if your local branch uses a different entry point or start script.

## Potential Applications

- Community-led civic issue reporting.
- Municipal complaint tracking and prioritization.
- Urban waste-management monitoring.
- Green-space discovery and geospatial planning.

## Project Context

Developed as a team project for Bytecamp 2025.

## Author / Contributor

Priyanshu Kannaujiya — UI/UX contribution.

## Repository

https://github.com/priyanshukannaujiya/SiliconMafia_Bytecamp2025
