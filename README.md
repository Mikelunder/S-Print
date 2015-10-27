# S-Print
Prototipo de zapatilla inteligente usando sensores Thinking Things de Telefónica.


##El evento 
El proyecto S-Print se realizó durante el <a href="http://www.fundaciontelefonica.com/empleabilidad/hackathon-todos-incluidos/madrid/"> Hackathon 'Todos Incluidos' </a> (#HackathonMAD , #somoscapacesdetodo) celebrado entre los días 23 y 25 de octubre de 2015 en el espacio Fundación Telefónica de Madrid. Este evento fue organizado por Fundación Telefónica, Telefónica I+D y otros colaboradores.


##La idea
S-Print es una zapatilla inteligente que permite comprobar si la forma de pisar del usuario es la correcta, permitiendo así prevenir lesiones y aumentar el rendimiento deportivo. Además cuenta con una plataforma web que permite obtener un estudio personalizado de la evolución de la pisada completa durante sesiones de entrenamiento y un informe con otros parámetros estadísticos. 
<p align="center">
<img src=https://github.com/eArraez/S-Print/blob/master/photos/Zapatilla.jpg width="250" height="200"/> <img src=https://github.com/eArraez/S-Print/blob/master/photos/EvaluaPisada.jpeg width="250" height="200"/>
</p>


##El equipo
S-Print fue ideado y desarrollado por los miembros del Equipo Blanco:
- Miguel Herrero Grueso
- Sonia Martínez Martín
- Elena Arráez Álvarez
- Jesús Rodríguez-Quiñones Galindo


##Hardware
Se empleó un kit básico de sensores basados en la tecnología <a href="http://www.thinkingthings.telefonica.com">Thinking Things</a> de Telefónica:
- Módulo ambiente: sensor de luminiscencia (el sensor de presión no estaba disponible)
- Módulo notificador: LED RGB + Buzzer

<p align="center">
<img src=https://github.com/eArraez/S-Print/blob/master/photos/ThinkingThings.JPG width="250" height="200" /> <img src=https://github.com/eArraez/S-Print/blob/master/photos/TT_green.JPG width="250" height="200" />
</p>


##Software
La plataforma web se realizó con una plantilla Joombla. Para visualizar los datos de los sensores en tiempo real se empleó un panel de <a href="https://freeboard.io">freeboard</a> con distintos widgets para cada gráfico: sparkline, gauge y map.
<p align="center">
<img src=https://github.com/eArraez/S-Print/blob/master/photos/ej_entrenamiento1.png width="450" height="200" />
</p>
