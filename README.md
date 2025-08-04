# 🧠 Face Recognition with OpenCV

This project demonstrates how to build a simple Face Recognition System using Python and OpenCV. It uses a dataset of face images to train a recognizer and then identifies faces in real time using a webcam.

---

## 📁 Project Structure

```
face-recognition-project/
├── data/
│   ├── mirda/
│   │   ├── 1.jpg
│   │   └── ...
│   ├── molan/
│       ├── 1.jpg
│       └── ...
├── train_model.py
├── recognize.py
├── face_trained.yml
└── README.md
```

---

## ⚙️ How to Run

### 1. ✅ Install Requirements

Make sure Python 3.11+ is installed.  
Then, install OpenCV:

```bash
pip uninstall opencv-python
pip install opencv-contrib-python
```

---

### 2. 🖼️ Prepare Dataset

Create a folder named `data/` with subfolders for each person.  
Each subfolder must contain several images of that person.

**Example:**

```
data/
├── mirda/
│   ├── 1.jpg
│   └── 2.jpg
└── molan/
    ├── 1.jpg
    └── 2.jpg
```

---

### 3. 🧠 Train the Model

Train the face recognizer using the dataset:

```bash
python train_model.py
```

This will generate the model file `face_trained.yml`.

---

### 4. 🎥 Run Face Recognition

Start face detection and recognition via webcam:

```bash
python recognize.py
```

The script will show the webcam feed and recognize known faces.

---

## 📂 Files Description

| File              | Description                              |
|-------------------|------------------------------------------|
| train_model.py     | Script to train the face recognition model |
| recognize.py       | Script to detect and recognize faces       |
| data/              | Folder with images of each person         |
| face_trained.yml   | Trained model saved after running training |

---

