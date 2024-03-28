# Vigipool

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

### Produit Vigipool

Vous devez avec un produit Vigipool connecté à internet et connaitre l'adresse IP de l'équipement principal.

### Home Assisttant MQTT

Il faut auparavant avoir déjà configuré le MQTT de Home Assistant avant de lancer l'installeur.
Pour cela, voir ce lien : https://www.home-assistant.io/integrations/mqtt/

## Configuration

1. Connectez-vous à votre interface Home Assistant (http://homeassistant:8123/)
1. Cliquez sur "Paramètres"
1. Cliquez sur "Modules complémentaires"
1. Cliquez sur "Boutique des modules complémentaires"
1. Cliquez sur "Terminal & SSH"
1. Cliquez sur "Installer"
1. Cliquez sur "Ouvrir l'interface utilisateur web"
1. Copier la ligne suivante : `wget -q https://raw.githubusercontent.com/developer-ccei-pool/home-assistant-vigipool-installer/main/vigipool_installer.sh && chmod +x vigipool_installer.sh && bash vigipool_installer.sh`
1. Coller la ligne dans le terminal. Pour cela, vous pouvez utiliser le raccourci clavier suivant "Ctrl+shift+v" ou celui-ci "shift+ins"
1. Suivez les instructions qui s'affichent à l'écran.
1. Une fois terminé, allez dans votre tableau de bord pour voir les ajouts.
