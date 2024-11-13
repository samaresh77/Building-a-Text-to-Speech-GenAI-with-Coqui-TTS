# Building-a-Text-to-Speech-GenAI-with-Coqui-TTS

To run code:

1. navigate into the project directory with:

cd C42-Text-to-Speech

2. Create a Python virtual environment to manage the project's dependencies by running the following command on your terminal:

python3 -m venv .venv

3. Now, activate the virtual environment:

On macOS/ Linux:

source .venv/bin/activate

On Windows:

.venv\Scripts\activate

4. With the virtual environment activated, install the necessary dependencies by running this command:

pip install -r requirements.txt

5. Now that your environment is set up, let’s generate your first speech output by running the following command:

tts --text "Hello Stackies and welcome to Getting Started with Speech Synthesis Campaign" --model_name tts_models/en/ek1/tacotron2 --out_path output/output.wav

6. python3 tts-app.py
