
#si_twin 

LynxAI, Inc

Connect us at support@lynxai.io


## Introduction
The main objective of this example is to demonstrate the standalone functionality of the silicon twin. It utilizes test data included in the release and provides output in the form of a waveform (VCD) along with a graphical user interface (GUI) that illustrates the accuracy of the model's output compared to the training dataset."

## Background
AI model described in the provided information is designed to solve challenges related to testing and verifying complex hardware IPs by creating a virtual representation that replicates their behavior accurately, simplifies testing, and assists in output validation. It aims to streamline the hardware development and verification process, making it more efficient and reliable.

## LynxAI's Solution
AI model described in the provided information is designed to solve challenges related to testing and verifying complex hardware IPs by creating a virtual representation that replicates their behavior accurately, simplifies testing, and assists in output validation. It aims to streamline the hardware development and verification process, making it more efficient and reliable.

[si_twin](https://github.com/lynxai-eng/S_Parameter_Generator/blob/main/S_Parameter_Generator.pdf)
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
- After execution new folder will be created as follows: 
```bash
    infer000{n}    // example infer0001,infer0002....
```
- In this folder have vcd files

![alt text](https://github.com/lynxai-eng/si_twin/blob/main/1.png)
![alt text](https://github.com/lynxai-eng/si_twin/blob/main/2.png)
![alt text](https://github.com/lynxai-eng/si_twin/blob/main/3.png)
 
![Logo](https://lynxai.io/wp-content/uploads/2021/11/AynxAi-Logo-design-final-min-1536x1536-1.png)


## Feedback

If you have any feedback, please reach out to us at support@lynxai.io