# TonyPiRobot

A PyQt5-based desktop application for robot control and management with a modern GUI interface.

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/python-3.7-blue.svg)](https://www.python.org/)
[![PyQt5](https://img.shields.io/badge/PyQt5-5.15-green.svg)](https://www.riverbankcomputing.com/software/pyqt/)

## 📋 Table of Contents

- [TonyPiRobot](#tonypirobot)
  - [📋 Table of Contents](#-table-of-contents)
  - [About The Project](#about-the-project)
    - [Built With](#built-with)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installation](#installation)
      - [Option 1: Using Pre-built Executable (Windows)](#option-1-using-pre-built-executable-windows)
      - [Option 2: Running from Source](#option-2-running-from-source)
  - [Usage](#usage)
    - [Key Features](#key-features)
  - [Screenshots](#screenshots)
  - [Roadmap](#roadmap)
  - [Contributing](#contributing)
  - [License](#license)
  - [Contact](#contact)
  - [Acknowledgments](#acknowledgments)

## About The Project

TonyPiRobot is a desktop application built with PyQt5 that provides a comprehensive interface for controlling and managing robot systems. The application features a modern GUI with web engine capabilities, network communication, and positioning services.

### Built With

- [Python](https://www.python.org/) 3.7
- [PyQt5](https://www.riverbankcomputing.com/software/pyqt/) - GUI framework
- [Qt5 WebEngine](https://doc.qt.io/qt-5/qtwebengine-index.html) - Embedded web browser
- [Qt5 Network](https://doc.qt.io/qt-5/qtnetwork-index.html) - Network communication
- [Qt5 Positioning](https://doc.qt.io/qt-5/qtpositioning-index.html) - Location services

## Getting Started

### Prerequisites

- Windows 10/11 (64-bit)
- Python 3.7 (if running from source)
- Git (for cloning the repository)

### Installation

#### Option 1: Using Pre-built Executable (Windows)

1. Download the latest release from the releases page
2. Extract the `main` folder
3. Run `main.exe` from the extracted folder

#### Option 2: Running from Source

1. Clone the repository
   ```bash
   git clone https://github.com/yourusername/TonyPiRobot.git
   ```

2. Navigate to the project directory
   ```bash
   cd TonyPiRobot
   ```

3. Install dependencies
   ```bash
   pip install PyQt5
   pip install netifaces
   ```

4. Run the application
   ```bash
   python main.py
   # or if you have the source file
   python -m main
   ```

## Usage

Launch the application by running `main.exe` (Windows) or executing the Python script. The application provides a graphical interface for robot control and management.

### Key Features

- **Modern GUI Interface**: Built with PyQt5 for a responsive and intuitive user experience
- **Web Engine Integration**: Embedded web browser capabilities for displaying web-based content
- **Network Communication**: Built-in network support for robot communication and data transfer
- **Positioning Services**: Location and positioning features for robot navigation
- **Cross-platform Ready**: Windows executable included, can be built for other platforms

## Screenshots

_Add screenshots or GIFs of your project here once available._

![Project Screenshot](screenshot.png)

## Roadmap

Planned features and future improvements:

- [ ] Linux and macOS builds
- [ ] Enhanced robot control protocols
- [ ] Real-time sensor data visualization
- [ ] Remote control capabilities
- [ ] Configuration management system
- [ ] Logging and debugging tools

See the [open issues](https://github.com/yourusername/TonyPiRobot/issues) for a full list of proposed features (and known issues).

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Project Link: [https://github.com/yourusername/TonyPiRobot](https://github.com/yourusername/TonyPiRobot)

## Acknowledgments

- [PyQt5](https://www.riverbankcomputing.com/software/pyqt/) - Python bindings for Qt5
- [Qt Framework](https://www.qt.io/) - Cross-platform application framework
- [Shields.io](https://shields.io/) - Badge generation
- [Choose an Open Source License](https://choosealicense.com/) - License guidance


