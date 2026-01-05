# Smart Tourist Language Companion 

An AI-powered web application that helps tourists in Sri Lanka overcome language barriers using real-time English-to-Sinhala translation, cultural guidance, and emergency support.

---

##  Key Features

*  **AI Voice Translator** – Instant English → Sinhala translation with **phonetic guide** for easy pronunciation
*  **AI Tourist Guide** – Chatbot for destinations, traditional food & cultural etiquette
*  **Interactive Sinhala Quiz** – Learn essential vocabulary in a fun way
*  **Emergency Companion** – One-tap access to:

  * Police: **119**
  * Ambulance: **1990**
   
*  **Survival Phrases** – Essential phrases with audio support for urgent situations

---

##  Tech Stack

**Frontend:** Flutter Web (Dart)

**Packages:** speech_to_text, flutter_tts, translator, http, url_launcher

**Backend:** FastAPI (Python), Uvicorn

**Logic:** Sinhala-to-Phonetic conversion & AI chat routing

---

##  Getting Started

### Run Backend

```bash
cd backend
python -m uvicorn app.main:app --host 0.0.0.0 --port 9000 --reload
```

### Run Frontend

```bash
flutter pub get
flutter run -d chrome
```

---

## 🎥 Demo

[Watch Demo Video](https://drive.google.com/file/d/1hJBYtafqDqHGrPm5NWlD_ZjBs0VP_60b/view?usp=drive_link)

---

## 📄 Documentation

[View Project Documentation](https://drive.google.com/drive/folders/1TSU9TtUp5DS47o7-k9l9Y_MjuWXX0V4J?usp=drive_link)

---
*Academic AI-based web application to enhance the tourist experience in Sri Lanka.
