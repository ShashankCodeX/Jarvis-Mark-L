# MARK L

A desktop voice assistant that uses the Gemini Live API to talk with you and help control your computer.

This project builds on the work shared in the [original MARK L project](https://github.com/FatihMakes/Mark-L) and retains its [Creative Commons BY-NC 4.0 license](https://creativecommons.org/licenses/by-nc/4.0/).

## What it can do

- Have real-time voice conversations and accept typed commands.
- Answer questions using web search, news, weather, and flight lookup.
- Open apps, control supported desktop functions, and interact with a browser.
- Capture the screen or camera for visual questions (with your permission).
- Read and summarize local files, and help with code.
- Set reminders, remember preferences between sessions, and show a remote-control dashboard.

Some capabilities depend on your operating system, installed applications, microphone, camera, and internet access.

## Setup

### Requirements

- Python 3.11 or 3.12
- A Gemini API key
- A microphone for voice conversations
- Windows, macOS, or Linux; some controls are platform-specific

### macOS or Linux

```bash
git clone https://github.com/ShashankCodeX/Jarvis-Mark-L.git
cd Jarvis-Mark-L
python3 -m venv venv
source venv/bin/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
python main.py
```

### Windows

```powershell
git clone https://github.com/ShashankCodeX/Jarvis-Mark-L.git
cd Jarvis-Mark-L
py -3.12 -m venv venv
venv\Scripts\activate
python -m pip install --upgrade pip
pip install -r requirements.txt
python main.py
```

On first launch, use the setup screen to enter your Gemini API key and select your operating system. The app saves these settings to `config/api_keys.json` on your computer.

If your system does not have Python 3.12 installed, install Python 3.11 or 3.12 first. Some optional features may need additional OS-specific packages or permissions.

## Keeping your data private

API keys, certificates, personal memory, virtual environments, and browser downloads are excluded from Git. Do not add secrets or personal data to the repository. `config/api_keys.example.json` is a blank example, not a working API key.

## License

This fork retains the original project's CC BY-NC 4.0 license. See the [license terms](https://creativecommons.org/licenses/by-nc/4.0/) and the original [MARK L project](https://github.com/FatihMakes/Mark-L).
