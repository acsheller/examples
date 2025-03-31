# GNURadio + XFCE + noVNC Dev Environment

🛰️ Remote-ready SDR container with:
- GNU Radio + RTL-SDR
- XFCE desktop over noVNC (access via browser)
- CUDA 12.6.2 for DSP acceleration
- Visual Studio Code + Chrome inside

## 🚀 Usage

```bash
export MY_UID=$(id -u)
export MY_GID=$(id -g)
docker-compose up --build
