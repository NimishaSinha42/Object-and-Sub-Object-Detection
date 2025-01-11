# Object-and-Sub-Object-Detection


# Object and Sub-Object Detection System (Detectron2)

This repository contains an implementation of a computer vision system for hierarchical object and sub-object detection using **Detectron2**. The system can detect objects and their associated sub-objects, structure results in a JSON format, and retrieve cropped images of sub-objects. It is optimized to achieve real-time inference speed on CPU.

## Features
- **Hierarchical Object and Sub-Object Detection**: Detects objects (e.g., cars) and associated sub-objects (e.g., tires, doors) with unique indexing.
- **JSON Output**: Outputs results in a hierarchical JSON format.
- **Sub-Object Cropping**: Extract and save specific sub-object images.
- **Real-Time Inference on CPU**: Processes video streams at 10–30 FPS.
- **Modular Design**: Easily extensible to support new object-sub-object pairs.


