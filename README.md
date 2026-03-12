# Kurt Armamento

Junior developer focused on IoT systems, practical backend tooling and Machine Learning Models. I build projects that are reproducible, well-documented, and demoable.

## Featured projects

### Room Sensor IoT (ESP8266 + Lua + MQTT + Node-RED + Discord)
End-to-end telemetry pipeline with alerts, a hardware-free simulator, and a Dockerized local stack (Mosquitto + Node-RED).
- [Repo](https://github.com/kurtarmamento/DHT11-IoT-lua-esp8266)

### Backend / Telemetry Ingest API (FastAPI, SQLite)
Ingests sensor readings over HTTP, validates payloads, stores latest-per-device, and exposes query endpoints (`/latest/{device_id}`) with tests + CI.
- Integrates with my IoT pipeline (MQTT → Node-RED → HTTP ingest).
- [Repo](https://github.com/kurtarmamento/telemetry-ingest-api)

### PyTorch Generative Models
Reproducible training/evaluation pipeline based on the Fashion MNIST dataset.
- Currently working on GAN implementation
- [Repo](https://github.com/kurtarmamento/pytorch-generative-models)

## WIPs
### Lua Remote Pump Monitor
A simulated pump controller that detects operating faults and communicates with an operator using MQTT, including remote control commands and fault reporting.
- Currently adding more features for more realistic simulation
- [Repo](https://github.com/kurtarmamento/lua-remote-pump-monitor)

### Prostate MRI Segmentation (U-Net)
Reproducible training/evaluation pipeline with metrics and artifacts based on HipMRI data.
- Currently squashing bugs with image rendering
- [Repo](https://github.com/kurtarmamento/prostate-unet)

### Unity ML-Agents Biped
Bipedal ML Agent learning to walk in Unity.
- Currently stabalising training towards steps rather than sliding
- [Repo](https://github.com/kurtarmamento/bipedal-ml-agent)

## Technical focus
- **Languages:** Python, Lua, JavaScript (Node-RED), C# (Unity)
- **IoT:** MQTT, Node-RED, ESP8266/NodeMCU, automation/alerts
- **Tooling:** Docker/Compose, Git/GitHub, Windows dev workflows
- **Machine Learning:** UNet, Improved UNet, VAE


## Contacts
- [GitHub](https://github.com/kurtarmamento)
- [LinkedIn](https://www.linkedin.com/in/kurt-armamento-892022211)
- [Website](https://kurtarmamento.github.io)
