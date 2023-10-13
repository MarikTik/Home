# Home: Smart Home Central Server

Welcome to the "Home" project, your central server for controlling and managing various smart home devices using your Raspberry Pi. This project transforms your Raspberry Pi into the brain of your smart home, allowing you to control and automate your devices effortlessly.

## Overview

The "Home" project acts as the command center for your smart home ecosystem, enabling you to:

- Control lighting, thermostats, and appliances.
- Monitor security cameras and sensors.
- Automate routines and scenarios.
- And much more!

## Prerequisites

Before you begin, ensure you have the following prerequisites:

- Raspberry Pi (with Raspbian OS or a compatible Linux distribution)
- Python 3.x installed on your Raspberry Pi
- Internet connection (for downloading dependencies)

## Installation

1. **Clone the Project**
    git clone https://github.com/MarikTik/Home.git
2. **Create Virtual Environment**
    python3 -m venv venv
3. **Activate the Environment and Download Dependencies**
    source venv/bin/activate
    pip install -r requirements.txt
4. **Run the APP**
    export FLASK_APP=main.py
    flask run --host 0.0.0.0
5. **Post Installation**
    ./init.sh