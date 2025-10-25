# RFDETR — Custom Road Damage Detection (RFDETR-Pipeline)

> End-to-end repository for training and running a RFDETR (DETR-style) object detector on a custom COCO-format dataset exported from Roboflow. This README contains runnable commands and code snippets for installation, dataset setup, training, evaluation and inference.

---

## Project Overview
This repository demonstrates how to:
- Download a custom dataset (COCO format) using the Roboflow API.
- Train `RFDETRBase` on that dataset.
- Plot training & validation losses.
- Run inference and draw labeled bounding boxes on test images.

---

## Features
- Roboflow download script (COCO)
- Simple training loop using `rfdetr.RFDETRBase`
- Loss-plotting example (Matplotlib + Pandas)
- Inference example with bounding-box drawing utility
- Minimal dependency footprint for quick experimentation
