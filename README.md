# 📸 Presenzee – Smart Attendance with Just One Snap

**Presenzee** is a face-recognition-powered smart attendance system that lets teachers mark attendance using a single classroom photo.  
No roll calls. No signature scams. No Excel uploads. Just snap → detect → done.


---

## 🚀 Features

- 👨‍🏫 Professor Dashboard to manage classes & students
- 📩 Auto-generated form link for student registration
- 🖼️ Face detection & auto-cropping using YOLOv8
- 🔁 Training with FaceNet on single-image data with augmentations
- 🤖 Attendance via group photo + face recognition (confidence threshold)
- 🧾 View present, absent, and unknown faces
- ✍️ Manual tagging for unknowns → used for retraining
- 📊 View past attendance records (per class)

---

## 🧠 How It Works

1. **Create Class** → Get a form link  
2. **Students Self-Register** → Upload 1 clear face photo  
3. **Train Model** → Embeddings generated per student using augmentations  
4. **Take Attendance** → Upload group photo → Faces matched  
5. **Review** → Confirm unknowns → Improve model next time

---

## 🧰 Tech Stack

| Layer          | Tech                                     |
|----------------|------------------------------------------|
| Frontend       | React Native (Expo)                      |
| Backend        | Node.js + Express (MEN Stack)            |
| Database       | MongoDB                                  |
| Face Detection | YOLOv8n (Ultralytics)                    |
| Face Embedding | FaceNet (Keras / TensorFlow)             |
| Augmentation   | OpenCV + Custom preprocessing            |
| Auth / Forms   | JWT + Dynamic form generation            |

---
## 📸 Demo Preview

## 💡 Why Presenzee?
Because calling names in 2025 is... outdated.
With just one image per student and one classroom photo, Presenzee handles what used to take minutes — in seconds.

No proxies. No drama. Just faces and facts.

## 🙌 Future Features
- ✉️ In-app messaging to absentees / parents
- 🔁 Auto-retraining when new students are added
- 👀 Attendance preview mode before confirmation
- ☁️ Cloud deployment & mobile app integration

🧑‍💻 **Made With ❤️ by Sanket Gadhe**

Want to contribute? Ping me or open a PR. Feedback & stars are always welcome! 🌟

