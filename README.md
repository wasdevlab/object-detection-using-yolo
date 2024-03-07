# Object Detection Using YOLO

To utilize the YOLO algorithm for object detection, follow these steps:

Open Jupyter Notebook in your web browser.
Navigate to the folder containing the YOLO-Object-Detection notebook.
Run the YOLO.ipynb notebook.
The Darknet framework will print out the detected objects, their confidence levels, and the time taken for detection. However, since Darknet wasn't compiled with OpenCV, it cannot display the detections directly. Instead, it saves them in a file named predictions.png.
Open predictions.png to view the detected objects.
Note that if you have access to a GPU and use the GPU version of Darknet, the detection process will be significantly faster compared to running it on a CPU.
Once these steps are completed, you will have successfully applied the YOLO algorithm for object detection using the provided notebook.
