ChromaSight is a real-time assistive framework designed to enhance visual accessibility for individuals with color vision deficiency. By utilizing computer vision and lightweight machine learning models, the system provides instant linguistic color identification to improve user independence.

🚀 Key Features
Real-Time Color Labeling: Provides instant linguistic identification of colors through a "point and identify" interface.

High Accuracy Classification: Employs a 3D Euclidean distance mapping system powered by the K-Nearest Neighbors (KNN) algorithm.

Optimized for Mobile: Integrated with TensorFlow Lite to ensure high-FPS performance and low latency on mobile devices.

Advanced Image Preprocessing: Features a multi-stage pipeline using median filtering and frame averaging to stabilize detection across variable lighting conditions.

Eyes-Free Interface: Includes a Text-to-Speech (TTS) system that translates mathematical coordinates into human-understandable terms.

📊 Performance
Accuracy: Achieved a 93.08% classification accuracy using optimized KNN mapping.

Efficiency: Implemented Sampling Window (Region of Interest) logic to minimize computational overhead during real-time execution.

🛠️ Technical Stack
Languages: Python.

Frameworks & Libraries: OpenCV, TensorFlow Lite, NumPy, Pandas, Matplotlib.

Algorithms: K-Nearest Neighbors (KNN).

Tools: VS Code, Git.

📂 Project Structure
Preprocessing: Handles median filtering and sensor flicker mitigation.

Core Logic: Manages 3D Euclidean distance calculations and KNN classification.

Mobile Deployment: Contains the TensorFlow Lite implementation for on-device execution.
