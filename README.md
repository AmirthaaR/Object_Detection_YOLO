# Object Detection using YOLO

## Project Overview
This project implements object detection using a pretrained YOLO11 Nano model. It identifies objects in an image and displays bounding boxes, class labels, and confidence scores.

The project was developed using Python and Google Colab as part of hands-on computer vision practice.

## Objectives
- Detect multiple objects in an image.
- Display object labels and bounding boxes.
- Calculate confidence scores for detected objects.
- Visualize and save the detection results.

## Technologies Used
- Python
- Ultralytics YOLO11
- OpenCV
- Matplotlib
- Google Colab

## Model
**YOLO11 Nano (`yolo11n.pt`)**

The pretrained model is used for object detection without training from scratch. It can detect common object categories learned from its training dataset.

## Project Workflow
1. Install the Ultralytics library.
2. Load the pretrained YOLO11 Nano model.
3. Upload an input image.
4. Run object detection with a confidence threshold of 0.25.
5. Display detected objects with bounding boxes and labels.
6. Print object names and confidence scores.
7. Save and download the annotated output image.

## Results
The model detects objects present in the input image and visualizes them using bounding boxes, class labels, and confidence scores.

The number and types of objects detected depend on the input image and the model's predictions.

**Sample output:** See `detected_objects.jpg` in this repository.

## How to Run
1. Open `Object_Detection_YOLO.ipynb` in Google Colab.
2. Run the notebook cells in order.
3. Upload an image when prompted.
4. View the detection results.
5. Download the annotated output image.

The pretrained model weights are downloaded automatically when the notebook runs.

## Future Improvements
- Test the model on multiple images.
- Compare different confidence thresholds.
- Detect objects in video streams.
- Compare YOLO model sizes and their detection performance.

## Author
**Amirthaa R.**

B.Tech Computer Science and Engineering
