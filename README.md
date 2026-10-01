# 🚗 Vehicle Number Plate Detection with YOLO11

An end-to-end computer vision application that detects vehicle license plates in real-time from videos and images using a custom-trained **YOLO11** model.

---

## 📌 Features

- **Real-Time Detection:** Accurate identification and localization of vehicle license plates.
- **YOLO11 Backbone:** Uses the latest lightweight, high-performance YOLO11 architecture (`best.pt`).
- **Interactive Interface / Pipeline:** Run inference directly via `app.py` on video streams or sample video clips.
- **Sample Testing Data:** Includes a sample test video (`card_plate.mp4`) for quick validation.

---

## 📁 Repository Structure

```text
number_plate_detection/
├── app.py              # Main inference / application script
├── best.pt             # Trained YOLO11 model weights
├── card_plate.mp4      # Sample video for demonstration
├── requirements.txt    # Project dependencies
└── README.md           # Project documentation
