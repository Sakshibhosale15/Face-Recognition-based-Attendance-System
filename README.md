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

## 📌 Steps to follow
- Create a folder named `TrainingImage` in your project before running.
- Open a `AMS_Run.py` and change the all paths with your system path.
- Run `AMS_Run.py.

---

### Project Structure

- After run you need to give your face data to system so enter your ID and name in box than click on `Take Images` button.
- It will collect 200 images of your faces, it save a images in `TrainingImage` folder
- After that we need to train a model(for train a model click on `Train Image` button.
- It will take 5-10 minutes for training(for 10 person data).
- After training click on `Automatic Attendance` ,it can fill attendace by your face using our trained model (model will save in `TrainingImageLabel` )
- it will create `.csv` file of attendance according to time & subject.
- You can store data in database (install wampserver),change the DB name according to your in `AMS_Run.py`.
- `Manually Fill Attendace` Button in UI is for fill a manually attendance (without facce recognition),it's also create a `.csv` and store in a database.

---

## ⚠️ Notes
- `trainer.yml` file is large. [📥 Download here](https://drive.google.com/file/d/1KckoCLuYe8jFUmRLX3fe8tH3iousvgyM/view?usp=drive_link)
- Performance depends on system specs (recommended: 8GB RAM).
- Works best with clear, front-facing images.

⭐ **Star this repo if it helped you!**

