# Stelpro Ki Z-Wave - Outdoor Temperature
Home Assistant Z-Wave JS / Z-Wave JS UI blueprint for displaying outdoor temperature on Stelpro Ki Z-Wave STZW402+ thermostats
Blueprint Home Assistant Z-Wave JS / Z-Wave JS UI pour afficher la température extérieure sur les thermostats Stelpro Ki Z-Wave STZW402+

<img src="https://github.com/user-attachments/assets/7e13b9b7-c5ce-4e10-933d-20930804cef6" width="300" />

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.me/AlainRaymond564)

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://github.com/alray31/STZW402/blob/main/StelproKi.yaml)

## English:
This blueprint does the following:
  
* Retrieves the outdoor temperature from the selected temperature sensor.
* Sends the outdoor temperature to the Stelpro Ki Z-Wave thermostat **(Model STZW402+ only)**.
* Updates the display automatically when the outdoor temperature changes.
### Notes:
* Target product reference: https://products.z-wavealliance.org/z-wave-product/ki-electronic-thermostat-for-smart-home-3/
* Do not use this blueprint for other thermostat models
* EXT temperature mode must be enabled from the thermostat advanced settings menu. Refer to manufacturer instructions:
* https://products.z-wavealliance.org/wp-content/uploads/products/50042/INS_STZW402_1215_EN.pdf
* Note that the first outdoor temperature sync on the thermostat display will occur once the outdoor temperature sensor changes its value for the first time after this automation is set up.


## Francais:
Ce blueprint effectue les actions suivantes:  

* Récupère la température extérieure depuis le capteur de température sélectionné.  
* Envoie la température extérieure au thermostat Stelpro Ki Z-Wave **(modèle STZW402+ uniquement)**.  
* Met à jour l'affichage automatiquement lorsque la température extérieure change.
### Notes: 
* Référence du produit ciblé: https://products.z-wavealliance.org/z-wave-product/ki-electronic-thermostat-for-smart-home-3/
* Ne pas utiliser ce blueprint pour d'autres modèles de thermostats.  
* Le mode température EXT doit être activé depuis le menu des paramètres avancés du thermostat. Consultez les instructions du fabricant :  
* https://products.z-wavealliance.org/wp-content/uploads/products/50042/INS_STZW402_1215_EN.pdf  
* Notez que la première synchronisation de la température extérieure sur l'affichage du thermostat aura lieu une fois que le capteur de température extérieure aura changé de valeur pour la première fois après la configuration de cette automatisation.

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.me/AlainRaymond564)

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https://github.com/alray31/STZW402/blob/main/StelproKi.yaml)

![image](https://github.com/user-attachments/assets/955ad5d2-f90a-4782-97a0-92e574a41671)

<p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/alray31/STZW402/blob/main/StelproKi.yaml">StelproKi.yaml</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://github.com/alray31">Alain Raymond</a> is licensed under <a href="https://creativecommons.org/licenses/by-nc/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Creative Commons Attribution-NonCommercial 4.0 International<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1" alt=""><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nc.svg?ref=chooser-v1" alt=""></a></p> 
