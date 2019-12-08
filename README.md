## Implementation by Adrian Rosebrock on Face detection with OpenCV and deep learning

Find Details in the line given below:

https://www.pyimagesearch.com/2018/02/26/face-detection-with-opencv-and-deep-learning/

## Face detection with OpenCV and deep learning

Perform fast, accurate face detection with OpenCV using a pre-trained deep learning face detector model shipped with the library.

### Face detection in images.

Usage Example:`python detect_faces.py -p models/deploy.prototxt.txt -m models/res10_300x300_ssd_iter_140000.caffemodel -i images/boys.jpg`

#### Example Input:
![alt_text](https://github.com/yasersakkaf/FaceDetection/blob/master/images/boys.jpg)

#### Example Output:
![alt text](https://github.com/yasersakkaf/FaceDetection/blob/master/images/Output_screenshot_02.10.2019.png)




### Face detection in webcam.

Usage Example:`python detect_faces_video.py -p models/deploy.prototxt.txt -m models/res10_300x300_ssd_iter_140000.caffemodel`


### Face detection in videos.

Usage Example:`python detect_faces_video.py -p models/deploy.prototxt.txt -m models/res10_300x300_ssd_iter_140000.caffemodel -v some_video.mp4`
