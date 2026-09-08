# 🔎 NeoX IP Finder

**NeoX IP Finder** is a Python-based GeoIP lookup tool that retrieves approximate geographical information associated with an IP address.

> ⚠️ GeoIP information is approximate. An IP address does not reveal a person's exact physical location.

## ✨ Features

* 🌐 IP address lookup
* 🌍 Country information
* 🚩 Country flag
* 🏙️ City and region
* 📮 ZIP / postal code
* 📍 Latitude and longitude
* 🛰️ ISP information
* 🏢 Organization information
* 🔢 ASN information
* 🕒 Timezone
* 🗺️ Google Maps link
* 📜 IP lookup history
* 🎨 NeoX Cyber terminal interface

## 📋 Requirements

* Windows 10/11
* Python 3.10+
* Internet connection

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/NeoX-Cyber/IP-Finder.git
```

Enter the project directory:

```bash
cd IP-Finder
```

Install the required Python package:

```bash
pip install -r requirements.txt
```

## 🚀 Usage

Run the program:

```bash
python ip_finder.py
```

The program provides three main options:

```text
[1] Locate IP
[2] IP History
[3] Exit
```

Enter an IP address when requested.

The tool will display available GeoIP information and generate a Google Maps URL based on the returned coordinates.

## 🗺️ Google Maps

The program generates a Google Maps URL using the latitude and longitude returned by the GeoIP service.

Example:

```text
https://www.google.com/maps?q=40.4093,49.8671
```

## 📜 IP History

IP lookups performed during the current program session are stored in memory and can be viewed through:

```text
[2] IP History
```

The history is not a database and is cleared when the program exits.

## ⚠️ Disclaimer

This project is intended for educational purposes, cybersecurity learning, network administration, and authorized testing.

GeoIP databases and APIs provide approximate location information. The results should not be interpreted as an exact physical location.

Only use this tool on IP addresses that you are authorized to investigate.

The developer is not responsible for misuse of this software.

## 📄 License

This project is released under the MIT License.

See [`LICENSE`](LICENSE) for details.

## 👨‍💻 Author

**NeoX-Cyber**

GitHub: https://github.com/NeoX-Cyber

---

⭐ If you find this project useful, consider giving it a star.
