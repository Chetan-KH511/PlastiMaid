# Plastmaid: Marine Debris Detection and Tracking

![Basic working!](https://github.com/user-attachments/assets/986a4be9-18d3-4f90-b531-a8adde6992af) <!-- Replace with your logo path -->

## Overview

Plastmaid is an innovative project aimed at detecting and tracking marine debris using advanced machine learning techniques. Leveraging the power of YOLOv8, this application provides real-time insights into underwater debris, helping to combat pollution in our oceans.

## Features

- **Real-time Detection**: Utilizes YOLOv8 for fast and accurate detection of marine debris.
- **User-Friendly Interface**: Built with Flask, providing an intuitive web interface for users.
- **GPU Acceleration**: Optimized for NVIDIA GPUs to enhance performance.
- **Data Visualization**: Visualize detected debris on a map for better understanding and analysis.

## Getting Started

### Prerequisites

- Python 3.7 or higher
- NVIDIA GPU (optional, but recommended for performance)
- Required Python packages (see `requirements.txt`)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/plastmaid.git
   cd plastmaid
   ```

2. Create a virtual environment (optional but recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Download the YOLOv8 model weights and place them in the `flask-server` directory. Ensure the file is named `Chetanyolov8finalfinalv3.pt`.
