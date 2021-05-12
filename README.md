# personal_assistant

1. [What you can find in this repository](#What-you-can-find-in-this-repository)
2. [Functionalities](#Functionalities)
3. [How to run it](#How-to-run-it)
4. [Connect with me](mailto:saharsh.shukla2018@vitstudent.ac.in)

## What you can find in this repository

Here you can find a personal assistant  that I have created to learn more about Text-To-Speech and Spee-to-Text techinques and practice with Python.

# Functionalities

Sophia (the virtual assistant), is able to:
* Search something su wikipedia for you
* Provide you the today's date
* Turn off your device
* Reboot your device
* Provide you information about the percentage of the battery and its state (plugged or not plugged)

# How to run it
```
# Activate the virtual environment 
source venv/bin/activate

# go in the source dirctory
cd src/

# Run the assistant
python assistant.py

# try to say 'Hello assistant'
# OR 'How are you' / 'What date is today'
# OR 'reboot my computer' / 'turn off my computer' etc...
```

## System requirements
* Python interpreter
* pyttsx3 ```pip install pyttsx3```
* libespeak1 ```sudo apt-get install libespeack1```
* SpeechRecognition ```pip install SpeechRecognition```
* PyAudio  ```pip install PyAudio```
* psutil ```wget https://bootstrap.pypa.io/get-pip.py -O - | python``` 
* mps-youtube ```pip install --upgrade youtube-dl```
* Python binding - vlc ``` https://wiki.videolan.org/Python_bindings/```
### Problems with PyAudio?
```sudo apt-get install portaudio19-dev python-pyaudio```
