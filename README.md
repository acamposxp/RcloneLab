[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/MinorMole/RcloneLab/blob/master/RcloneLab.ipynb)
[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/)
[![made-with-Markdown](https://img.shields.io/badge/Made%20with-Markdown-1f425f.svg)](https://commonmark.org/)
[![GitHub license](https://img.shields.io/github/license/MinorMole/RcloneLab.svg)](https://github.com/MinorMole/RcloneLab/blob/master/LICENSE)

## Introduction

[**RcloneLab**](https://minormole.github.io/RcloneLab/) is a rclone GUI for Google Colaboratory, similar to Rclone Browser. Please consider contributing our project, any improved version of the code is welcome and much appreciate.

[**rclone**](https://rclone.org/) ("rsync for cloud storage") is a command line program to sync files and directories to and from different cloud storage providers.

[**Google Colaboratory**](https://colab.research.google.com/) is a free Jupyter notebook environment that requires no setup and runs entirely in the cloud with high speed network. Check the VM's specification [here](https://github.com/MinorMole/RcloneLab/tree/master/VM's%20specification).

## Installation

1. Open the IPython Notebook file in Google Colaboratory by clicking [here](https://colab.research.google.com/github/MinorMole/RcloneLab/blob/master/RcloneLab.ipynb).
  
2. Choose where to load rclone.conf file by two methods below.

    2.1. Default, by upload rclone.conf from your computer. If you choose this method, uncheck the "Use_rclone_config_from_Google_Drive" checkbox.

    2.2. Use rclone.conf from your Google Drive storage. Check the "Use_rclone_config_from_Google_Drive" checkbox.
    
2. Click "Run cell" (play button) in the Installation section. Time Zone setup is optional for the correct time of log output.

    ![](https://github.com/MinorMole/RcloneLab/raw/master/docs/01.png)
  
4. Click "Run cell" (play button) in the "Usage" section to test if rclone can locate the rclone.conf file.

    > Note: If you choose to use rclone.conf from your Google Drive storage. Locate your rclone.conf in the Google Drive and paste the location in the Configuration section. (If file doesn't exist rclone will create it.)
    
    Example
    - My Drive/rclone.conf
    - Team Drives/Drive Name/rclone.conf

5. The RcloneLab is ready to use.

## Usage

Click "Run cell" (play button) in the RcloneLab section to run the rclone.

- Note: We recommend to use [Rclone Browser](https://github.com/DinCahill/RcloneBrowser) for file browsing and get path for RcloneLab.

## Licence

Licenced under the [MIT License](https://github.com/MinorMole/RcloneLab/blob/master/LICENSE).
