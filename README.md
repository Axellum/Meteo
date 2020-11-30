# Station météo Home assistant - Météo France, IOT Link -

MAJ 17/11/2020: La version 'final', plus simple, en préparation ici: https://github.com/Axellum/Ecran-meteo-Nextion-par-ESPHome

Attention: L'API Météo France a évolué, du coup une partie du code sur ce git est obsolette.
Préview de la version simplifié:

![V simple](/20201117_112501.png)

MAJ 15/04/2020: Suppresion de Darks sky et Pi hole (bientot arreté). Passage sur ESP32, fini les problemes de buffer TCP! Du coup je vais pouvoir compléter un peu le projet. Légére modifications graphique sur la 1er page (réorganisation et complément d infos, recallage). L'arriver de quelques sonoffs et l utilisation de RFlink ESP vas me permetre de tester les commandes domatiques, et de récupérer les sondes météos des station météo du commerce ;).

Affichage météo avec interaction sur les objets Home assistant:

[![ESPHome Logo](http://axellum.free.fr/ecran.png)](https://www.facebook.com/pg/Station-Météo-France-et-commandes-diverses-sur-écran-Nextion-102829114681432/)

    Matériel:
        Écran Nextion NX4832T035 (3.5p) à 30€
        Un ESP32 (actuellement sur ESP8266 mais les ESP32 devrait être mieux adapté) 5 - 7€
        Un serveur avec Home assistant (Sur une VM débian installé dans une Freebox dans mon cas)

L’écran permettra d'afficher le temps sur 3 jours (par météo France), détection des averses sur 1h00, icône des risques d'orages / gel / neige, l'affichage des alerte Météo France ex..
D'autres pages afficheront les données du serveur et PC, avec des jauges.

Présentation Youtube:
https://youtu.be/dMXXnOEiKkE 
