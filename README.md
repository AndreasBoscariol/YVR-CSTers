# About

Source code and resources for tackling the challenge of detecting wear-and-tear of YVR airport facility.

# Process Overview
- Gather grahical data
- Annotate data with open-source tools like [labelImg](https://github.com/HumanSignal/labelImg#)
- Train tensorflow object detection model on datasets
- Deploy model to edge devices (Raspberry Pi)

## Data Collection Guideline
- Take pictures at various rotations, distances and perspectives
- Create at least 200 pictures for model training
- No identical pictures

## Image Annotation Guideline 
- Include full object inside bounding box
- Overlaps in bounding boxes are allowed
- Discard pictures that's hard to annnotate 
- Check out [this video](https://www.youtube.com/watch?v=v0ssiOY6cfg&t=335s) for full details
- Furthermore, [this video] (https://www.youtube.com/watch?v=XZ7FYAMCc4M&ab_channel=EdjeElectronics) expands on the next steps
- And this [final one](https://www.youtube.com/watch?v=aimSGOAUI8Y&ab_channel=EdjeElectronics) should lead to the wrap up 

