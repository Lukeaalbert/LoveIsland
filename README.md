# Love Island

## Have you ever wondered what it would be like to star in "Love Island?"
### Well now you (kind of) can!

This project was inspired by and based on Charlie Holtz's (@cbn123) David Attenborough narration project.
This programs capture images via your personal computer camera, and utilizes Open AI APIs to
generate narration. Next Eleven Labs cloned voice text-to-speach API narrates you in real time with the voice of
the famous UK Love Island host, Iain Stirling.

### Walkthrough 
First, clone this repo, setup and activate a virtualenv, and install dependencies.

`python3 -m pip install virtualenv  
python3 -m virtualenv venv  
source venv/bin/activate  
pip install -r requirements.txt`

Next, set OpenAI and Eleven Labs tokens.

`export OPENAI_API_KEY=<token>
export ELEVENLABS_API_KEY=<eleven-token>
export ELEVENLABS_VOICE_ID=<voice-id>`

Finally, run it! On one terminal:

`python capture.py`

On another terminal:

`python narrator.py`
