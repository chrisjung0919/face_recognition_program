# Face Recognition Program

> **Detects and identifies faces from a webcam feed or static images**

---

## 📖 Project Overview
This is my first personal project written in **Python** that uses **OpenCV** and the excellent **face_recognition** library (built on top of *dlib*) to:

- Detect faces in real-time from your webcam
- Recognize multiple known people
- Work with still images as well as live video

---

## 🙏 Inspiration & Credits
| Resource | How it helped |
| -------- | ------------- |
| 🎥 YouTube video — [“Build a Face Recognition Program in Python – Full Guide”](https://www.youtube.com/watch?v=dY29JzuMJJU&list=WL&index=3&t=9s) | Guided me step-by-step through the overall approach and code structure |
| 📚 GitHub — [ageitgey/face_recognition](https://github.com/ageitgey/face_recognition) | Provides the underlying face detection & recognition functionality |

Big thanks to both creators for making this project possible!

---

## ⚙️ Requirements
| Package | Tested Version | Install Command |
|---------|----------------|-----------------|
| Python  | 3.9+ | *(Make sure it’s on your PATH)* |
| OpenCV | latest | `pip install opencv-python` |
| dlib    | 19.22.1 (Windows 64-bit pre-built wheel) | `pip install dlib-19.22.1-cp39-cp39-win_amd64.whl` <br> *(Download the file from this GitHub repo: [Dlib Installation Wheel](https://github.com/Cfuhfsgh/Dlib-library-Installation/blob/main/dlib-19.22.1-cp39-cp39-win_amd64.whl))* |
| CMake   | latest | `pip install cmake` |
| face_recognition | latest | `pip install face_recognition` |

> **Note for Windows users:** The pre-built *dlib* wheel linked above avoids having to compile dlib from source. If you use a different Python version or OS, install the appropriate wheel or build from source.

---

## 📂 How to Use

1. **Run with live camera:**
```bash
python facerecognitions.py
```

2. **Run with an image file:**
```bash
# (If implemented, modify the script to accept file input)
python facerecognitions.py path/to/your/image.jpg
```

> Make sure the script supports command-line arguments for image input if you choose option 2.

---

## 🗂️ Project Structure
```
face_recognition_program/
├─ face recognition program/
│  ├─ facerecognitions.py   # main script
│  ├─ person1.jpg           # known face examples
│  ├─ person2.jpg
│  └─ ...
├─ LICENSE
└─ README.md
```

---

## 📜 License
This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.

---
