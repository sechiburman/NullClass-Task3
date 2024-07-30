# Animal Detection 

This project utilizes the YOLO (You Only Look Once) object detection algorithm to detect and classify animals in images. It includes a GUI interface built with Tkinter for easy image selection and display.

## Features

- Detects and classifies animals (herbivores and carnivores) in images using YOLO object detection.
- Displays bounding boxes and labels for detected animals.
- Counts and displays the number of herbivores and carnivores detected in the image.
- Provides a user-friendly GUI using Tkinter for image upload and result display.

## Requirements

The necessary Python packages are listed in `requirements.txt`. These packages must be installed in the system for successfull running of the source code file (FINAL.ipynb).

## Additional files required 

- YOLO weights file (yolov3.weights)
- YOLO configuration file (yolov3.cfg)
- COCO class labels file (coco.names)

## Running the Notebook

To run the animal detection using YOLO (final.ipynb):
Execute the cells in the notebook to perform animal detection. The notebook will prompt a window to choose an image for analysis. It will then display detected animals, count herbivores and carnivores, and visualize the results

## How to Use
1. Click the "Upload Image" button to select an image file from your computer.
2. The application will detect and classify animals in the uploaded image using YOLO.
3. Bounding boxes and labels for detected animals will be displayed on the image.
4. The counts of herbivores and carnivores detected will be shown below the image.

## Example Usage
- Ensure that the YOLO files (yolov3.weights, yolov3.cfg, coco.names) are correctly specified in the script.
- Use the Tkinter GUI to easily upload images and view detection results interactively.

## Notes
- This application relies on pre-trained YOLO models for object detection. Make sure to have the correct model files for proper functioning.
- Adjustments may be needed based on your specific file paths and configurations.
