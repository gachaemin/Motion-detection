# Motion Sensing Camera
---
##### Detecting and outputting motion from the camera
Using Python Open CV , it implements the computer's built-in camera and detects and outputs the motion being filmed.

### Results:
---
<img width="80%" src="https://user-images.githubusercontent.com/112791488/207103216-dcb00f0b-80d5-4220-9305-a4b90dd0ea32.gif"

### Requirements: (with versions i tested on)
---
```sh
- python (3.7.3)
- opencv (4.1.0)
```
### How to execute
---
Steps involved:
1. PC Camera works.
2. Capture by giving a delay to the image that you read by the camera.
3. Reverse the image file to gray.
4. Find the difference in value between images inverted in gray.
There is a difference if there is movement.
5. Filter with Threhold to remove meaningless movement.
6. Use the counting function to count the pixel value at which the motion occurred.
7. Output motion.

### Reference data
---
파이썬(Python) OpenCV로 웹캠(USB CAMERA) 영상 열기!! by sinwho
link: [sinwho tistory](https://sinwho.tistory.com/entry/%ED%8C%8C%EC%9D%B4%EC%8D%ACPython-OpenCV%EB%A1%9C-%EC%9B%B9%EC%BA%A0USB-CAMERA-%EC%98%81%EC%83%81-%EC%97%B4%EA%B8%B0)