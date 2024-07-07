# SSWnet-yolo
Real-time Melanoma Detection Algorithm

![1720295279380](https://github.com/Ap1rate/SSWnet-yolo/assets/107412066/20db9ed3-0ff8-453f-b94c-f2d223e6439c)

# Introduction
Based on Dynamic Snake Convolution,

SSWnet created by Squeeze-and-Excitation Networks and Wise-IoU Integration, performance was attempted under yolov5 conditions.

# Algorithmic Network Module Diagram
![1720366718587](https://github.com/Ap1rate/SSWnet-yolo/assets/107412066/618b741a-8d96-4797-a358-d8d2836e1583)
↓
![1720366726973](https://github.com/Ap1rate/SSWnet-yolo/assets/107412066/4e496116-1438-4358-ac37-de0bb556425c)
↓
![1720366731974](https://github.com/Ap1rate/SSWnet-yolo/assets/107412066/56d8f553-ef4a-4dde-8320-d09a02f54cab)
↓
![1720366735265](https://github.com/Ap1rate/SSWnet-yolo/assets/107412066/6657a793-0512-4bec-ab4b-14c9702dd425)

# Performance
Single Scale Inference on VGA resolution（max side is equal to 640 and scale).

![1720294869401](https://github.com/Ap1rate/SSWnet-yolo/assets/107412066/6a81066a-acb8-44cd-b647-27e0db51ea95)
# datasets
![1720295365537](https://github.com/Ap1rate/SSWnet-yolo/assets/107412066/d3ef968a-152b-470a-a492-23c42faca337)

# install
```bash
git clone https://github.com/SSWnet-yolo  # clone
cd SSWnet-yolo
pip install -r requirements.txt  # install
```
# run
```bash
python3 test_widerface.py --weights 'your test model' --img-size 640
cd widerface_evaluate
python3 evaluation.py
```
# Experimental Configuration
![image](https://github.com/Ap1rate/SSWnet-yolo/assets/107412066/b3fbfb47-f201-4292-8e59-73f631dc63d9)

# test
![1720294833476](https://github.com/Ap1rate/SSWnet-yolo/assets/107412066/27340f78-7d51-4101-8129-98ba78c19fe5)
![1720294874768](https://github.com/Ap1rate/SSWnet-yolo/assets/107412066/eefc89b8-dd3a-4ab6-92a0-3016313ef007)
![1720294892330](https://github.com/Ap1rate/SSWnet-yolo/assets/107412066/26fc9e0b-66fa-47cc-896c-5256c9c7619b)
![1720294899751](https://github.com/Ap1rate/SSWnet-yolo/assets/107412066/68b951b2-4e19-42d7-8409-085e9a989426)
![1720294909944](https://github.com/Ap1rate/SSWnet-yolo/assets/107412066/284c5655-f402-40e6-8bb6-36de7cc7f69f)

# References
https://github.com/ultralytics/yolov5

https://github.com/ultralytics/yolov7

https://github.com/ultralytics/yolov8

https://github.com/ultralytics/yolovX

# Citation
If you think this work is useful for you, please cite

