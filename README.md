# Intelligent Attendance System using Face Recognition

An AI-based attendance management system that automatically recognizes students' faces and records attendance using computer vision and deep learning. The system eliminates the need for manual attendance while providing a faster and more accurate solution.

---

## Features

- Face detection using OpenCV
- Face recognition using a trained deep learning model
- Automatic attendance marking
- Attendance stored in CSV format
- Trained model for quick recognition
- Easy to use through Jupyter Notebook

---

## Technologies Used

- Python
- OpenCV
- TensorFlow / Keras
- NumPy
- Pandas
- Jupyter Notebook

---

## Project Structure

```
Intelligent-Attendance-System/
│
├── train/                     # Training dataset
├── Project.ipynb              # Main notebook
├── attendance.csv             # Attendance records
├── attendance_model.yml       # Trained face recognition model
├── .gitignore
└── README.md
```

---

## How It Works

1. Collect face images for each student.
2. Train the face recognition model using the training dataset.
3. Detect faces through the webcam.
4. Recognize the detected face.
5. Automatically mark attendance in `attendance.csv`.

---

## Installation

### Clone the repository

```bash
git clone https://github.com/syeda-iram/Intelligent-Attendance-System.git
```

### Navigate to the project

```bash
cd Intelligent-Attendance-System
```

### Install required libraries

```bash
pip install opencv-python numpy pandas tensorflow jupyter
```

---

## Usage

1. Open the Jupyter Notebook.

```bash
jupyter notebook
```

2. Open **Project.ipynb**

3. Run all cells in sequence.

4. The attendance will be saved automatically in `attendance.csv`.

---

## Dataset

The project uses a custom face image dataset stored in the `train` folder for training the recognition model.

---

## Future Improvements

- Real-time database integration
- Web-based interface
- Multi-classroom support
- Email notifications
- Cloud deployment
- Face mask detection
- Anti-spoofing (liveness detection)

---

## Author

**Tasmiya Iram Syeda**

BS Computer Science  
University of Central Punjab (UCP)

GitHub: https://github.com/syeda-iram

---

## License

This project is developed for educational and academic purposes.
