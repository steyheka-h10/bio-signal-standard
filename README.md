# Bio-Signal Standard

An open-source project defining a standardized, human-readable data format for bio-signals collected by electronic tattoos and other wearable devices.

## Project Charter

### Purpose
The Bio-Signal Standard project aims to create a unified, interoperable data format for bio-signals such as ECG (heart rate), EMG, skin temperature, hydration, and other physiological metrics. By providing a clear, extensible, and machine-readable specification, we enable researchers, developers, and manufacturers to share, compare, and integrate data across different hardware and software platforms.

### Motivation
Wearable technology, especially electronic tattoos and flexible printed circuit boards (FPCBs), is rapidly advancing. However, the lack of a common data format creates silos, hinders collaboration, and slows innovation. This project addresses that gap by establishing an open, community‑driven standard that prioritizes accessibility, clarity, and extensibility.

### Target Audience
- **Researchers** in academia and industry who collect and analyze bio-signals.
- **Developers** building wearable applications, data visualization tools, or analytics pipelines.
- **Manufacturers** of electronic tattoos and flexible sensor systems who want their devices to interoperate with existing software ecosystems.
- **Open‑source contributors** interested in wearable technology, data standards, and interoperability.

### Scope (Version 1.0)
The initial release (v1.0) will focus on three core data types:
1. **Heart rate (ECG)** – raw or processed heart‑rate data.
2. **Skin temperature** – temperature measurements from on‑skin sensors.
3. **Generic motion sensor data** – accelerometer, gyroscope, or IMU readings.

Each data type will be defined by a JSON‑based schema that includes required fields, optional metadata, and units of measurement. The specification will also define common metadata fields (device ID, timestamp, sampling rate, etc.) that apply to all data types.

### Contributing
We welcome contributions from anyone passionate about wearable technology and open standards. Please review our [Contributing Guidelines](CONTRIBUTING.md) (to be added) and join the discussion in the [Issues](https://github.com/steyheka-h10/bio-signal-standard/issues) section.

### License
This project is licensed under the [MIT License](LICENSE).