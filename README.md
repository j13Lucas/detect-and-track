# <img src = "https://opencv.org/wp-content/uploads/2021/06/OpenCV_logo_black_.png">  Computer Vision I (Introduction)

In this project, we have created a **Video Analysis** application that performs detection and tracking. 

Specifically, the application performs 2 tasks:

1. Detecting the soccer ball using **YOLOv3**.
2. Perform tracking using **KCF** tracker.

If the application looses tracking, we continue looking for the next `n` frames (in our case, `n`is set to `10`) until the detector is able to detect the soccer ball again. Subsequently, the tracker then takes over for tracking it further.



One can start the application by running:

`python c1_project2_detect_and_track.py`


A sample video output is shown below.


![c1_project2_detection_and_tracking](https://github-production-user-asset-6210df.s3.amazonaws.com/47062478/245316770-9590c14f-e931-4e31-9552-0ee66d35500a.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAIWNJYAX4CSVEH53A%2F20230810%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20230810T124841Z&X-Amz-Expires=300&X-Amz-Signature=f3cb13f8a7e43e5c4299dab9e58d2cde486a74e556ea867791c307aa8fe3c0ab&X-Amz-SignedHeaders=host&actor_id=55636313&key_id=0&repo_id=652431672)


---

