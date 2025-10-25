# RFDETR — Custom Road Damage Detection (RFDETR-Pipeline)

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
