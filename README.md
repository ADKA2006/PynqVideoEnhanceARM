# PynqVideoEnhanceARM
Real-Time Video Enhancement on PYNQ using ARM Processor

**Features**

Contrast (Alpha): Adjusts the contrast to enhance image clarity.
Brightness (Beta): Changes brightness to manage the overall lighting of the video.
Saturation: Controls color intensity.
Hue: Modifies the hue, shifting colors in the video.
FPS Control: Dynamically changes the frame rate for real-time performance adjustments.
Edge Detection: Applies an edge-detection effect to highlight details.
Live Feedback: Displays FPS and parameter values in the video feed.

**Requirements**
Python 3.1.1
OpenCV (pip install opencv-python)
NumPy (pip install numpy)

**Installation**

Clone the repository:
git clone https://github.com/yourusername/RealTimeVideoEnhanceTool.git
cd RealTimeVideoEnhanceTool

**Install required Python packages:**

pip install -r requirements.txt

**Usage**

Run the script:
python enhance_video.py
The program will start capturing video from the default webcam. Adjust the parameters in real-time using the following keys:

Increase/Decrease Frame Rate: + / -
Increase/Decrease Contrast (Alpha): a / s
Increase/Decrease Brightness (Beta): d / f
Increase/Decrease Saturation: g / h
Increase/Decrease Hue: j / k
Increase/Decrease Edge Iterations: z / x
Quit: Press q
Adjusted parameter values and FPS are displayed in the video feed for reference.


