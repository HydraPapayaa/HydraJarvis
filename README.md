# HydraJarvis
Un jarvis casero en muy muy muy fase beta


// bash
# Linux
curl -fsSL https://ollama.com/install.sh | sh
sudo dnf install ffmpeg openssl wmctrl   # Debian/Ubuntu: sudo apt install ...
cd HydraJarvis && ./run.sh

// powershell
# Windows (PowerShell)
winget install -e --id Ollama.Ollama
winget install -e --id Gyan.FFmpeg
winget install -e --id ShiningLight.OpenSSL.Light
cd HydraJarvis; python run.py
