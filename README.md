# cifar-ai-image-classifier
AI image classification system built with **TensorFlow**, **Flask**, and **React** to classify images using the CIFAR-10 dataset
This project implements an AI image classifier with the following stack:

Backend: Flask API for image classification.
Frontend: React for the user interface.
AI Model: TensorFlow model trained on CIFAR-10.
CIFAR-10 Dataset Classes:
airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck
Features:
Upload and classify images via a simple web interface.
Flask API to handle classification requests.
TensorFlow model with an accuracy of ~68%.
Easy setup and usage for local testing.
PythonProjectAI/
├── ai-image-classifier/
│   ├── backend/                # Flask backend API
│   │   ├── app.py              # Main API server
│   │   ├── model/              # Directory for model files
│   │   │   └── image_classifier.h5 # Trained model
│   │   ├── requirements.txt    # Python dependencies
│   │   └── utils.py            # Helper functions for preprocessing
│   │
│   ├── frontend/               # React frontend
│   │   ├── src/
│   │   │   ├── App.js          # Main React component
│   │   │   ├── api.js          # API calls to backend
│   │   │   └── styles.css      # Custom styles
│   │   └── package.json        # Frontend dependencies
│   │
│   ├── train.py                # TensorFlow training script
│   └── README.md               # Project documentation
└── venv/                       # Python virtual environment
