# DeZ_chatbot_Pytorch

# Chatbot Deployment with Flask and JavaScript

Chatbot [DeZ](https://github.com/Logeshvarman/DeZ_chatbot_Pytorch)  with Flask and JavaScript.

This gives 2 deployment options:
- Deploy within Flask app with jinja2 template
- Serve only the Flask prediction API. The used html and javascript files can be included in any Frontend application (with only a slight modification) and can run completely separate from the Flask App then.

## Initial Setup:
This repo currently contains the starter files.

Clone repo and create a virtual environment
```
$ git clone https://github.com/Logeshvarman/DeZ_chatbot_Pytorch.git
$ cd DeZ
$ conda create --name DeZ
$ conda activate DeZ
```
Install dependencies
```
$ (DeZ) conda install Flask torch torchvision nltk
```
Install nltk package

Modify `intents.json` with different intents and responses for your Chatbot

Run
```
$ (Dez) python train.py
```
This will dump data.pth file. And then run
the following command to test it in the console.
```
$ (Dez) python chat.py

```
❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️
❤️from ❤️❤️❤️❤️❤️❤️❤️
❤️❤️❤️CodeZ❤️❤️❤️❤️❤️
❤️❤️❤️❤️❤️Developers❤️
❤️❤️❤️❤️❤️❤️❤️❤️❤️❤️
