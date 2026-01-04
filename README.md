# Smart Tourist Language Companion

**Smart Tourist Language Companion** is an AI-powered web application designed to assist tourists visiting Sri Lanka. It bridges the language gap by providing real-time voice translation, AI-driven cultural chat assistance, and interactive learning tools.

---

## Key Features

* ** AI Voice Translator:** Translate English speech to Sinhala instantly. It also provides a **Phonetic Guide** (Sinhala sounds written in English letters) so you can pronounce words easily.
* ** AI Tourist Guide:** A smart chatbot to answer questions about Sri Lankan destinations, traditional food, and cultural etiquette.
* ** Interactive Sinhala Quiz:** Learn essential Sinhala vocabulary through a fun and engaging quiz system.
* ** Emergency Companion:** Quick access to Sri Lankan emergency services. Includes one-tap dialing for:
    * **Police:** 119
    * **Ambulance:** 1990
    * **Tourist Police:** Quick support for travelers.
* ** Survival Phrases:** A library of essential phrases with audio support to help you in urgent situations.

---

##  Tech Stack

### Frontend (Web App)
* **Framework:** Flutter Web (Dart)
* **Key Packages:** `speech_to_text`, `flutter_tts`, `translator`, `http`, `url_launcher`.

### Backend (API)
* **Framework:** FastAPI (Python)
* **Server:** Uvicorn
* **Logic:** Custom Sinhala-to-Phonetic conversion engine and automated chat routing.

---

## How to Run the Project

This project consists of two main parts: the **FastAPI Backend** and the **Flutter Web Frontend**. Follow these steps to get it running on your machine.


First, you need to start the Python server. Open your terminal in the `backend` folder and run:
```bash
python -m uvicorn app.main:app --host 0.0.0.0 --port 9000 --reload


second run the frontend:
# Get the required packages
flutter pub get

# Run the app in Chrome browser
flutter run -d chrome

---

<h2 style="background-color: black; color: white; padding: 5px;">Project Resources & Demo</h2>

### Demo Video
[Watch the full demo here](https://drive.google.com/file/d/1qFFRyfMd03hlAGWfMn1Pz08hvJWCIZRY/view?usp=drive_link)

### Project Documentation
[View all project documentation here](https://drive.google.com/drive/folders/1oAy68DDxbvXTZGRjVRvE4EUS4NZNMla6)





