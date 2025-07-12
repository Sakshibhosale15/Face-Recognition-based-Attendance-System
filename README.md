# Face-Recognition-based-Attendance-System
A simple Python-based GUI project that uses OpenCV to recognize faces and mark attendance automatically.

## 🔧 Requirements
- OpenCV → `pip install opencv-python`
- Pillow → `pip install Pillow`
- Pandas → `pip install pandas`
- Tkinter (comes pre-installed with Python)

---

## 📁 Project Flow
1. 📸 Click **"Take Images"** – Captures 200 face images per person.
2. 🧠 Click **"Train Image"** – Trains the recognizer and saves the model.
3. ✅ Click **"Automatic Attendance"** – Recognizes faces and marks attendance in a `.csv` file.
4. ✍️ Use **"Manual Attendance"** to mark it manually.

---

## 📌 Folder Tips
- Create a folder named `TrainingImage` before running.
- Trained model gets saved in `TrainingImageLabel`.
- Attendance saved as CSV files with time and subject.

---

## ⚠️ Notes
- `trainer.yml` file is large. [📥 Download here](YOUR_GOOGLE_DRIVE_LINK)
- Performance depends on system specs (recommended: 8GB RAM).
- Works best with clear, front-facing images.

⭐ **Star this repo if it helped you!**

