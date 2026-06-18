# Real-Time Object Detection Web App

A browser-based, real-time object detection application featuring a live webcam feed, bounding-box overlays, detection controls, live metrics, and a dynamic word cloud display.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Status](https://img.shields.io/badge/status-active-brightgreen)](https://github.com/playa2021git/yolo-object-detector2025)

---

### ▶️ **[Live Demo - Try It Now!](https://playa2021git.github.io/yolo-object-detector2025/)**

---

## About The Project

This project is a user-friendly, real-time object detection application that runs entirely in your web browser. It was developed with a special audience in mind: **technology teachers and students in Japanese junior high schools**.

The goal is to make object detection easy to demonstrate in class. Students can use a webcam to see how an AI model identifies objects in the real world, while also changing practical settings such as confidence threshold and detection interval.

## Key Features

* **Real-Time Detection:** Identifies objects from your webcam feed and overlays bounding boxes and confidence labels.
* **Performance Controls:** Adjust the confidence threshold, detection interval, and maximum number of detections without editing code.
* **Camera Selection:** Switch between available cameras after permission is granted.
* **Live Metrics:** Shows approximate inference FPS, latest detection count, TensorFlow.js backend, and model name.
* **Dynamic Word Cloud:** Visualizes the frequency of detected objects in a fun, intuitive way.
* **Pause and Reset:** Pause detection when discussing a frame, and reset the word cloud when starting a new activity.
* **Privacy First:** All processing happens locally in the browser. Camera data is not uploaded to a server.
* **Zero Installation for Users:** Works from a static web page over HTTPS or localhost.

## How It Works (Technology Stack)

This application is built with accessible web technologies:

* **HTML5, CSS3, and modern JavaScript** in a single static page.
* **TensorFlow.js 4.x** for running machine-learning inference in the browser.
* **COCO-SSD 2.2.3** using the lightweight MobileNet V2 base model, pre-trained to recognize 80 common object classes.
* **wordcloud2.js** for the word cloud visualization.
* **GitHub Pages** or any static web host for deployment.

## Running Locally

Because browsers restrict webcam access, open the app from `localhost` or an HTTPS origin.

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000/> in a modern browser and allow camera access.

## A Note for Educators (先生方へ)

This tool is intended for use in technology classes (`技術科`). It can help spark discussions such as:

* How does an AI “see” the world?
* Why does it sometimes misidentify objects?
* How does changing the confidence threshold affect results?
* Why does a faster detection interval use more computer resources?
* What are the privacy and ethics considerations for camera-based AI?

## License

This project is licensed under the MIT License. See the `LICENSE` file for details. You are free to use, copy, modify, and distribute this software.
