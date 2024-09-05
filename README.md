# mediapipe blur face python
<p align="center">
  <img src="https://raw.githubusercontent.com/p-p-p-p/Face-Blur-Webapp/main/demo/demo.gif" alt="animated" />
</p>
<br>
This web app only run on localhost <br>
Python version >=3.7 <br>

## step 1

```
pip install -r requirements.txt
```
## Run web app
To run the web app  or, double click on the run.py file

```
python run.py
```

![Demo](https://raw.githubusercontent.com/p-p-p-p/Face-Blur-Webapp/main/demo/webapp.PNG)
#### Give a clear input file name like "video.mp4" not like "vid - 324$op _ 9363*.mp4"
#### If you increase "Face Detection Confidence" then face tracking will more accurate. <br>
#### If you reduce "Blur pixel size in face" then face blur pixel size will increase. <br>
#### In "Horizontally flip video" "yes" mean you can mirror your video. "No" mean nothing will happen.


## From webcam
Realtime face blur using webcam
```
python webcam.py
```

# Blur face and Change background
```
streamlit run face_blur_and_background_change.py --server.maxUploadSize=5000
```
![Demo](https://raw.githubusercontent.com/p-p-p-p/Face-Blur-Webapp/main/demo/test.png)

# Blur face and Change background
```
python face_block_and_background_change_webcam.py
```
