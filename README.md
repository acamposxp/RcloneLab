[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MinorMole/RcloneLab/blob/master/RcloneLab.ipynb)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![made-with-Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg)](http://commonmark.org)
[![PyPI license](https://img.shields.io/pypi/l/ansicolortags.svg)](https://github.com/MinorMole/RcloneLab/raw/master/LICENSE)

## Introduction

**RcloneLab** is a rclone GUI for Google Colaboratory, similar to Rclone Browser. Please consider contributing our project, any improved version of the code is welcome and much appreciate.

[**rclone**](https://rclone.org/) ("rsync for cloud storage") is a command line program to sync files and directories to and from different cloud storage providers.

[**Google Colaboratory**](https://colab.research.google.com/) is a free Jupyter notebook environment that requires no setup and runs entirely in the cloud.

## Installation

1. Open the IPython Notebook file in Google Colaboratory by clicking [here](https://colab.research.google.com/github/MinorMole/RcloneLab/blob/master/RcloneLab.ipynb).
2. Click "Run cell" (play button) in the Installation section. Time Zone setup is optional for the correct time of log output.

    ![](https://github.com/MinorMole/RcloneLab/raw/master/docs/01.png)
  
3. Open the link in the output area and choose Google account you want to connect. Then copy the code to text box (Enter your authorization code:) and press Enter.

    ![](https://github.com/MinorMole/RcloneLab/raw/master/docs/02.png)
  
    If the operation successful this text "Mounted at /GD" will show in the output area.
  
4. Locate your rclone.conf in the Google Drive and paste the location in the Configuration section. (If file doesn't exist rclone will create it.)

    Example
    - My Drive/rclone.conf
    - Team Drives/Drive Name/rclone.conf
  
5. Click "Run cell" (play button) in the Configuration section to test if rclone can locate the rclone.conf file.
6. The RcloneLab is ready to use.

## Usage

Click "Run cell" (play button) in the RcloneLab section to run the rclone.

## Licence

Licenced under The [MIT License](https://github.com/MinorMole/RcloneLab/raw/master/LICENSE).
