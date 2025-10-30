# Sora 2 Ai watermark remover
![License](https://img.shields.io/badge/license-GPLv3-green.svg?style=flat)

# Description
This project is designed to precisely remove watermarks from Sora 2 generated videos using AI.

# How it works?
This project uses AI to remove watermarks from Sora 2 generated videos. When a user uploads a video, the system analyzes each frame to detect the watermark and removes it using inpainting. The processed video is then rendered and returned to the user.

# Requirements🛠
- Python 3.10+
- Windows/MacOS/Linux
- At least 4GB of RAM
- [ffmpeg](https://ffmpeg.org/download.html)

# Installation
Before using the watermark remover, you need to set it up on your pc. Clone it using Git:
```bash
git clone https://github.com/hate0s/sora2-watermark-remover
```
Then you need to install the dependencies:
```bash
cd sora2-watermark-remover
pip install requirements.txt
```

# Usage

To start using the program, launch the main.py file:
```bash
python main.py
````
This will open a web page in your browser where you can upload your videos.
The processed results will be saved in the output folder.

Also, you can use the web server version for your projects.
Run **server.py:**
```bash
python server.py
```

The web server will start on port 8000.



# Donations & Sponsorship

If you find this project useful, consider supporting future development:
- **BTC**: bc1q8grhtxdw37npcdadm7xa848vquqgurj9ecvpex
- **ERC20**: 0x2d19c72fb8b3a7cdc7fa4970b5c777966f547854

**Thank you!🙏**

