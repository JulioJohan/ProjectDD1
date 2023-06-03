# AmbiSense
<!-- Subtitulo -->
## Objetivo del proyecto
El objetivo principal del proyecto de Sistema de Monitoreo Ambiental es diseñar y desarrollar un sistema que permita a los usuarios monitorear y controlar los diferentes parámetros ambientales en la oficina de manera eficiente y conveniente. El proyecto busca crear un entorno más saludable y confortable para los ocupantes, al tiempo que promueve la eficiencia energética y la sostenibilidad.

## Integrantes
- David Enrique Lopez Juarez
- Julio Johan Jaramillo Mejia
- Alejandro Rafael Guerrero Lozano
- Itzel Juliza Guerrero Rodriguez

<!--Componentes electricos-->
## Hardware
| Num.| Componente | Descripción | Imagen | Costo | Cantidad |
|-----|------------|-------------|--------|-------|----------|
|  1  | Sensor de temperatura y de humedad (ambos) (DHT11) |Mide la temperatura del entorno	|![imagen](https://cdn.shopify.com/s/files/1/1040/8806/products/photo_IC-20010_DHT11_DigitalTemperatureHumiditySensor_DHT11_01_700x700.png?v=1627344523)|  $140 | 2
|  2  | Sensor de gas	(MQ-2) |Detecta la presencia de gases		|![imagen](https://uelectronics.com/wp-content/uploads/AR0221_MQ5-2-2.jpg)|  $140 | 2
|  3  | Sensor de movimiento	(PIR) | Detecta el movimiento en un área			|![imagen](https://epyelectronica.com/wp-content/uploads/2020/09/Sensor-de-Movimiento-PIR-HC-SR501.png)|  $100 | 2
|  4  | Sensor de sonido	(KY-038)| Detecta el nivel de sonido en el entorno	|![imagen](https://aelectronics.com.mx/metepec/14-thickbox_default/sensor-de-sonido-modulo.jpg)|  $100 | 2



## Tabla de Software utilizado
| Id | Software | Version | Tipo |
|----|----------|---------|------|
| SF01 | Node- Red | v3.0.2 |  Software    |
| SF02 | MQTT | v3.1.0 |   Libreria  |
| SF03 | Python | v3.9.5 |   Lenguaje de programación  |
| SF04 | Tinkercad | Actual |   Software  |
| SF05 | Fritzing | v0.9.3 |   Software  |


## Tabla de historias de usuario
| Id | Historia de usuario | Prioridad | Estimación | Como probarlo | Responsable |
|----|---------------------|-----------|------------|---------------|-------------|
|HU001| Como usuario, quiero poder monitorear la temperatura ambiente del espacio de trabajo de mis empleados en tiempo real para ajustar la climatización de manera eficiente y asegurar el confort de mis empleados| Debe | 4 | El usuario entra en LVGL dentro de la aplicación para poder navegar y monitorer la temperatura |  Julio Johan Jaramillo Mejia |
| HU002   |  Como usuario, quiero poder supervisar la humedad relativa del aire del espacio de trabajo de mis empleados para controlar y evitar problemas de humedad, como el moho y la condensación excesiva.  |    Debe   |   4   | El usuario entra en LVGL dentro de la aplicación para poder navegar y monitorer la humedad |  Itzel Juliza Guerrero Rodriguez  |
| HU003 | Como usuario, quiero ser alertado inmediatamente si se detecta una fuga de gas o una concentración peligrosa del espacio de trabajo, para tomar medidas de seguridad y evitar accidentes.  |  Debe |   4   |  El usuario entra en LVGL dentro de la aplicación para poder navegar y checar si hay una fuga | David Enrique Lopez Juarez |
| HU004 | Como usuario, quiero recibir alertas cuando se detecte movimiento en áreas específicas  del espacio de trabajo  mientras estoy ausente, para tomar medidas de seguridad y precaución. |  Debe |   4   |  El usuario entra en LVGL dentro de la aplicación para poder navegar y checar si hay un excesivo de movimiento |  Alejandro Rafael Guerrero Lozano |
| HU005 | Como usuario, quiero supervisar los niveles de ruido  del espacio de trabajo de mis empleados para evaluar el ambiente sonoro y tomar acciones para reducir el ruido excesivo o identificar situaciones inusuales. Ademas de tener un control con los empleados|  Debe |   4   |  El usuario entra en LVGL dentro de la aplicación para poder navegar y checar si existe un ruedo excesivo |  David Enrique Lopez Juarez |

## Prototipo en dibujo
![Carcasa del dispositivo para monitorear](https://github.com/JulioJohan/Social_Hub_IOT/blob/main/59b66046-de32-4683-b355-f47a140f9e83.jpeg)
![Carcasa del dispositivo para monitorear medidas](https://github.com/JulioJohan/Social_Hub_IOT/blob/main/324cf8b0-4d27-4943-ab37-0e067d3ed931.jpeg)
![Carcasa del dispositivo del smarwatch ](https://github.com/JulioJohan/Social_Hub_IOT/blob/main/d1cdfbf2-3c57-4323-a2b8-95e6568c3d88.jpeg)

## Prototipo en Fritzing 
![image](https://github.com/JulioJohan/Social_Hub_IOT/assets/92689016/83f0b4f8-b656-4159-823b-e841490cf50c)
Archivo para importa a Fritzing
https://drive.google.com/file/d/1hTj0Yit1YV8chYnKZ-L4cELiSmPzCCmE/view?usp=sharing
## Placa PCB
![image](https://github.com/JulioJohan/Social_Hub_IOT/assets/92689016/f1482343-17b9-444a-ac60-fee20b4c01d9)
![image](https://github.com/JulioJohan/Social_Hub_IOT/assets/92689016/5de45c54-2eb1-4dfe-a9df-51f6a97b9d83)
![image](https://github.com/JulioJohan/Social_Hub_IOT/assets/92689016/a8f1ee7b-cd9f-4f3d-9161-c0d63a9c7184)
Archivo para importa a Fritzing
https://drive.google.com/file/d/1hTj0Yit1YV8chYnKZ-L4cELiSmPzCCmE/view?usp=sharing
## Prototipo en 3D

![Carcasa del dispositivo para monitorear 3D](https://github.com/JulioJohan/Social_Hub_IOT/blob/main/c4a88b76-bfaf-43d6-9086-7c03bc590762.jpeg)
![Carcasa del dispositivo para smarwatch 3D](https://github.com/JulioJohan/Social_Hub_IOT/blob/main/62b0dfc3-ee43-4020-9fa4-9f2033622546.jpeg)

Archivos para importar en tinkercard
https://drive.google.com/drive/folders/17Y6I6Qh2MGuPxudXHm-QEi41wmYJhm28?usp=sharing
