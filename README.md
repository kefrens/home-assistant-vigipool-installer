# Home Assistant Vigipool Installer 

[![en](https://img.shields.io/badge/lang-en-white.svg)](https://github.com/developer-ccei-pool/home-assistant-vigipool-installer/blob/master/README.md)
[![fr](https://img.shields.io/badge/lang-fr-white.svg)](https://github.com/developer-ccei-pool/home-assistant-vigipool-installer/blob/master/README.fr.md)

Vigipool is an innovative app to control and manage your swimming pool remotely.

This installer will configure Home Assistant to add the main features of the Vigipool application to your interface.

List of Vigipool devices compatible with the installer:
- Tild
- Phileo VP
- Ofix
- AnteaM
- Zelia
- VigiBrio

## Prerequisites

### Home Assistant MQTT

- Warning ! Home Assistant cannot connect to several MQTT servers so this script cannot be used if the Vigipool product is not the MQTT server

- You must first have already configured the Home Assistant MQTT before launching the installer. To do this, see this link: https://www.home-assistant.io/integrations/mqtt/

### Vigipool product

- Have a Vigipool product
- Use the Vigipool mobile application to connect to the Vigipool product then configure the product to connect it to your Wi-Fi and know its IP

## Configuration

1. Connect to your Home Assistant interface (http://homeassistant:8123/)
1. Click “Settings”
1. Click “Add-ons”
1. Click “Add-ons Store”
1. Click “Terminal & SSH”
1. Click “Install”
1. Click "Open Web UI"
1. Copy the following line: `wget -q https://raw.githubusercontent.com/developer-ccei-pool/home-assistant-vigipool-installer/main/vigipool_installer.sh && chmod +x vigipool_installer.sh && bash vigipool_installer.sh`
1. Paste the line into the terminal. To do this, you can use the following keyboard shortcut "Ctrl+shift+v" or this one "shift+ins"
1. Follow the terminal instructions.
1. Once it's done, go to your dashboard to see the changes.