# OpenVino_Cars_counting
OpenVino counting Cars

This project consists of implementation of cars counter on highway.

The whole process consists of few steps:
1. Install ultralytics  YOLOv8
2. install bytetrack which will be used for tracking objects (in this case cars, buses, trucks or motorbykes)
3. Install Roboflow Supervision
4. Tracking utils function, and ,atching the boxes from model with the one from tracker
5. Loading Yolo V8 model
6. Object detection model
7. Convert to OpenVino IR format
8. Use NNCF post qunatisation API for model optimization
9. Testing model on one frame video
10. Start of tracker and OpenVino optimization
11. (Optional) Uploading resulting video to cloud

Videos are on urls:

Original video: 

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/ayMn05QY_UY/0.jpg)](https://www.youtube.com/watch?v=ayMn05QY_UY)

Result video: 

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/xFJue6uXx2w/0.jpg)](https://www.youtube.com/watch?v=xFJue6uXx2w)
