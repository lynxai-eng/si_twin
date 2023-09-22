
## si_twin 

LynxAI, Inc

Connect us at support@lynxai.io


## Introduction
The main objective of this example is to demonstrate the standalone functionality of the silicon twin. It utilizes test data included in the release and provides output in the form of a waveform (VCD) along with a graphical user interface (GUI) that illustrates the accuracy of the model's output compared to the training dataset."
AI model described in the provided information is designed to solve challenges related to testing and verifying complex hardware IPs by creating a virtual representation that replicates their behavior accurately, simplifies testing, and assists in output validation. It aims to streamline the hardware development and verification process, making it more efficient and reliable.

## LynxAI's Solution
AI model described in the provided information is designed to solve challenges related to testing and verifying complex hardware IPs by creating a virtual representation that replicates their behavior accurately, simplifies testing, and assists in output validation. It aims to streamline the hardware development and verification process, making it more efficient and reliable.

[si_twin](https://github.com/lynxai-eng/si_twin/blob/main/silicon_twin_demo.pdf)
## Installation
- Python3.9 required
- This is a Linux release of LynxAI app. Please contact LynxAI for other OS support at support@lynxai.io

clone repository

```bash
    git clone https://github.com/lynxai-eng/si_twin.git
```

install packages 
```bash
    cd si_twin
    pip install -r requirements.txt
```

## Usage/Examples

Input file Example


-  Execute following command to run the app

```bash
    python3 si_twin.py 
```
- si_twin app interface 

![alt text](https://github.com/lynxai-eng/si_twin/blob/main/1.png)
- The GUI displays the result of the model. 
1. The top left window shows the accuracy of the model output against the anticipated output from the Ethernet MAC API. 
2. The Top right displays the failing signals, on a scale of 0 to 1, with 1 being 100% match. For example a signal that is 0.8 indicates  80% success.
3. The bottom window is drilling down into specificity of the failing cycles and the states for which they are failing

![alt text](https://github.com/lynxai-eng/si_twin/blob/main/2.png)
- The VCD file is generated in the following folder

![alt text](https://github.com/lynxai-eng/si_twin/blob/main/3.png)
- After execution new folder will be created as follows: 
```bash
    infer000{n}    // example infer0001,infer0002....
```



 
![Logo](https://lynxai.io/wp-content/uploads/2021/11/AynxAi-Logo-design-final-min-1536x1536-1.png)


## Feedback

If you have any feedback, please reach out to us at support@lynxai.io