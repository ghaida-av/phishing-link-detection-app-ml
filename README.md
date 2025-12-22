# Phishing Link Detection App
Phishing Link Detection App using Machine Learning


This project works both as:

- An Android app (built in Kotlin)
- A Web app (built with HTML, CSS, and JavaScript)

The app helps check if a link is safe or phishing using simple rules.

---

## 📱 Android App (Kotlin)

- The Android app allows you to enter a link and check it.
-  Results:
  - ✅ SAFE LINK
  - ⚠ PHISHING LINK

### How it works

The app uses simple rules to detect phishing links:

1. If the link contains `@` -> phishing  
2. If the link contains words like `login`, `verify`, or `bank` -> phishing  
3. If the link is very long (more than 75 characters) -> phishing  

 These are basic Machine Learning style rules.

---

### Run Android app locally

1. Open Android Studio  
2. Go to File -> Open and select this project folder  
3. Connect an Android device or use an emulator  
4. Click Run to start the app  

---

## 🌐 Web App (HTML + CSS + JS)

- The web version works in any browser.
- Blue background, input box to enter link, check button, and result display.

### Run Web app locally

1. Open Terminal  
2. Go to the project folder:

```bash
cd ~/AndroidStudioProjects/PhishingLinkDetector

