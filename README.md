🌊 OceanEye – Watching Every Move at Sea
📌 Problem Statement

Marine fouling, also known as biofouling, refers to the unwanted accumulation of microorganisms, algae, plants, and animals on submerged surfaces such as ships, offshore platforms, and naval structures.

This leads to:

Increased drag and reduced speed of ships 🚢

Higher fuel consumption ⛽

Expensive maintenance costs 🛠

Environmental risks due to invasive species 🌱

The Indian Navy and shipping industry face major operational and economic challenges because of this.

💡 Our Solution – OceanEye

OceanEye is an AI-powered intelligent image-based system that can:
✅ Detect and classify fouling species from underwater images.
✅ Estimate fouling density (% coverage – light, medium, heavy).
✅ Display results on a dashboard with visualizations, alerts, and history.

This helps naval engineers and ship operators reduce costs, improve efficiency, and plan timely maintenance.

🔄 System Flow

Input: Underwater images/videos from ROVs, drones, or divers.

Preprocessing: Noise removal, resizing, enhancement, frame extraction.

AI/ML Analysis:

Species classification (e.g., algae, barnacles, mussels).

Density estimation (% surface coverage).

Results Processing: Combine results, compare with thresholds.

Outputs:

Alerts if fouling exceeds threshold.

Data stored in database for history.

Dashboard: Interactive web UI with charts, heatmaps, and reports.

⚙ Features

🔬 Automated Species Classification using deep learning (YOLO/ResNet).

📊 Density Estimation with image segmentation.

🎥 Real-time Video Analysis (future scope with underwater drones).

📈 Dashboard & Visualization with charts, heatmaps, and trends.

🚨 Alert & Notification System when fouling crosses critical levels.

🗄 Historical Data Storage for predictive maintenance.

🌍 Scalable & Adaptable for naval, shipping, and offshore industries.

🛠 Tech Stack

AI/ML: Python, TensorFlow/PyTorch, YOLOv8, ResNet, OpenCV

Backend: Flask / FastAPI

Frontend: React + Tailwind CSS / Dash

Database: PostgreSQL / SQLite

Visualization: Plotly / Power BI

Deployment: Docker, NVIDIA Jetson (for edge AI), AWS/GCP (optional)

How to Run
1️⃣ Backend
cd backend
pip install -r requirements.txt
python app.py

2️⃣ Frontend
cd frontend
npm install
npm start

3️⃣ Open in Browser
http://localhost:3000
