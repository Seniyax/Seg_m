# Semantic Segmentation with CamVid Data
Semantic segmentation's goal is to classify each pixel in an image into a specific category like in image classification where we assign a specific category for the whole image.I perform a semantic segmantation on CamVid (Cambridge-Driving Labelled Video Dataset) Data where the task is to classify each object present in the data in pixel wise.Trained the model using training images and its corresponding Mask (label) then validated using validated data provided.

<img width="3423" height="1151" alt="segmentation_result" src="https://github.com/user-attachments/assets/8da8403e-fc15-4529-9b2c-0337b01070f1" />

## Model Architecture : U-Net
U-Net is a convolutional neural network originally designed for biomedical image segmentation but widely adopted for various tasks due to its effectiveness with limited training data.
It features a contracting path (encoder) to capture context and a symmetric expanding path (decoder) with skip connections to enable precise localization.

<img width="1255" height="900" alt="u-net-architecture" src="https://github.com/user-attachments/assets/5ead10ae-7d11-4dae-9558-684a400b7a7d" />

## Real-World Applications
Semantic segmentation, as demonstrated on datasets like CamVid, has significant real-world impact, particularly in:
### Autonomous Driving (Self-Driving Cars)
- Enables vehicles to understand the driving environment at a pixel level.
- Identifies drivable areas (roads, lanes), obstacles (vehicles, pedestrians, cyclists), traffic signs, and dynamic elements.
- Used in perception systems of companies like Tesla, Waymo, and Cruise for real-time scene parsing.


