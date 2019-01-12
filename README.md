[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MinorMole/RcloneLab/blob/master/RcloneLab.ipynb)

## Introduction

**RcloneLab** is a rclone GUI for Google Colaboratory, similar to Rclone Browser. Please consider contributing our project, any improved version of the code is welcome and much appreciate.

**Google Colaboratory** is a free Jupyter notebook environment that requires no setup and runs entirely in the cloud.

## Installation

1. Open the IPython Notebook file in Google Colaboratory by clicking [here](https://colab.research.google.com/github/MinorMole/RcloneLab/blob/master/RcloneLab.ipynb).
2. Click "Run cell" (play button) in the Installation section. Time Zone setup is optional for the correct time of log output.

    ![](https://github.com/MinorMole/RcloneLab/raw/master/docs/01.png)
  
3. Open the link in the output area and choose Google account you want to connect. Then copy the code to text box (Enter your authorization code:) and press Enter.

    ![](https://github.com/MinorMole/RcloneLab/raw/master/docs/02.png)
  
    If the operation successful this text "Mounted at /GD" will show in the output area.
  
4. Locate your rclone.conf in the Google Drive and paste the location in the Configuration section. (If file doesn't exist rclone will create it.)

    Example
  - Team Drives/rclone.conf
  - My Drive/rclone.conf
  
5. Click "Run cell" (play button) in the Configuration section to test if rclone can locate the rclone.conf file.
6. The RcloneLab is ready to use.

## Usage

Click "Run cell" (play button) in the RcloneLab section to run the rclone.
