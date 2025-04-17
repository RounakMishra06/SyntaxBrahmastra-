# Team Name:
Syntax Brahmastra

Project Title:
NabhSeva – AI-Powered Autonomous Drone Delivery System

✅ Problem Statement Addressed:
Delays in critical deliveries during emergencies, especially in remote and disaster-struck regions, can cost lives. Traditional delivery methods often fail due to traffic, terrain, or lack of infrastructure. NabhSeva provides an AI-powered autonomous drone delivery solution to tackle these challenges with speed, precision, and safety.

✅ Tech Stack Used:
Frontend: HTML, CSS, JavaScript (Dashboard UI)

Backend: Python with Flask

Drone Control: DroneKit-Python, MAVProxy

Mapping & Navigation: GPS, Google Maps API

AI Integration: OpenCV + TensorFlow (for real-time obstacle detection and optimized routing)

Database: Firebase / MongoDB (for storing delivery logs, routes, and user data)

✅ Setup Instructions:
Clone the Repository:

bash
Copy code
git clone https://github.com/your-username/nabhseva.git
cd nabhseva
Set Up the Virtual Environment:

bash
Copy code
python -m venv venv  
source venv/bin/activate  # For Windows: venv\Scripts\activate
Install Required Packages:

bash
Copy code
pip install -r requirements.txt
Launch the Backend Server:

bash
Copy code
python app.py
Start Drone Simulation (if no real drone):

bash
Copy code
dronekit-sitl copter
Access the Dashboard:
Open http://localhost:5000 in your browser.




