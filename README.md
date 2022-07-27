# Poryecto-inteligencia-artficial-vector-man-2
Algoritmo de inteligencia artificial algoritmo genético
Intrucciones para ejecucion
Se necesita la instalación de openai retro, se hace atraves de python 3 utilizando pip.
Deben crear la carpeta.
Clonen el repositorio de python usando la opcion de fork en github:https://github.com/ChristianUP18/Poryecto-inteligencia-artficial-vector-man-2/edit/main/README.md.
1. ```git clone https://github.com/ChristianUP18/Poryecto-inteligencia-artficial-vector-man-2/edit/main/README.md```
dentro del EXAMEN ejecutor lo siguiente
2. ```virtualenv -p python3 env```
3. ```source env/bin/activate```
4. ```pip3 install gym-retro```
5. Luego es necesario que importen el juego de vector man 2 a la base de datos gym. Recuerden que el juego es ilegal distribuirlo en linea asi que no se pueden subirlo  al entregable ya nos  banearan su repositorio.
6. Para impotar el juego creen una carpeta llamada roms y colocan ahi el archivo md con el juego luego ejecuten: ```python3 -m retro.import roms```
7. Esto indicara un mensaje de que el rom se ha importado a retro gym
8. Ahora deben ejecutar el codigo de ejemplo y probar los niveles en vectorman. Parte de su trabajo sera encontrar los niveles que deben utilizar para el entrenamiento.
9. Para ussarlo necesitaran Correctamente el codigo genetico son necesarias las siguientes importaciones:
import retro, import numpy as np, import cv2, import neat,import pickle, import gym y import random

