

Arduino + Servo-moteur + node.js + Johnny-five 
========================================================

Contrôlez un servo-moteur via l'interface web:


## Installation 

```
git clone git@github.com:manuel-CQE/Servomoteur.git
cd Servomoteur
npm install
```

Modules utilisés

* johnny-five
* express
* socket.io
* serialport




Connexion de l'Arduino via USB, chargez via l'API d'Arduino **Example > Firmdata > StandandFirmData**

## Execution de l'application

```
node app.js
```
L'application établie une connexion avec l'Arduino
Le Servo-moteur s'initialise


## Utilisation via votre navigateur : 

```
localhost:3000
```
L'application vous envoie une page web avec un curseur et affiche l'angle correspondant.
Vous pouvez utilser les fleches gauche et droite ou la souris.


# Branchement du Servo-moteur sur l'Arduino:

L'alimentation du servo-moteur sur +5V et GND de l'arduino, et le fil pilote sur le pin 9 (PWM)
![Arduino](https://raw.githubusercontent.com/manuel-CQE/Servomoteur/master/doc/Arduino-ServoMoteur.png)

## Démonstration :

[![ScreenShot](https://i.ytimg.com/vi/jSLlbobQq9Q/mqdefault.jpg)](https://www.youtube.com/watch?v=jSLlbobQq9Q&feature=youtu.be)