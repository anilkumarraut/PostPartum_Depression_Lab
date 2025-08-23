# 🎭 TikTok Video Analysis for Postpartum Depression Detection

## 📌 Overview
This project is designed to **analyze TikTok videos** to extract **audio features** and separate the **background music and human voice** from the video. The primary goal is to assist in detecting **postpartum depression** by analyzing the user's speech patterns.

---

## 🔹 Features Implemented
✔ **Upload a TikTok video** from the user's local computer.  
✔ **Extract audio** from the uploaded video.  
✔ **Separate background music and vocals** using `Demucs`.  
✔ **Generate structured JSON output** with relevant file paths.  
✔ **Handle cases where one or both audio components are missing**.  
✔ **Allow users to download extracted audio files**.

---

## 🏗️ Work
1. **Upload TikTok Video**  
   - The user selects and uploads a video file (`.mp4` format).
   
2. **Extract Audio**  
   - `FFmpeg` is used to extract
