# 📱 CosmetiCare – Smart Medical & Cosmetics Inventory Tracker

> A modern Android application designed for automated tracking, expiry monitoring, and intelligent safety analysis of medical and cosmetic products. Developed as a Bachelor's Diploma Project at Taras Shevchenko National University of Kyiv.

*(Note: This repository serves as a visual showcase. The source code is not included to protect academic integrity).*

---

## 📥 Download & Install
Due to file size limits, the compiled application is hosted in the Releases section.
- [Download CosmetiCare APK](https://github.com/annayurevychwork/cosmeticare/releases/tag/v1.0)

---

## 🚀 Key Features
- **Local-First Architecture:** Full offline functionality with a local Room SQLite database containing the EU CosIng registry.
- **Smart OCR INCI Analysis:** Automatically extracts ingredient lists from product labels using Google ML Kit.
- **Personalized Safety Calculator:** Dynamic safety scoring based on user profiles (Skin Type, Custom Allergies, and a strict Kids Mode).
- **Chemical Incompatibility Detection:** Alerts users about dangerous active ingredient combinations within their daily routines (e.g., AHA + Retinol).
- **Inventory & Expiry Tracking:** Automatically calculates the safest expiry date based on PAO (Period After Opening) and fixed dates, sending background push notifications.

---

## 🛠️ Tech Stack
- **Language:** Kotlin
- **Architecture:** Clean Architecture (MVVM)
- **UI Framework:** Jetpack Compose, Material Design 3
- **Dependency Injection:** Dagger-Hilt
- **Local Database:** Room (SQLite)
- **Machine Learning (AI):** Google ML Kit (On-device Text Recognition OCR)

---

## 📸 App Showcase

### 1. User Profile & 2. Main Dashboard
<p float="left">
  <img src="profile.png" alt="Profile" width="300" />
  <img src="main.png" alt="Main Dashboard" width="300" />
</p>

### 3. Product Details & 4. Daily Routine
<p float="left">
  <img src="details.png" alt="Product Details" width="300" />
  <img src="routine.png" alt="Routine" width="300" />
</p>

### 5. Adding a Product & 6. Expiry Notifications
<p float="left">
  <img src="create.png" alt="Create Product" width="300" />
  <img src="notif.png" alt="Notifications" width="300" />
</p>

### 7. INCI Assistant & 8. Ingredient Conflicts
<p float="left">
  <img src="inci.png" alt="INCI Help" width="300" />
  <img src="clash.png" alt="Conflicts" width="300" />
</p>
