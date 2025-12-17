# 🐾 PlayPaws

PlayPaws is a **mobile matchmaking app for dog owners** that helps people find compatible playmates for their dogs based on breed traits, temperament, and owner preferences. Inspired by swipe-based apps like Tinder, PlayPaws combines a polished Flutter frontend with a Python-powered matching algorithm to create meaningful, real-world connections between pets and their owners while showcasing full-stack and applied ML development.

---

## ✨ Features

* 🐕 **Authentication & Profiles**: Secure login with Apple and Google via Firebase Authentication. Users create detailed profiles for themselves and their dogs.
* 🔄 **Swipe-Based Matching**: A Tinder-style matching page where users swipe left or right on other dog profiles.
* 🧠 **ML-Powered Compatibility**: Dogs are ranked using a custom matching algorithm based on breed temperament embeddings and user preferences.
* 💬 **Messaging**: Matched users can chat and coordinate playdates.
* 📅 **Calendar Scheduling**: View and schedule upcoming dog playdates (available after a mutual match).

---

## 🛠️ Tech Stack

**Frontend**

* Flutter (Dart)
* iOS Simulator (Xcode) / Android Emulator (Android Studio)
* CocoaPods (iOS dependencies)

**Backend / ML**

* Python
* FastAPI (API layer)
* Sentence Transformers (text embeddings)
* NLTK (text preprocessing)

**Database & Auth**

* Firebase Authentication (Apple & Google login)
* Firebase Firestore (user profiles, dog profiles, breed data)

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

* Flutter SDK
* Python 3.9+
* Xcode (for iOS) **or** Android Studio (for Android)
* CocoaPods

---

### Installation & Setup

1. **Clone the repository**

```bash
git clone https://github.com/your-username/playpaws.git
cd playpaws
```

2. **Install backend Python packages**

```bash
pip install fastapi uvicorn sentence-transformers pydantic requests
```

3. **Start the backend API**

```bash
cd ML_Algorithm
python main.py
```

4. **Navigate to the Flutter app**

```bash
cd ..
cd flutterDemo
```

5. **Verify Flutter dependencies**

```bash
flutter doctor
```

6. **Install Flutter packages**

```bash
flutter pub get
```

7. **Run the app**

* Open an iOS Simulator in Xcode **or** an Android emulator in Android Studio
* Select a device and run:

```bash
flutter run
```

---

## 🧠 What I Learned

* Building a cross-platform mobile app with Flutter and Dart
* Integrating Firebase Authentication and Firestore into a production-style app
* Designing and deploying a Python-based ML API
* Using NLP techniques (NLTK + Sentence Transformers) to generate semantic embeddings
* Translating cosine similarity scores into a real-world recommendation system

---

## 🔮 Future Improvements

* 🐾 Real-time messaging with read receipts
* 📍 Location-based filtering for nearby matches
* 📊 Improved preference weighting and recommender system
* ☁️ Cloud deployment for the FastAPI backend

---

## 📸 Screenshots / Demo

> Add screenshots or a short demo GIF here

---

## 👤 Author

**Dinasty Kelly**

**Joelle Chua**

**Matthew Charles**

**Tesneem Essa**

* GitHub: [TesneemE](https://github.com/TesneemE)
* LinkedIn: [Tesneem Essa](https://www.linkedin.com/in/tesneem-essa-87b862262)


---

If you like this project, feel free to ⭐️ the repo or reach out!
