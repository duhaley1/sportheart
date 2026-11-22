# Compatibilité et portée des tests

2026-11-22

| Équipement | Connexion | Vérification |
|---|---|---|
| iGPSPORT iGS630S | BLE | Testé : iGS630S |
| Garmin Edge 530 | Connect IQ + iPhone | Edge 530 : connexion réussie selon un utilisateur. Firmware, usage prolongé écran verrouillé et export FIT restent à vérifier. |
| Autre équipement BLE | BLE | Chaque autre modèle doit être testé. Le support BLE ne prouve pas une compatibilité vérifiée. |

La fermeture forcée, le redémarrage, le verrouillage hors du poignet et la mise en veille de l’écran sont des états différents. Les essais sur iGS630S ont confirmé la reconnexion après redémarrage de l’appareil dans les deux modes et les mises à jour en arrière-plan en mode iPhone. Chaque autre modèle doit être testé séparément.

## Garmin Edge 530

Edge 530 utilise un champ Connect IQ. Ne jumelez pas SportHeart dans la liste des capteurs cardiaques.

1. Associez le compteur dans Garmin Connect, puis choisissez-le ici.

2. Installez SportHeart et ajoutez son champ à un écran de cyclisme.

3. Choisissez le relais téléphone, démarrez la mesure sur la montre, puis activez le partage ici.

Un accusé de réception ne confirme pas l’affichage. Vérifiez l’écran du compteur.

Ce champ ne remplace pas un capteur Garmin natif et ne garantit pas le calcul de charge d’entraînement.

## iGPSPORT iGS630S

iGS630S : Paramètres → Capteurs → Ajouter un capteur → Fréquence cardiaque.

Gardez l'application iPhone ouverte pour le couplage initial en mode iPhone. Les deux modes utilisent des émetteurs différents et peuvent nécessiter des entrées de capteur enregistrées distinctes.

Lors des essais sur iGS630S, une liaison simultanée entre téléphone et appareil empêchait parfois la réception des données cardiaques malgré un capteur connecté. Déconnecter cette liaison, supprimer l’ancien capteur puis le jumeler à nouveau a rétabli les données. La cause n’est pas confirmée ; les autres modèles peuvent se comporter différemment.

En mode iPhone, déconnectez uniquement le lien application compagnon de l'équipement. Laissez le Bluetooth de l'iPhone et la connexion de la montre activés.

App Store: https://apps.apple.com/app/id6827442593

Connect IQ: https://apps.garmin.com/zh-CN/apps/0b750e18-5b36-4cc7-9470-b8f996dfa94a

Support: support-fr.html
