# 🛰️ Oxygen-Cylinder-Detection (YOLOv8)

This repository contains a fine-tuned **YOLOv8 ONNX model** trained for detecting critical equipment in a space station environment.

## 🚀 Model Details
- Base Model: `yolov8.pt`
- Training Epochs: 50
- Dataset: OxygenCylinder Dataset
- Framework: Ultralytics YOLOv8
- Exported Format: `.onnx`

## 💡 Usage
You can download the model and use it in any Python or web-based ONNX runtime for inference:

```python
import onnxruntime as ort
session = ort.InferenceSession("falcon_model.onnx")
