# yolov5_tut
Object detection using Yolo v5

Step 1: Clone this repository <br>
Step 2: run 
```
pip3 install -r requirements.txt
```
Step 3: run
```
python train.py --img 640 --cfg yolov5s.yaml --hyp hyp.scratch.yaml --batch 16 --epochs 100 --data road_sign_data.yaml --weights yolov5s.pt --workers 10 --name yolo_road_det
```

source : https://blog.paperspace.com/train-yolov5-custom-data/


