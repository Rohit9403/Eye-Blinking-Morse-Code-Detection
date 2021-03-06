# Eye-Blinking-Morse-Code-Detection
Blinking eye can send a Morse Code. The goal of the project is to detect the morse code and convert it into a readable message.
This project has been completed by help from eye blink detection tutorial of [pyimagesearch.com](https://www.pyimagesearch.com/2017/04/24/eye-blink-detection-opencv-python-dlib/)

## Story behind eye blink Morse Code
In 1966, while being held as a POW by the North Vietnamese, the American aviator Jeremiah Denton appeared in a televised interview with a Japanese reporter. When asked about the conditions under which he was being held, Denton said, "I get adequate food, adequate clothing and medical care when I require it." But notice the labored way in which Denton blinks his eyes while he is talking. As a Naval Aviator, Denton was trained in the use of Morse Code and he took this opportunity to blink out a coded message to any American forces that might be watching. In a sense, he was using his eyelids to say something very different than what he was saying with his mouth.

The interview was pure propaganda; the North Vietnamese had scripted Denton's response to the questions. But his blinking gave the U.S. Office of Naval Intelligence its first confirmation that American captives were being tortured behind enemy lines. The story is remarkable not only for Denton's incredible heroism but also for the effectiveness of his communication. It was only with the benefit of a well designed code that he was able to say so much, so unambiguously, with fifteen well-timed blinks.

![Admiral](https://github.com/Rohit9403/Eye-Blinking-Morse-Code-Detection/blob/master/Admiral.gif)


## Working
- DOT  "." : Short Blink
- Dash "-" : Long Blink
- Next Word: Too Long Blink

## Downloads and libraries
- [shape_predictor_68_face_landmarks.dat](https://www.pyimagesearch.com/2017/04/24/eye-blink-detection-opencv-python-dlib/#download-the-code)
- dlib
- OpenCV

## How to run 
Download the files mentioned in downloads section and install libraries specified.Then clone this repository or Download and run following:
- To run it on Web Cam 

`-python eye_blink_Morse.py --shape-predictor shape_predictor_68_face_landmarks.dat`
- To run it on recorded video 

`-python eye_blink_Morse.py --shape-predictor shape_predictor_68_face_landmarks.dat --video blink_detection_demo.mp4`

**NOTE:** Uncomment Line 106,117 & 118 and Comment line 108

## Demo
[YouTube Link](https://www.youtube.com/watch?v=Vs00hD6b60I)
