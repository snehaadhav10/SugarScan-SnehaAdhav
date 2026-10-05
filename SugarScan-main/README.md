# SugarScan – AI Sugarcane Disease Detection

SugarScan is a Flutter mobile application that uses deep learning to detect diseases in sugarcane leaves.

## Features

* Camera and Gallery image input
* AI-based disease detection using an EfficientNetB0 TFLite model
* Detects 5 conditions:

  * Healthy
  * Mosaic
  * Rust
  * Red Rot
  * Yellow Leaf
* Confidence scores for predictions
* Scan history
* Disease information and treatment guidance
* Works offline

## Model

* **Architecture:** EfficientNetB0
* **Model Format:** TensorFlow Lite (TFLite)
* **Dataset:** 5-class sugarcane leaf dataset
* **Input Size:** 224 × 224 RGB images
* **Classes:** 5

## Built With

* Flutter 3.19.6
* Dart
* TensorFlow Lite
* Hive for local storage
* EfficientNetB0

## How It Works

1. Select an image from the gallery or capture one using the camera.
2. The image is processed and resized to 224 × 224 pixels.
3. The EfficientNetB0 TFLite model analyzes the image.
4. The app displays the predicted condition and confidence score.
5. The scan can be saved in the local scan history.

## Team Members

* **Sneha Adhav** – AI/ML & Model Integration
* **Adish Patil** – Flutter Development & Model Integration
* **Shravani Galande** – UI/UX & Application Development
* **Disha Khanchandani** – Dataset, Testing & Documentation

## Project Type

Academic Group Project
