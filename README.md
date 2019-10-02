# Face detection with OpenCV and deep learning

Perform fast, accurate face detection with OpenCV using a pre-trained deep learning face detector model shipped with the library.

#### Face detection in images.

Usage:

`python detect_faces.py -p models/deploy.prototxt.txt -m models/res10_300x300_ssd_iter_140000.caffemodel -i images/boys.jpg`

#### Face detection in webcam.

Usage:

`python detect_faces_video.py -p models/deploy.prototxt.txt -m models/res10_300x300_ssd_iter_140000.caffemodel`


#### Face detection in videos.

Usage:

`python detect_faces_video.py -p models/deploy.prototxt.txt -m models/res10_300x300_ssd_iter_140000.caffemodel -v some_video.mp4`
