# diploma

```markdown
# Project Setup Instructions

## 1. diploma_models (Python 3.9)
**Instructions for running models in Python:**

### 1.1. Installing dependencies:
Make sure you have Python 3.9 installed or are using a virtual environment.

Create and activate a virtual environment (if necessary):
```bash
python3.9 -m venv venv
source venv/bin/activate  # For Linux/macOS
venv\Scripts\activate     # For Windows
```

### 1.2. Installing dependencies:
Navigate to the `diploma_models` folder and install all dependencies:
```bash
cd diploma_models
pip install -r requirements.txt
```

### 1.3. Running the model:
After installing the dependencies, you can run the model:
```bash
python train_on_base.py
```

---

## 2. GoogleML_Kit_diploma (Flutter)
**Instructions for running the Flutter app:**

### 2.1. Initializing dependencies:
Navigate to the `GoogleML_Kit_diploma` folder:
```bash
cd GoogleML_Kit_diploma
```

Install all dependencies:
```bash
flutter pub get
```

### 2.2. Running the app:
Make sure your environment for Android or iOS (depending on the platform) is set up, and then run the app:
```bash
flutter run
```

### 2.3. Choosing the platform:
To run on Android:
```bash
flutter run -d android
```

To run on iOS:
```bash
flutter run -d ios
```

---

## 3. CoreML_diploma (SwiftUI)
**Instructions for running the SwiftUI app:**

### 3.1. Importing the project into Xcode:
Navigate to the `CoreML_diploma` folder and open the project in Xcode:
```bash
cd CoreML_diploma
open CoreML_diploma.xcodeproj
```

### 3.2. Setting up for running:
In Xcode, select the connected simulator or a real device (iPhone, iPad) on which you want to run the app.

### 3.3. Running the app:
To run the app, click the "Run" button in the top left corner of Xcode or use the hotkeys `Cmd + R`.

---
