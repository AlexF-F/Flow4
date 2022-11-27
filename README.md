# <p align="center"><img src="https://i.imgur.com/A6bWGFl.gif"/></p>

<h1 align="center">Cuarto Flow </h1>

<h4> Este repositorio contiene el sprimer ejercicio en Node Red,El flow 4 representa el cuarto ejercicio a realizar con NodeRed. Este flow consiste en un tablero que presente la información de temperatura y humedad locales. Este flow recibe la información por MQTT con un broker local. </h4> 


### CONTENIDO
#### Material necesario
- Node.js Usar la versión LTS v16x e instalar los build tools.
- Node-Red
- Nodos Dashboard
-Mosquitto
#### Instrucciones
1.Instalación de NodeJS. Se recomienda tener instalado NodeJS en alguna versión LTS. Al momento de creación de este documento, se usó la versión 16.17.0LTS. Esta instalación debe incluir las Build-Tools para hacer uso de NPM
2.Instalación de NodeRed. La instalación se realiza por NPM. Al momento de la creación de este contenido, se usó la versión 3.0.2
3.Instalar los nodos node-red-dashboard. Para ello, dirigete a la opcion "Manage Palet" de NodeRed y en la pestaña Install busca node-red-dashboard. Finalmente haz clic en instalar.
4.Instalación de Broker local Mosquitto MQTT.
#### Instrucciones de operacion
- Para observar el resutlado de este flow, abre un navegador y dirígete a localhost:1880/ui
- Enviar por MQTT un mensaje que contenga un JSON con las variables ID, temp y hum

#### Resultados y conclusiones 

A continuación puede ver el tablero resultante.<a href="https://www.mozilla.org/es-ES/">tablero</a>.
A continuación puedes ver los nodos del flow.<a href="https://www.mozilla.org/es-ES/">tablero</a>.
#### Video representativo
Puedes encontrar el video explicativo en el siguiente enlace: <a href="https://www.mozilla.org/es-ES/">Video</a>.
