## File Accessibility

**What all can be expected from the above files?**
- ***1.py***: Uses <a href="https://docs.opencv.org/3.0-beta/modules/video/doc/motion_analysis_and_object_tracking.html#calcopticalflowfarneback">calcOpticalFlowFarneback</a> as a primary method to calculate the dense optical flow.
    - Works best for crowd motion estimation
- ***detection2.py***:  Reference taken from <a href="https://www.youtube.com/watch?v=WrlH5hHv0gE">The Coding Lib</a>
    - Works best for individual motion estimation
- ***esp32-detect.py***: ESP32 stream 
    - opencv integrates with esp32 stream 
    - make sure that the url is taken frame by frame as in ```url='http://192.168.43.47/capture'```
    - Taking stream from esp32(continuation of above point)
    ```python
    
    while True:
    # loop_control+=1
    print("Begin")
    imgResp=urllib.request.urlopen(url,timeout=5)
    print("url is open")
    imgNp=np.array(bytearray(imgResp.read()),dtype=np.uint8)
    print("we read the data")
    frame=cv2.imdecode(imgNp,-1)
    print(frame)
    ```

## Output Videos
| <img src="https://github.com/Curovearth/Garuda-LaHacks/blob/main/gif's/code1.gif" align=center width=600> |
| --- |
| <img src="https://github.com/Curovearth/Garuda-LaHacks/blob/main/gif's/code2.gif" align=center width=600> |
| <img src="https://github.com/Curovearth/Garuda-LaHacks/blob/main/gif's/code3.gif" align=center width=600> |
