CitiTrack – Public Complaint Tracking System

CitiTrack is a web-based platform that enables citizens to submit civic complaints and allows authorities to track, manage, and resolve them through a centralized dashboard. The system integrates DBMS, ADSA (graph theory), and data visualization concepts to support efficient decision-making.

Features

- Citizen complaint submission with category, location, and description.
- Real-time status tracking.
- Admin dashboard for verifying and resolving complaints.
- Analytical charts for category-wise and time-based trends.
- Graph-based hotspot identification using NetworkX.
-SQLite database with structured tables and timestamps.

Tech Stack
-Backend: Python
- Frontend: Streamlit / HTML / CSS
- Database: SQLite 
- Visualization: Plotly, Pandas, NetworkX

How to Run
git clone https://github.com/yourusername/cititrack.git
cd cititrack
pip install -r requirements.txt
streamlit run app.py


Access at:

http://localhost:8501

Project Structure
cititrack/
│── app.py
│── cititrack.db
│── utils/
│── static/
│── templates/
│── requirements.txt
│── README.md

Author

Shweta Mishra – BE IT
Focused on practical software solutions, analytics, and graph-based problem-solving.
