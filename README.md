# people-counting-opencv

### URL
https://www.pyimagesearch.com/2018/08/13/opencv-people-counter/

### ���̽� ����

### requirements
python 3.5
opencv-python==3.4.7.28
dlib==19.15.0
numpy==1.14.3
imutils==0.5.0
scipy==1.1.0

### conda ����
```
conda create --name py35pc python==3.5
```

### ���̺귯�� ��ġ
```
conda activate py35pc
pip install -r requirements.txt
```

### how to run
```
python people_counter.py -p ./mobilenet_ssd/MobileNetSSD_deploy.prototxt -m ./mobilenet_ssd/MobileNetSSD_deploy.caffemodel
```
If you want to run using your video run like below
```
python people_counter.py -p ./mobilenet_ssd/MobileNetSSD_deploy.prototxt -m ./mobilenet_ssd/MobileNetSSD_deploy.caffemodel -i ./videos/example_01.mp4 -o ./temp/example_01_out.mp4
```
