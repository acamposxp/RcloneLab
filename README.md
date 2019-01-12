[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MinorMole/RcloneLab/blob/master/RcloneLab.ipynb)

## Introduction

**RcloneLab** is a rclone GUI for Google Colaboratory made by MinorMole and pureexe

## Installation

1. Open the IPython Notebook file by clicking [here](https://colab.research.google.com/github/MinorMole/RcloneLab/blob/master/RcloneLab.ipynb).
2. Click "Run cell" (play button) in the Installation section.

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

    Note: Test checkbox is Dry-run
