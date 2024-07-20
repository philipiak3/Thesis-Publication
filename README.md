# The FileFormatting ipynb file contains the coding in Python in order to translate the original XML annotations into TXT files in order for the model to receive the proper YOLO annotations. The dataset annotation files were transformed to
# YOLO-compatible annotation files by recording the tuple: [y, Cx, Cy, wb, hb ] where y represents the class (polyp or non-polyp), Cx and Cy are the horizontal and vertical centres of the bounding boxes and wb, hb are their corresponding width and height, respectivelly. 

# In the PolypDetectionYOLOv7 ipynb file, there's the implementation of the YOLOv7 model, as well as the training and inference on our dataset.
