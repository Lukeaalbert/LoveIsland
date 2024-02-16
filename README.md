# Love Island Narration

## Have you ever wanted to be on the reality TV show, "Love Island?" Well now you (kind of) can with this rather useless project.

This project was inspired by and based on Charlie Holtz's David Attenborough project.
This project uses Open AI's APIs to generate Love Island narration text for images that are captured by
your computer's camera. It then audibly narrates yourself in real time with ElevenLab's voice cloning, text-to-speech API.
The voice I cloned is based on the famous Iain Stirling ;).

### Setup

Clone this repo, setup and activate a virtualenv, and install the dependencies:

```bash
python3 -m pip install virtualenv
python3 -m virtualenv venv
source venv/bin/activate
```

`pip install -r requirements.txt`

Set API tokens:

```
export OPENAI_API_KEY=<token>
export ELEVENLABS_API_KEY=<eleven-token>
export ELEVENLABS_VOICE_ID=<voice-id>
```

### Run it!

In a terminal, run the program to capture images:
```bash
python capture.py
```
In another terminal, run the narrator program:
```bash
python narrator.py
```

I HOPE YOU ENJOY! - Luke Albert

