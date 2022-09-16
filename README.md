# Yolov5 Modified for Feature Extraction

The BaseModel class in yolo.py has been edited to output a specified layer (in this case Stage1_Conv of the yolov5s model, defined by ouput_layer=1)

### Usage:
1. Find the layer number from model yaml you want to output (zero indexed)
2. Edit yolo.py BaseModel forward_once variable output_layer to desired layer number to output.  
3. Run output.py or use the output_layer function to get desired layer returned

TODO: Make changing the desired output layer to be defined when intializing the model
