# 🏛️ Interactive AR Science Museum

<div align="center">

### Explore the History of Science Through Augmented Reality

An educational Augmented Reality Android application that brings historical scientific instruments to life through interactive 3D models.

[![Unity](https://img.shields.io/badge/Unity-2022.3%20LTS-black?logo=unity)](https://unity.com/)
[![Vuforia](https://img.shields.io/badge/Vuforia-10.x-blue)](https://developer.vuforia.com/)
[![Platform](https://img.shields.io/badge/Platform-Android-green?logo=android)](https://www.android.com/)
[![Language](https://img.shields.io/badge/Language-C%23-purple?logo=csharp)](https://learn.microsoft.com/en-us/dotnet/csharp/)
[![Course](https://img.shields.io/badge/Course-AR%20%26%20VR-orange)](#-course-information)

<br>

### 🎬 Demo

[![Watch Demo](https://img.shields.io/badge/▶_Watch_Full_Demo-Google_Drive-success?style=for-the-badge\&logo=googledrive)](https://drive.google.com/file/d/1MSbuA1AEU16gQxsw1eTbuE_LKB-JfMeJ/view?usp=sharing)

</div>

---

## 📖 About The Project

**Interactive AR Science Museum** is an educational Augmented Reality application developed using **Unity** and **Vuforia Engine**.

The application transforms traditional scientific museum experiences into an interactive digital experience. Users can point their Android device's camera at specific target images to reveal and explore historical scientific instruments as **interactive 3D models**.

The project aims to make learning about science and historical inventions more engaging by combining:

* 🏛️ Museum-style educational content
* 📱 Augmented Reality
* 🧊 Interactive 3D models
* 📚 Scientific information
* 🎮 Touch-based interaction

---

## 🎯 Project Objectives

The main objectives of the project are:

* Create an interactive educational AR experience.
* Present historical scientific instruments in 3D.
* Help students understand scientific instruments through visualization.
* Combine educational content with modern AR technology.
* Provide an easy and intuitive Android user experience.
* Make museum-style learning more engaging and interactive.

---

## ✨ Features

### 📷 Image Target Recognition

The application uses **Vuforia Engine** to recognize predefined target images and display the corresponding 3D model.

### 🧊 Interactive 3D Models

Users can explore detailed 3D representations of historical scientific instruments.

### 👆 Touch Interaction

Users can rotate the displayed model using one-finger touch gestures.

### 🔄 Rotation & Inertia

Models support smooth rotation with an inertia effect for a more natural interaction.

### 📚 Information Panels

Each scientific instrument includes an information panel containing educational and historical information.

### 🎨 Vintage Museum UI

The interface uses a vintage-inspired design to match the theme of historical scientific instruments.

### ❓ Help System

A built-in help panel explains how to interact with the AR experience.

### 📱 Portrait Mode

The application is designed to work in fixed portrait orientation for a consistent user experience.

---

# 🔬 Scientific Instruments

The application currently includes **five scientific instruments**:

| # | Instrument             | Description                                                                                           |
| - | ---------------------- | ----------------------------------------------------------------------------------------------------- |
| 1 | ⚖️ Balance Scale       | A historical precision measuring instrument used for comparing masses.                                |
| 2 | ☎️ Vintage Telephone   | A historical communication device associated with the development of the telephone.                   |
| 3 | 🔬 Optical Microscope  | An optical instrument used to magnify objects that are too small to be seen clearly by the naked eye. |
| 4 | 📷 Photographic Camera | A historical device used for capturing images using photographic techniques.                          |
| 5 | 📀 Gramophone          | A historical sound reproduction device that used discs to record and play audio.                      |

---
## 📸 Screenshots

<div align="center">

| Start Screen | Vintage Phone AR | Camera AR |
|:---:|:---:|:---:|
| <img src="https://raw.githubusercontent.com/Mohanad06/AR-Science-Museum/main/screenshots/startscreen.jpeg" width="200"/> | <img src="https://raw.githubusercontent.com/Mohanad06/AR-Science-Museum/main/screenshots/Vintage%20Phone.jpeg" width="200"/> | <img src="https://raw.githubusercontent.com/Mohanad06/AR-Science-Museum/main/screenshots/Camera.jpeg" width="200"/> |
| *Vintage-themed main menu* | *Vintage Phone AR Model* | *Camera AR Model* |

| Microscope AR | Balance Scale AR | Gramophone AR |
|:---:|:---:|:---:|
| <img src="https://raw.githubusercontent.com/Mohanad06/AR-Science-Museum/main/screenshots/Microscope.jpeg" width="200"/> | <img src="https://raw.githubusercontent.com/Mohanad06/AR-Science-Museum/main/screenshots/Scaler.jpeg" width="200"/> | <img src="https://raw.githubusercontent.com/Mohanad06/AR-Science-Museum/main/screenshots/Gramophone.jpeg" width="200"/> |
| *Optical Microscope AR Model* | *Balance Scale AR Model* | *Gramophone AR Model* |

</div>

# 🧪 How It Works

The application follows a simple AR workflow:

```text
Launch Application
       ↓
Start Screen
       ↓
Tap "START"
       ↓
Open AR Camera
       ↓
Point Camera at Target Image
       ↓
Vuforia Recognizes Target
       ↓
3D Model Appears
       ↓
Explore & Rotate the Model
       ↓
Read Scientific Information
```

---

## 🚀 Getting Started

### Prerequisites

* Android device running **Android 7.0 (API 24)** or higher
* Rear-facing camera
* Minimum **2GB RAM**

### Installation

**Option 1 — Direct APK Install:**

1. Download the latest APK from the [Releases](https://github.com/Mohammed-elsafty74/AR-Science-Interactive-Museum/releases) page.
2. Enable *Install from Unknown Sources* on your Android device.
3. Open the APK file and install it.
4. Grant camera permission on first launch.

**Option 2 — Build from Source:**

```bash
# Clone the repository
git clone https://github.com/Mohammed-elsafty74/AR-Science-Interactive-Museum.git

# Open the project in Unity 2022.3 LTS
# File → Build Settings → Android → Build And Run
```

> **Requirements for building:** Unity 2022.3 LTS, Vuforia Engine 10.x, Android SDK (API 24+), and IL2CPP backend.

---

## 📘 Booklet

> يحتوي على جميع صور الـ Image Targets المستخدمة في التطبيق.

<div align="center">

<a href="https://github.com/Mohammed-elsafty74/AR-Science-Interactive-Museum/raw/main/BookLet/BookLet.pdf">
  <img src="https://img.shields.io/badge/📥_Download_Booklet-PDF-blue?style=for-the-badge" />
</a>

</div>

> ⚠️ You must download or open the booklet to use the AR features of the app.
> ⚠️ If the PDF preview does not load on GitHub, please download the file.

---

## 📱 How To Use

1. **Download** the AR Booklet from the link above.
2. **Print** the booklet or open it on another screen.
3. **Open** the app on your Android device.
4. **Tap START** on the main screen to activate the camera.
5. **Point** your camera at any target image from the booklet — keep it flat and well-lit.
6. **Watch** the 3D model appear above the image in real space.
7. **Drag** with one finger to rotate the model in any direction.
8. **Read** the information panel for historical details.
9. **Move away** from the image to dismiss the model.

> 💡 **Tips:**
>
> * Use good lighting — avoid dark rooms or direct sunlight on the page.
> * Keep the target image flat on a stable surface.
> * Maintain a distance of **20–40 cm** from the camera to the target.

---

## 📁 Project Structure

```text
AR-Science-Interactive-Museum/
│
├── Assets/
│   ├── Scripts/
│   │   ├── StartButton.cs           # Scene transition & AR activation
│   │   ├── HelpPanelController.cs   # Help panel with fade animation
│   │   ├── ProductInfo.cs           # Vuforia tracking & UI display
│   │   └── ModelTouchController.cs  # Touch rotation with inertia
│   │
│   ├── Models/
│   │   ├── Scale/                   # Balance Scale 3D model
│   │   ├── Phone/                   # Vintage Telephone 3D model
│   │   ├── Microscope/              # Optical Microscope 3D model
│   │   ├── Camera/                  # Photographic Camera 3D model
│   │   └── Gramophone/              # Gramophone 3D model
│   │
│   ├── Scenes/
│   │   ├── StartScene.unity         # Main menu scene
│   │   └── ARScene.unity            # Core AR experience scene
│   │
│   ├── Images/                      # Vuforia target images
│   ├── Textures/                    # UI and background textures
│   └── StreamingAssets/Vuforia/     # Vuforia target database
│
├── Packages/                        # Unity package dependencies
├── ProjectSettings/                 # Unity project configuration
└── README.md
```

---

## 🛠️ Built With

| Technology                                                                | Purpose                                |
| ------------------------------------------------------------------------- | -------------------------------------- |
| [Unity 2022.3 LTS](https://unity.com)                                     | Game engine & AR scene management      |
| [Vuforia Engine 10.x](https://developer.vuforia.com)                      | Image target recognition & AR tracking |
| [TextMeshPro](https://docs.unity3d.com/Manual/com.unity.textmeshpro.html) | High-quality UI text rendering         |
| C#                                                                        | Scripting & game logic                 |
| Android SDK (API 24+)                                                     | Android build target                   |

---

## 📋 Course Information

> This project was developed as part of the **AR & VR** course.
> **Year:** 2026

---
