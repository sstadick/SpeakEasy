# SpeakEasy
An easy to set up Speech to Text system with some basic automation. 

# Install
* Note, this was done on Ubuntu 16.04
```bash
pip install virtualenv
cd <desired place for virtualenv>
virtualenv SpeakEasyPyEnv
source <path to SpeakEasyPyEnv>/bin/activate
sudo apt-get install libjack0
sudo apt-get install libjack-dev
sudo apt-get install portaudio19-dev && pip install --upgrade pyaudio
pip install wheel
sudo apt-get install python python-all-dev python-pip build-essential swig git
sudo pip install pocketsphinx
sudo pip install monotonic
sudo pip install SpeechRecognition


sudo apt-get install Audacity
sudo apt-get install vlc #(for ubuntu)
```

# Knowledge Sources
1. https://pypi.python.org/pypi/SpeechRecognition/
2. https://github.com/Uberi/speech_recognition/blob/master/examples/microphone_recognition.py
3. https://github.com/StevenHickson/PiAUISuite
4. https://help.ubuntu.com/community/AudioCapture
