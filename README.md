# Alvate

Alvate aims to tackle the rising anxiety and intimacy problems amongst teens by using AI to create positive reinforcement in the day-to-day experience and thoughts of the users. The product, a personal motivation video generator, takes short day-to-day commentary from the user and a video of a person speaking and generates a video of the person giving the user a positive reinforcement comment. Our goal is to provide users a comforting words from a comforting face and increase their mood/motivation.



This repository contains the core processing for the product, inputting a resume of how the user is feeling, and having as output Neil deGrasse Tyson saying an uplifting comment (if you want another avatar you can save a short video of someone talking in the root folder under the name of `video.mp4`). 

The code is based on the implementation of the following papers:

|📑 Transfer Learning from Speaker Verification to Multispeaker Text-To-Speech Synthesis | 📑  Lip Sync Expert Is All You Need for Speech to Lip Generation In the Wild
|:-:|:-:|
[Paper](https://arxiv.org/pdf/1806.04558.pdf) | [Paper](https://arxiv.org/abs/2008.10010) |


Prerequisites
-------------
- Your [ChatGPT API KEY](https://platform.openai.com/account/api-keys) on `alvate.py`
- `Python 3.6` 
- ffmpeg: `sudo apt-get install ffmpeg`
- Install PyTorch. Pick the latest stable version, your operating system, your package manager (pip by default) and finally pick any of the proposed CUDA versions if you have a GPU, otherwise pick CPU. Run the given command.
- Install necessary packages using `pip install -r requirements.txt`.  
- Download Pretrained Models: 

[Download this](https://drive.google.com/file/d/13fNxK2M7Kz05mvJFOTzjytK0i78cE5ug/view?usp=share_link) to Path: 
`./saved_models/default`


[Download this](https://iiitaphyd-my.sharepoint.com/:u:/g/personal/radrabha_m_research_iiit_ac_in/Eb3LEzbfuKlJiR600lQWRxgBIY27JZg80f7V9jtMfbNDaQ?e=TBFBVW
) to Path: 
`./checkpoints`

[Download this](https://www.adrianbulat.com/downloads/python-fan/s3fd-619a316812.pth) to Path: 
`./face_detection/detection/sfd/s3fd.pth`

Run project
-------------
After installing all the dependencies, you can run the project with `python3 main.py`
