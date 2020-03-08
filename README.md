# Station météo Home assistant - Météo France, Darksky, IOT Link -

------- En construction -------------------------

Affichage météo avec interaction sur les objets Home assistant:

    Matériel:
        Écran Nextion NX4832T035 (3.5p) à 30€
        Un ESP32 (actuellement sur ESP8266 mais les ESP32 devrait être mieux adapté) 5 - 7€
        Un serveur avec Home assistant (Sur une VM débian installé dans une Freebox dans mon cas)

L’écran permettra d'afficher le temps sur 3 jours (météo France et Darksky), l'arrivé de la prochaine averse, icône des risques d'orages / gel / neige, l'affichage des alerte Météo France ex.. Une deuxième page affichera les donné du serveur et PC, avec des jauges pour les données matériel du serveur, les donné UP et DOWL de la Freebox, nombre de client Pi Hole et trois boutons aux choix pour déclencher des événements sur Hass (avec IOT Link).
