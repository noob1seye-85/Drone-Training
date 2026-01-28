# Drone-Training
![Python](https://img.shields.io/badge/python-3.13-blue)
# Multimodal AI for Drone-Enabled Search & Rescue

A personal learning & portfolio project to build multimodal AI systems for aerial (primarily), land, and water-based drones. Focus areas:

- **Detection** models: Identify missing persons, vehicles, heat signatures (thermal), distress signals, etc.
- **Guidance** models: Provide terminal navigation decisions to deliver supplies or reach targets (path planning, reinforcement learning elements later)

This repository documents my structured journey from Python foundations → data handling → classical ML → deep learning → computer vision → multimodal fusion → lightweight edge deployment.

Goal: In 3–6 months, produce a showcase project (with notebooks, models, demos) suitable for job applications in AI/ML, computer vision, robotics, or security-adjacent roles.

## Current Status (Early Stage – Foundations)

- **Week 1**: Python basics, pandas data handling, Matplotlib visualization
  - Simulated drone telemetry exploration (altitude, speed, battery, detected objects, thermal anomaly scores)
  - Interactive Jupyter notebooks for EDA

Planned progression:

1. Advanced pandas / NumPy for real sensor data
2. Linear algebra, probability & statistics refresh
3. Classical ML (scikit-learn)
4. Deep learning fundamentals (PyTorch)
5. Computer vision (object detection: YOLO, thermal fusion)
6. Multimodal models & lightweight inference (for drone hardware)
7. Simple agent-based guidance logic
8. Deployment experiments (Jetson/edge, ROS2 basics?)

## Repository Structure
AI-Learning-Path/
├── week1-basics/                  # Python & data fundamentals
│   ├── drone_data_intro.py
│   └── drone_exploration.ipynb    # Preferred interactive notebook
├── week2-.../                     # Future weeks/modules
├── data/                          # Sample datasets (small/public only)
├── notebooks/                     # Main exploration & prototyping notebooks
├── models/                        # Saved models & weights (later)
├── docs/                          # Additional notes, diagrams, references
├── README.md
└── requirements.txt               # pip freeze > requirements.txt later
text## Technologies & Tools (Building Up)

- Python 3.13 (currently)
- Jupyter Lab (primary exploration environment)
- pandas, NumPy, Matplotlib, Seaborn
- Coming soon: scikit-learn, PyTorch, OpenCV/torchvision, ultralytics (YOLO), etc.
- Hardware: RTX 5080 laptop GPU + external RTX 4090 eGPU (CUDA acceleration later)

## Why This Project?

To demonstrate end-to-end AI engineering skills:
- Data wrangling & visualization
- Model design, training, evaluation
- Multimodal reasoning (RGB + thermal + metadata)
- Real-world constraints (edge compute, real-time inference)
- Clear documentation & reproducible notebooks

Inspired by real-world SAR drone applications (thermal person detection, supply drop navigation).

## Getting Started (For Anyone Reviewing)

1. Clone the repo: `git clone https://github.com/noob1seye-85/Drone-Training.git`
2. Create & activate virtual environment:
   ```bash
   python -m venv venv
   .\venv\Scripts\activate    # Windows

Install dependencies (when we have a requirements.txt):Bashpip install -r requirements.txt
Explore notebooks in week1-basics/ with jupyter lab

Progress & Next Milestones

 Environment setup (venv, Jupyter, pandas basics)
 First interactive notebook – simulated drone telemetry
 Load & clean real public drone/flight datasets
 Basic statistical analysis & feature engineering
...

Feel free to open issues or discussions if you're following along or have suggestions!
Last updated: January 2026
Nick – Berlin-based learner building toward AI + robotics applications
