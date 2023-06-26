# Fish detection Yolov5
Trained Yolov5 for three type of fish detection 
The dataset was collect from [Roboflow](https://universe.roboflow.com/research-vpani/fish-species-classification)
## Dependencies
* python == 3.10.4
* pip install -r requirements.txt

## Note 
* Make Sure you paste your image or video into the correct folder ..\inference\images
* Result will be store into the runs/detect/exp*

How to run for file:
<pre><code>python detect.py</code></pre>
* From CMD Terminal for live detection
* python detect.py --source 0
* For image base detection
* python detect.py --weights best.pt --img 416 --conf 0.1


# result
![snapper-8_jpg rf 06b12e5fda7c3f2085d033b6b2dee5ae](https://github.com/furiouskhan007/Fish_detection_Yolov5/assets/135207625/776e26e7-d7bd-4751-85f2-1ae46d846fe5)
![pink-salmon-1067x400_jpg![kerapu_22_jpg rf 07cd75757ba72ae16624eb860cc23390](https://github.com/furiouskhan007/Fish_detection_Yolov5/assets/135207625/6adbfcf3-98b0-4bf6-aa84-7b84c6a29f3d)
![Atlantic_Salmon-Atlanterhavsparken_Norway_jpg rf c5580e296b735c964929a2a9bf164c46](https://github.com/furiouskhan007/Fish_detection_Yolov5/assets/135207625/de7ff171-ff60-4399-8605-89f82fa693f0)
 rf 7b7872c3be691c20ac11a3107dcc841b](https://github.com/furiouskhan007/Fish_detection_Yolov5/assets/135207625/9a35fd6a-4192-4152-8186-d2473bbe8ded)
![istockphoto-486139401-612x612_jpg rf 00554501bb5dd1027f0fcdf7bf03fffe](https://github.com/furiouskhan007/Fish_detection_Yolov5/assets/135207625/d562c94b-66a1-486b-b124-c3b455e16666)
![chum-salmon-prior-to-spawning_jpg rf 6aef8840c0b07ef9c1b881cce3b7bfeb](https://github.com/furiouskhan007/Fish_detection_Yolov5/assets/135207625/e633d28f-10c2-42bd-ba2e-f7bc476327b4)
![296770-images-37-_jpg rf 9188cd8ca2d09b27c715efa705e97cad](https://github.com/furiouskhan007/Fish_detection_Yolov5/assets/135207625/1784f4c0-b74a-4954-8e76-a6bc234ddcbf)
