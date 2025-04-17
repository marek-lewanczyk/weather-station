# 🌦️ Weather Station - Smart Modular Weather Monitoring System: ⚙️ IN PROGRESS ⚙️

A modular IoT weather station built using **ESP8266 with MicroPython** as the sensing device and **Raspberry Pi** as the backend server.

---

## 📁 Repository Structure

This project is split into three independent Git submodules:

| Folder    | Description                                                           |
| --------- | --------------------------------------------------------------------- |
| `device/` | Firmware for ESP8266 (MicroPython) – handles sensor readings          |
| `server/` | Backend running on Raspberry Pi – MQTT listener, data logger, and API |

---

## 🚀 Getting Started

### ✅ Clone the repository with submodules:

```bash
git clone --recurse-submodules https://github.com/marek-lewanczyk/weather-station.git
```

If you already cloned it without submodules:

```bash
git submodule update --init --recursive
```

## Attribution

Parts of this project (e.g. 3D models) are based on work licensed under [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).

Original source: https://www.printables.com/model/729382-yaws-yet-another-weather-station/files

## License

This software is licensed under the [MIT License](https://mit-license.org). See [LICENSE](LICENSE) for details.
