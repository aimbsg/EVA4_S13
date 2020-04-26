# EVA4_S13
YoloV3 implementation :
Part A - Re-executed the existing OpenCV code to predict bounding box for existing COCO class

Part B - Used VGG for annotation as YoloV3 annotation tool(https://github.com/miki998/YoloV3_Annotation_Tool) was not accessible from Colab and I have limitation on installing Python in laptop.
Created a separate code(S13_B1_Custom_label_creation.ipynb) to convert VGG annotator format (top_left_x, top_left_y) to Yolo format(center_x, center_y)
Ran the model for various epochs (100-500)
Downloaded YT video and modify the source in detect.py
Fit the model on video
Link to annotated video : https://youtu.be/Kg-onHeva_g
