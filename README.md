# yolov5_tut
Object detection using Yolo v5

source : https://blog.paperspace.com/train-yolov5-custom-data/

command: python train.py --img 640 --cfg yolov5s.yaml --hyp hyp.scratch.yaml --batch 16 --epochs 100 --data road_sign_data.yaml --weights yolov5s.pt --workers 10 --name yolo_road_det
