<div align="center">

# 🏛️ Interactive AR Science Museum

### المتحف العلمي التفاعلي

**Explore the history of science through Augmented Reality.**

Point your camera at a target image and bring historical scientific instruments to life as interactive 3D models.

<br>

[![Unity](https://img.shields.io/badge/Unity-2022.3%20LTS-black?style=for-the-badge&logo=unity)](https://unity.com/)
[![Vuforia](https://img.shields.io/badge/Vuforia-Engine%2010.x-blue?style=for-the-badge)](https://developer.vuforia.com/)
[![Platform](https://img.shields.io/badge/Platform-Android-green?style=for-the-badge&logo=android)](https://www.android.com/)
[![Language](https://img.shields.io/badge/Language-C%23-purple?style=for-the-badge&logo=csharp)](https://learn.microsoft.com/en-us/dotnet/csharp/)
[![License](https://img.shields.io/badge/License-Academic-orange?style=for-the-badge)](#-license)

<br>

### 🎬 Demo

[![Watch Demo](https://img.shields.io/badge/▶_Watch_Full_Demo-Google_Drive-success?style=for-the-badge&logo=googledrive)](https://drive.google.com/file/d/1MSbuA1AEU16gQxsw1eTbuE_LKB-JfMeJ/view?usp=sharing)

</div>

---

# 📖 Table of Contents

- [🔬 About The Project](#-about-the-project)
- [🎯 Project Goal](#-project-goal)
- [✨ Features](#-features)
- [🔭 Scientific Instruments](#-scientific-instruments)
- [⚙️ How It Works](#️-how-it-works)
- [📸 Screenshots](#-screenshots)
- [📱 How To Use](#-how-to-use)
- [🚀 Getting Started](#-getting-started)
- [📘 AR Booklet](#-ar-booklet)
- [📁 Project Structure](#-project-structure)
- [🛠️ Built With](#️-built-with)
- [🎓 Course Information](#-course-information)
- [👥 Team](#-team)
- [📄 License](#-license)

---

# 🔬 About The Project

**Interactive AR Science Museum** is an educational **Augmented Reality Android application** developed as part of an **AR & VR course project**.

The application transforms a traditional scientific booklet into an interactive digital museum.

Instead of simply reading about historical scientific instruments, users can:

- 📷 Scan printed target images.
- 🗿 View the corresponding 3D model in Augmented Reality.
- 👆 Rotate the model using touch gestures.
- 📚 Read historical and scientific information.
- 🔎 Explore the instrument from different angles.

The project combines **education, historical science, 3D visualization, and Augmented Reality** into one interactive experience.

---

# 🎯 Project Goal

The main goal of the project is to make learning about the **history of science and scientific instruments** more engaging and memorable.

Traditional educational materials mainly depend on:

> 📖 Text + Images

This project adds:

> 📖 Text + Images + 🗿 3D Models + 📱 Augmented Reality

By pointing a smartphone camera at a target image, the application recognizes the image and displays the corresponding scientific instrument as a 3D AR object.

---

# ✨ Features

### 🎯 Image Target Recognition

Powered by **Vuforia Engine**, the application recognizes five different scientific instrument target images.

### 🗿 Interactive 3D Models

Each target activates a corresponding 3D model that appears directly above the target image.

### 👆 Touch-Based Rotation

Users can drag their finger across the screen to rotate the 3D model and inspect it from different angles.

### 🌀 Inertia Effect

The model continues rotating smoothly for a short time after the user releases their finger, creating a more natural interaction.

### 📋 Information Panels

Each scientific instrument includes an information panel containing its name and historical/scientific information.

### 🏛️ Vintage Museum UI

The interface uses a vintage-inspired visual style to match the historical theme of the project.

### ❓ Built-in Help System

A dedicated animated help panel explains how to use the AR experience.

### 📱 Portrait Mode

The application is optimized for a fixed portrait orientation to provide a stable mobile UI.

---

# 🔭 Scientific Instruments

| # | Instrument | Arabic Name | Key Fact |
|---|---|---|---|
| ⚖️ 1 | **Balance Scale** | الميزان الحساس | Accuracy up to 0.001g |
| ☎️ 2 | **Vintage Telephone** | الهاتف الثابت | Invented by Alexander Graham Bell in 1876 |
| 🔬 3 | **Optical Microscope** | الميكروسكوب الضوئي | Can provide magnification up to 1000× |
| 📷 4 | **Photographic Camera** | الكاميرا الفوتوغرافية | Early camera development dates back to the 19th century |
| 🎵 5 | **Gramophone** | الجرامافون | Invented by Emile Berliner in 1887 |

---

# ⚙️ How It Works

The application follows a simple AR pipeline:

```text
                 ┌─────────────────┐
                 │   Launch App    │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │   Start Screen  │
                 └────────┬────────┘
                          │
                     Tap START
                          │
                          ▼
                 ┌─────────────────┐
                 │   AR Camera     │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │ Scan Target     │
                 │     Image       │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │    Vuforia      │
                 │ Image Detection │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │  Target Found   │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │ 3D Model Appears│
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │  Info Panel     │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │ Touch Rotation  │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │ Target Lost     │
                 └────────┬────────┘
                          │
                          ▼
                 ┌─────────────────┐
                 │ Model Hides /   │
                 │      Resets     │
                 └─────────────────┘
