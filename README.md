# 🌦️ Weather Station - Smart Modular Weather Monitoring System

A modular IoT weather station built using **ESP8266 with MicroPython** as the sensing device and **Raspberry Pi** as the backend server.

# ⚙️ IN PROGRESS ⚙️

🚧 This project is currently in active development. Expect frequent changes, new features, and occasional bugs.

## ✨ Planned Features

The project aims to provide a complete, modular and extensible weather monitoring system. Key planned features include:

- 📡 Wireless communication between sensor node and server
- 🌡️ Support for common weather sensors:
  - Temperature
  - Humidity
  - Atmospheric pressure
  - Wind speed and direction
  - Rainfall
- 🧠 Central processing and data aggregation
- 💾 Data logging for long-term analysis
- 📊 Visualization of collected weather data (locally or remotely)
- ⚙️ Modular codebase and easy hardware expansion
- 🔧 Setup scripts and automation for quick deployment

This feature set may grow as the project evolves!

## 📁 Repository Structure

This project is split into three independent Git submodules:

| Folder    | Description                                    |
| --------- | ---------------------------------------------- |
| `device/` | Software for ESP8266 – handles sensor readings |
| `server/` | Backend running on Raspberry Pi                |

## 🚀 Getting Started

### ✅ Clone the repository with submodules:

```bash
git clone --recurse-submodules https://github.com/marek-lewanczyk/weather-station.git
```

If you already cloned it without submodules:

```bash
git submodule update --init --recursive
```

## 🙌 Attribution

Elements of this project are inspired by:

- **Raspberry Pi Foundation**  
  "Build Your Own Weather Station"

  [https://projects.raspberrypi.org/en/projects/build-your-own-weather-station](https://projects.raspberrypi.org/en/projects/build-your-own-weather-station)

  Licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)

- **Matteo Domanin**
  "YAWS, Yet Another Weather Station"

  [https://www.printables.com/model/729382-yaws-yet-another-weather-station/files](https://www.printables.com/model/729382-yaws-yet-another-weather-station/files)

  Licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)

## 👥 Authors

This project is developed and maintained by:

- [**Marek Lewańczyk**](https://github.com/marek-lewanczyk)
- [**Katarzyna Kasperek**](https://github.com/s27553-pj)

  If you'd like to contribute, feel free to open an issue or a pull request 💡

## 📄 License

This software is licensed under the [MIT License](https://mit-license.org). See [LICENSE](LICENSE) for details.
