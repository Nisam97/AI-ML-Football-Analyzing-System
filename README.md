# AI-ML-Football-Analyzing-System
🎥⚽ Real-time football analysis using AI, YOLO, and computer vision.
This repository contains an AI-powered computer vision system designed for advanced football match analysis using YOLO, OpenCV, and ByteTrack. It provides real-time detection, tracking, and tactical visualizations of players, referees, and the ball from football match footage.

🔍 Key Features

⚡ Real-Time Detection: Detect players, ball, and referees using YOLOv5/v8.

🧠 Team Classification: Auto-assign players to teams based on jersey color using HSV & CNN.

🎥 Camera Calibration: Correct perspective and align pitch using homography.

📊 Tactical Visualization:

📈 Radar views

![image alt](https://github.com/Nisam97/AI-ML-Football-Analyzing-System/blob/main/Screenshot%202025-03-10%20104140.png?raw=true)

🔷 Voronoi diagrams

![image alt](https://github.com/Nisam97/AI-ML-Football-Analyzing-System/blob/main/Screenshot%202025-03-10%20104202.png?raw=true)

🔥Heatmaps

![image alt](https://github.com/Nisam97/AI-ML-Football-Analyzing-System/blob/main/Screenshot%202025-03-10%20104242.png?raw=true)

☁️ Google Colab Compatible: Optimized for Roboflow models and cloud execution.

🚀 Getting Started

You can run this project in Google Colab with GPU or locally (requires NVIDIA GPU with CUDA support).

Before you start Configure your API keys

  Go to your Roboflow Settings page. Click Copy. This will place your private key in the clipboard.
  In Colab, go to the left pane and click on Secrets (🔑)
  
  Store Roboflow API Key under the name ROBOFLOW_API_KEY.

## 🛠️ Technologies Used

- **Language**: Python 3.x
- **Deep Learning**: PyTorch, YOLOv5/v8, TensorRT
- **Computer Vision**: OpenCV, Supervision (Roboflow)
- **Tracking**: ByteTrack
- **Visualization**: Matplotlib, Seaborn
- **Data Handling**: NumPy, Pandas
- **Cloud**: Google Colab, Roboflow API

📜 References

Roboflow Blog - Camera Calibration

YOLOv5 by Ultralytics

Supervision Library


Based on and inspired by Roboflow's Sports Computer Vision project. Licensed under MIT.


