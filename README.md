# people-counting-opencv

### URL
https://www.pyimagesearch.com/2018/08/13/opencv-people-counter/

### 파이썬 버젼

### requirements
python 3.5
opencv-python==3.4.7.28
dlib==19.15.0
numpy==1.14.3
imutils==0.5.0
scipy==1.1.0

### conda 설정
```
conda create --name py35pc python==3.5
```

### 라이브러리 설치
```
conda activate py35pc
pip install -r requirements.txt
```

### how to run
```
python people_counter.py -p ./mobilenet_ssd/MobileNetSSD_deploy.prototxt -m ./mobilenet_ssd/MobileNetSSD_deploy.caffemodel
```