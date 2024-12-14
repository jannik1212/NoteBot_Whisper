# NoteBot_Whisper

The goal of this project is to develop a **Discord bot** capable of **transcribing**, **translating**, and **summarizing** conversations in real time within Discord voice channels. The bot transcribes spoken audio and translates it into English, with added support for **Swiss German**, a language not commonly supported by transcription systems.

This repository contains the code for **fine-tuning Whisper** to support Swiss German. The **SwissDial dataset** from ETH Zurich, used for the fine-tuning process, can be downloaded [here](https://mtc.ethz.ch/publications/open-source/swiss-dial.html).

The fine-tuned **whisper-large-v2** model can be downloaded from [HuggingFace](https://huggingface.co/notebotIE/whisper-large-v2-swiss-german).

The repository for the **NoteBot Integration into Discord** can be found [here](https://github.com/Leo1212/NoteBot).


## TODOs

### 1. Set Up Your Development Environment
Run the following commands to create and activate the development environment:
```bash
conda create --name "notebot" python=3.11.9
conda activate notebot
pip install -r requirements.txt
```

### 2. Create the `.env` file. 
You have an example here `example.env` and place your required usernames and keys in it. 


