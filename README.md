AI-Powered Multilingual Voice Translator  

- ![image alt](https://github.com/ShiruvatiNarasimha/AI-Voice-Translator/blob/29e6acd31d77fa258cfd94ecc84a6649bb9d4c4f/Screenshot%202024-11-24%20191728.png)

## Overview  
This project is a *real-time voice translation system* designed to facilitate seamless communication across multiple languages. Using advanced AI technologies, the system transcribes speech, translates it, and reproduces the voice output in a natural, expressive tone while retaining the speaker's original style and emotion.  

## Features  
- *Real-Time Translation*: Instant voice-to-voice translation across multiple languages.  
- *Voice Recognition: High-accuracy transcription using **Assembly AI*.  
- *Natural Voice Output: Generates expressive, natural-sounding speech with **ElevenLabs*.  
- *Multilingual Support*: Enables communication in diverse languages.  
- *Personalized Output*: Retains the speaker's tone and voice style for familiarity.



## Technologies Used  
- *Programming Language*: Python  
- *APIs and Libraries*:  
  - [Assembly AI](https://www.assemblyai.com/) for voice-to-text transcription.  
  - [ElevenLabs](https://elevenlabs.io/) for voice synthesis and cloning.  

## Installation  
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/voice-translator.git
   cd voice-translator

2. Create a virtual environment:

python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate


3. Install dependencies:

pip install -r requirements.txt



Usage

1. Obtain API keys for Assembly AI and ElevenLabs.


2. Add your API keys to an .env file:

ASSEMBLYAI_API_KEY=your_assemblyai_key
ELEVENLABS_API_KEY=your_elevenlabs_key


3. Run the application:

python main.py


4. Speak into your microphone, and the system will process and translate your voice in real time.



Contributing

Contributions are welcome! Feel free to fork the repository and submit pull requests.

License

This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements

Assembly AI

ElevenLabs


Replace "yourusername" in the GitHub URL and add a requirements.txt file if needed.
