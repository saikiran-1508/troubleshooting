# Development setup

Target platform: Windows. The local prototype was checked using Python 3.13.

Create an isolated environment from the repository folder:

```powershell
python -m venv .venv
.\.venv\Scripts\python.exe -m pip install -r requirements.txt
```

Download `vosk-model-small-en-us-0.15` from the official model list:
https://alphacephei.com/vosk/models

Extract it into `models/vosk-model-small-en-us-0.15/`. The extracted directory
should contain `am/final.mdl`. The environment and model files are excluded from
Git because they can be installed or downloaded separately.

A microphone and Windows permission for desktop apps to access it are required.
The model download and dependency installation need internet access; the local
speech workflow operates offline afterward.

The source and launch scripts are not part of this first publication. Installing
dependencies alone does not provide a runnable assistant yet.
