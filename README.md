# People-counting-opencv

### Project URL
https://www.pyimagesearch.com/2018/08/13/opencv-people-counter/

### Requirements
python 3.5  
opencv-python==3.4.7.28  
dlib==19.15.0  
numpy==1.14.3  
imutils==0.5.0  
scipy==1.1.0  

### Conda environment
```
conda create --name py35pc python==3.5
```

### Installation
```
conda activate py35pc
pip install -r requirements.txt
```

### How to run
```
python people_counter.py -p ./mobilenet_ssd/MobileNetSSD_deploy.prototxt -m ./mobilenet_ssd/MobileNetSSD_deploy.caffemodel
```
If you want to run using your video run like below
```
python people_counter.py -p ./mobilenet_ssd/MobileNetSSD_deploy.prototxt -m ./mobilenet_ssd/MobileNetSSD_deploy.caffemodel -i /path/your/input/video -o /path/to/save/output/video
```
