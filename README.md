# RustyGPT
Voice Assistant with OpenAI and Speech Recognition
This Python script uses the OpenAI API and Speech Recognition library to create a voice assistant that can process voice input, convert it into text, and respond using OpenAI's GPT-3.5 model.

Installation
Clone the repository:
git clone https://github.com/AdelJumaily/RustyGPT.git
Navigate to the project directory:


cd your-voice-assistant
Install the required libraries:
You need to install several Python libraries to run the voice assistant. Open a terminal and run the following command:

pip install: pyaudio, speechrecognition, playsound, gtts, and openai
Obtain an OpenAI API key:
```bash
pip install pyaudio
```
```bash
speechrecognition
```
```bash
playsound
```
```bash
gtts
```
```bash
openai
```


Sign up for an account at https://beta.openai.com/signup/
Create a new API key in your OpenAI account dashboard.
Replace Place OpenAi API Here in the script with your actual API key.

Usage
Run the script:
To start the voice assistant, navigate to the project directory in your terminal and run the following command:
python voice_assistant.py
Interacting with the assistant:

Once the script is running, the voice assistant will listen for your voice input.
Say "Rusty" followed by your command to interact with the assistant.
Assistant's Response:

The assistant will convert your voice input into text using the Speech Recognition library.
It will then send the text to the GPT-3.5 model provided by OpenAI for processing.
The assistant will respond with generated text, which will be converted into speech and played back to you using the playsound and gTTS libraries.
Contributing
If you would like to contribute to the project, feel free to fork the repository, make your changes, and create a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/AdelJumaily/RustyGPT/blob/main/LICENSE) file for details.
