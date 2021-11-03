# CS6220 Project
Group 2: DeepFace: A High Performance Deep Neural Network System for Facial Recognition on the Edge\
Group Member: Ziang Ren, Liqiong Zhao, Ruiyang Qin, Zirong Yu

## Files in this folder
```
project
│	README.md
│	project.ipynb
│	face_mask_detection.ipynb
│	easy_case.png
│	good_case.png
│	challenging_case.png
│	face_mask.h5
│	test.mp4
│	tmp.jpg
└───res_ssd
│	│	deploy.prototxt
│	└	res10_300x300_ssd_iter_140000.caffemodel
└───database
	└───Zirong Yu
	│	│	front_mask.jpg
	│	│	front_nomask.jpg
	│	└	side_with_mask.jpg
	│	
	└───Other people
```
## Package used
`deepface`: `pip install deepface`\
`numpy`: `pip install numpy`\
`cv2`: `pip install opencv-python`\
`matplotlib`: `pip install matplotlib`\
`tensorflow`: `pip install tensorflow`\
`pandas`: `pip install pandas`\
`keras`: `pip install keras`\
`seaborn`: `pip install seaborn`\
`pillow`: `pip install Pillow`
## How to run
In the project directory, type `jupyter notebook project.ipynb` to open jupyter notebook and view the project.\
In the second cell, `cv_flag` indicates using a camera or using a video.\
`cv_flag = 0` means using a camera, `cv_flag = VIDEO_FILE_PATH` means using a video file from `VIDEO_FILE_PATH`.\
Press `q` to quit openCV video capture.
## About Training Mask Detection
Dataset used: https://www.kaggle.com/ashishjangra27/face-mask-12k-images-dataset

In the project directory, type `jupyter notebook face_mask_detection.ipynb` open jupyter notebook and view the training process of mask detection.\
Because the training dataset is too large to upload, download the dataset from the kaggle website and put it into the project directory. The path should look like:
```
project
└───Face Mask Dataset
	│	Train
	└	Test
```
