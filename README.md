# Gender_detection
Women_Safety_Analytics

# Gender_detection
women safety anlytics

# 🛡️ Women Safety Analytics — Gender Detection Module

Real-time gender detection using **YOLOv5 + OpenCV**, developed as part of the **Smart India Hackathon**.  
My responsibility: building the **Gender Detection** component that identifies male/female in CCTV footage for public safety applications.  

---

## 👀 What It Does

✅ Detects humans  
✅ Classifies gender as **Male / Female**  
✅ Shows bounding box + confidence levels  
✅ Works in real-time on CPU  
✅ Can plug into alert systems for women safety

---

## 🎥 Demo

### 📸 Sample Detection Output
> The model detects a person → draws a bounding box → slaps a gender label + confidence score 🔥
>
> *Replace the below image path after upload*
>
![Gender Detection Sample](assets/images/gender_detection_sample.png)

---

### 🎬 Real-Time Demo Video
> Shows the live gender classification on CCTV/webcam footage.
>
> *Upload your video in GitHub, then replace this link 👇*
>
https://github.com/your-username/your-repo-name/assets/video/demo_gender_detection.mp4

---

## 🧠 Tech Stack
| Component | Tools |
|----------|------|
| Model Architecture | YOLOv5 |
| Vision | OpenCV |
| Programming | Python |
| Dataset | Custom + Public datasets |

---

## 🛠️ How It Works

1️⃣ Capture video frame  
2️⃣ YOLOv5 detects people in frame  
3️⃣ Gender classifier predicts label  
4️⃣ Bounding boxes drawn with confidence  
5️⃣ Results displayed in real time

```bash
[ Person ] -> Gender: Female | 0.92
[ Person ] -> Gender: Male | 0.87


