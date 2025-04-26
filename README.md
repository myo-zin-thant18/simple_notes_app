
# 📱 Take-home Assignment | Final Report

**Full Name:** [Myo Zin Thant]  
**Student ID:** [6631503076]  
**App Name:** Simple Notes App  
**Framework Used:** Flutter  
**GitHub Repository Link:** [https://github.com/myo-zin-thant18/simple_notes_app]  
**APK/IPA File Link:** [https://drive.google.com/file/d/1C18F-nuhXgtkIVN8Lzo7KY_ao7ykNGaF]

---

## 1. App Concept and Design

### 1.1 User Personas

Persona 1:  
- Name: Nay Win Aung 
- Age: 21  
- Occupation: University Student  
- Needs: Wants an app to quickly jot down lecture notes and reminders

Persona 2:  
- Name: Shoka 
- Age: 26  
- Occupation: Office Worker  
- Needs: Wants to record daily tasks, ideas, and important notes easily

---

### 1.2 App Goals

- Allow users to quickly create, view, edit, and delete notes
- Save notes securely in Firebase Firestore
- Display timestamp for each note
- Provide Light and Dark Mode toggle for better user experience

---

### 1.3 App Mockup (Screens)

- Home Screen (list of all notes)
- Add Note Screen (to create a new note)
- Edit Note Screen (to modify an existing note)
- Delete Note Screen (to delete an existing note)

---

### 1.4 User Flow

Open App ➔ View list of notes ➔ Tap "+" button ➔ Add new note ➔ Save  
Or tap an existing note ➔ Edit or swipe left ➔ Delete note

---

## 2. App Implementation

### 2.1 Development Details

Tools Used:

- Flutter 3.19
- Dart 3.2
- Firebase Core
- Firebase Firestore
- intl package (for formatting timestamps)
- Material 3 Design

---

### 2.2 Features Implemented

- ✅ Create new notes
- ✅ View list of notes
- ✅ Edit existing notes
- ✅ Delete notes with swipe gesture
- ✅ Firebase Firestore integration
- ✅ Display timestamps for each note
- ✅ Light and Dark Mode toggle

---

### 2.3 App Screenshots

#### Home Screen with Light Mode and Dark Mode
<img width="313" alt="Screenshot 2025-04-26 at 5 53 14 PM" src="https://github.com/user-attachments/assets/e5edd21d-177c-4859-b03c-f5b142e3bcd6" />

<img width="313" alt="Screenshot 2025-04-26 at 5 53 26 PM" src="https://github.com/user-attachments/assets/00264f5d-45fa-4f20-ad51-d7a00cfdac51" />

#### Add Note Screen
<img width="308" alt="Screenshot 2025-04-26 at 5 54 31 PM" src="https://github.com/user-attachments/assets/2f74c255-598d-4ee4-ada6-fd9fd4fae379" />

<img width="309" alt="Screenshot 2025-04-26 at 5 54 45 PM" src="https://github.com/user-attachments/assets/62c499d0-bed8-4661-9f63-596c41dc2793" />

#### Update Note Screen
<img width="310" alt="Screenshot 2025-04-26 at 5 55 08 PM" src="https://github.com/user-attachments/assets/e40f2af5-d7c4-4603-bd6c-60ba8d06780e" />

<img width="306" alt="Screenshot 2025-04-26 at 5 55 21 PM" src="https://github.com/user-attachments/assets/b8a434c2-772c-44ce-8882-d7550de2d7cd" />

#### Delete Note Screen (You can swipe to delete)
<img width="310" alt="Screenshot 2025-04-26 at 6 01 06 PM" src="https://github.com/user-attachments/assets/b6dce886-1e98-4456-b8c6-9d144c8c34c7" />

<img width="313" alt="Screenshot 2025-04-26 at 6 01 17 PM" src="https://github.com/user-attachments/assets/19b8570e-4a87-4f3b-a644-07036b1bcc58" />

#### Firebase Database
<img width="1280" alt="Screenshot 2025-04-26 at 5 50 24 PM" src="https://github.com/user-attachments/assets/bd068e73-4e54-4000-a850-5fd02bdda072" />


---

## 3. Deployment and Installation

### 3.1 Build Type

- ✅ Release

---

### 3.2 Platform Tested

- ✅ Android
- ✅ iOS

---

### 3.3 README and Installation Guide

Installation steps:

1. Download the APK file from the provided link.
2. Open the APK file via File Manager on your Android device.
3. Allow installation from unknown sources if prompted.
4. Install and start using the app!

---

## 4. Reflection

- Faced issues with Firebase connection on real devices — solved by adding SHA-1 fingerprint and updating `google-services.json`
- Learned how to use Firestore streams to fetch real-time data
- Gained experience in implementing Light/Dark theme switching in Flutter
- Would like to add login and cloud backup features in the future

---

## 5. AI Assisted Development (Bonus)

### 5.1 AI for Idea Generation

Prompt used:  
"Suggest simple Flutter app ideas using Firebase Firestore."

Result:  
Got the idea to build a lightweight Notes App.

---

### 5.2 AI for UI Design

Prompt used:  
"Design a simple notes app layout in Flutter with Add/Edit/Delete functionality."

Result:  
Helped plan the layout structure using Scaffold, ListView, and Card widgets.

---

### 5.3 AI for Code Writing

Prompt used:  
"Example of Flutter CRUD operations with Firestore."

Result:  
Adapted basic Firestore read/write logic to my app.

---

### 5.4 AI for Debugging

Prompt used:  
"My Flutter app cannot connect to Firebase on real device, here’s the error."

Result:  
Learned the importance of SHA-1 certificate for real device authentication.

---

### 5.5 AI for Deployment

Prompt used:  
"How to build a Flutter app APK and share it with others."

Result:  
Learned how to properly build APK with `flutter build apk --release`.

---

# ✅ Final Submission Checklist

- ✅ Completed all required sections
- ✅ Attached GitHub and APK links
- ✅ Provided detailed reflections
- ✅ Explained AI assistance clearly

---

# 🏁 Done! ✅
