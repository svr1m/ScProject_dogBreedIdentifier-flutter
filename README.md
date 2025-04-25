# 🐾 PawCare - Pet Health & Breed Assistant

PawCare is a modern Flutter mobile application designed to help pet owners track the health of their pets, manage care routines, and identify dog breeds using AI-based image classification.

Model training python file is also given.

## 📲 Features

- 🐶 **Add & Manage Pet Profiles**  
  Create detailed profiles for each of your pets with name, age, breed, weight, and more.

- 💉 **Health Tracking**  
  Record vet visits, vaccinations, medications, and health notes.

- 🧠 **AI Breed Identifier**  
  Snap or upload a dog photo and let our AI tell you the breed!

- 🔔 **Reminders & Notifications**  
  Stay on top of pet care with reminders for appointments and vaccinations.

- ☁️ **Cloud Sync**  
  All data is securely stored and synced using Firebase.

  - Ai chatbot

## 🧱 Tech Stack

- **Flutter** - Cross-platform UI toolkit  
- **Dart** - Programming language  
- **Firebase** - Backend services (Auth, Firestore, Storage, Notifications)  
- **TensorFlow Lite** - Breed recognition model (via image classification)  
- **Provider / Riverpod** - State management  

## 📦 Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/svr1m/ScProject_dogBreedIdentifier-flutter.git
   cd ScProject_dogBreedIdentifier-flutter
   ```

2. Get dependencies:
   ```bash
   flutter pub get
   ```

3. Run the app:
   ```bash
   flutter run
   ```

> Make sure you have Flutter SDK and a device/emulator set up.

## 🧪 AI Integration

The app uses a pre-trained TensorFlow Lite model to identify dog breeds from user-uploaded images. The model is optimized for mobile and integrated via `tflite_flutter`.

## 🛡️ Permissions Used

- Camera & Gallery Access (for breed identification)
- Notifications (reminders)
- Internet (sync & AI)


## 📌 Notes

- This app is currently under active development.
- Future versions may include appointment booking, chat with vets, and nutrition advice.

---

> 🐕 Built with ❤️ for pet lovers everywhere!
