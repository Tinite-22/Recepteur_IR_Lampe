# R-cepteur_IR_Lampe
Ce projet consiste à créer un interrupteur sans fil. Il permet de contrôler un appareil électrique (comme une lampe, un ventilateur ou un moteur) à distance à l'aide d'une télécommande infrarouge standard (comme celle d'une TV ou d'un kit Arduino).
Le microcontrôleur (Arduino) décode les signaux infrarouges reçus. Si le signal correspond au code "ON", il active un relais. Si le signal correspond au code "OFF", il désactive le relais.
Liste des Composants
Voici le matériel nécessaire pour réaliser ce montage :
•	Carte Arduino Uno
•	Module Récepteur Infrarouge (généralement le modèle VS1838B ou similaire).
•	Télécommande Infrarouge (n'importe quelle télécommande standard fonctionne).
•	Module Relais 5V (1 canal ou plus).
•	Câbles de connexion (Jumpers Mâle-Femelle et Mâle-Mâle).
•	Breadboard (platine d'essai) pour faciliter les connexions.
•	L'appareil à contrôler ici une lampe de 220v
Connexions
Broche Capteur	Arduino	Broche Relais	Arduino
VCC	5V	VCC (ou DC+)	5V
GND	GND	GND (ou DC-)	GND
OUT	D8	IN	D7
