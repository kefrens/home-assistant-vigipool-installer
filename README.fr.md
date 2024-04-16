# Home Assistant Vigipool Installer 

[![en](https://img.shields.io/badge/lang-en-white.svg)](https://github.com/developer-ccei-pool/home-assistant-vigipool-installer/blob/master/README.md)
[![fr](https://img.shields.io/badge/lang-fr-white.svg)](https://github.com/developer-ccei-pool/home-assistant-vigipool-installer/blob/master/README.fr.md)

Vigipool est une appli innovante pour contrôler et piloter votre piscine à distance.

Cet installateur va configurer Home Assistant pour ajouter les principales fonctionnalités de l'application Vigipool à votre interface.

Liste des équipements Vigipool compatibles avec l'installateur : 
- Tild
- Phileo VP
- Ofix
- AnteaM
- Zelia
- VigiBrio 

## Prérequis

### Home Assisttant MQTT

- Attention ! Home Assisstant ne peut pas se connecter sur plusieurs serveurs MQTT donc ce script n'est pas utilisable si le produit Vigipool n'est pas le serveur MQTT

- Il faut auparavant avoir déjà configuré le MQTT de Home Assistant avant de lancer l'installeur. Pour cela, voir ce lien : https://www.home-assistant.io/integrations/mqtt/

### Produit Vigipool

- Avoir un produit Vigipool
- Utiliser l'application mobile Vigipool pour se connecter au produit Vigipool puis configurer le produit pour le connecter à votre Wi-Fi et connaitre son IP

## Configuration


1. Connectez-vous à votre interface Home Assistant (http://homeassistant:8123/)

1. Cliquez sur "Paramètres" ![step 1](https://raw.githubusercontent.com/developer-ccei-pool/home-assistant-vigipool-installer/main/img/fr/1.png)

1. Cliquez sur "Modules complémentaires" ![step 2](https://raw.githubusercontent.com/developer-ccei-pool/home-assistant-vigipool-installer/main/img/fr/2.png)

1. Cliquez sur "Boutique des modules complémentaires" ![step 3](https://raw.githubusercontent.com/developer-ccei-pool/home-assistant-vigipool-installer/main/img/fr/3.png)

1. Cliquez sur "Terminal & SSH" (Si le module n'apparait pas, c'est que votre compte n'est pas en mode avancée, un message devrait automatiquement apparaître qui vous redirigera vers le menu pour activer cette fonctionnalité si c'est le cas.) ![step 4](https://raw.githubusercontent.com/developer-ccei-pool/home-assistant-vigipool-installer/main/img/fr/4.png)

1. Cliquez sur "Installer" ![step 5](https://raw.githubusercontent.com/developer-ccei-pool/home-assistant-vigipool-installer/main/img/fr/5.png)

1. Cliquez sur "Démarrer" ![step 6](https://raw.githubusercontent.com/developer-ccei-pool/home-assistant-vigipool-installer/main/img/fr/6.png)

1. Cliquez sur "Ouvrir l'interface utilisateur web" ![step 7](https://raw.githubusercontent.com/developer-ccei-pool/home-assistant-vigipool-installer/main/img/fr/7.png)

1. Copier la ligne suivante : 
######
    wget -q https://raw.githubusercontent.com/developer-ccei-pool/home-assistant-vigipool-installer/main/vigipool_installer.sh && chmod +x vigipool_installer.sh && bash vigipool_installer.sh

10. Coller la ligne dans le terminal. Pour cela, vous pouvez utiliser le raccourci clavier suivant "Ctrl+shift+v" ou celui-ci "shift+ins" ![step 8](https://raw.githubusercontent.com/developer-ccei-pool/home-assistant-vigipool-installer/main/img/fr/8.png)

1. Suivez les instructions qui s'affichent à l'écran.

1. Une fois terminé, allez dans votre tableau de bord pour voir les ajouts.
