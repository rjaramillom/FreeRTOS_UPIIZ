# FreeRTOS_UPIIZ
El repositorio contiene códigos y prácticas de clases 
## Arduino IDE
- Descargar e instalar el software Arduino IDE.
- Instalar libería ESP32. Archivo -> Preferencias -> URL: https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
- Herramientas -> Administrador de tarjetas -> buscar ESP32 e installar. 
# Actividades
## Actividad 00
Genere una carpeta con el nombre Actividad 00. Ahí deberá integrar los siguientes códigos realizados en clase: 
- Conexión a Wi-Fi e interacción con base de datos en Firebase. (Publicar fecha y nivel entregado por sensor ultrasonico)
- Habilitación de bluetooth al presionar un botón y deshabilitar el mismo a través de comando por bluetooth y/o al presionar nuevamente el botón. 
- Interacción con bot de Telegram. 

## Actividad 01
- Probar el código dentro de la carpeta Actividad 01.
- Después de la sección del loop principal, deberá agregregar un comentario donde indique lo que realiza el código.  

Genere un código que contemple lo siguiente: 
- Dos tareas que permitan controlar el toggle de un GPIO. (Solo un GPIO por tarea)
- El toggle de una tarea deberá ser del doble de la frecuencia de la otra tarea. 
- Modifique la prioridad de las tareas, primero establezca la prioridad igual, después modifique la prioridad e invierta esta prioridad con la finalidad de observar el comportamiento a través de un osciloscopio. 
- Después del loop principal deberá agregar una sección de comentarios donde realizará un análisis del comportamiento. Si desea agregar imagenes deberá integrarlas en el repositorio. 

## Actividad 02

- Probar el código dentro de la carpeta Actividad 02.
- Después de la sección del loop principal, deberá agregregar un comentario donde indique lo que realiza el código.  

Genere un código que contemple lo siguiente: 
- Usando FreeRTOS, cree dos tareas separadas. 
- La primer tarea recibe un número entero a través de UART (del Serial Monitor) y lo asigna a una variable. 
- La otra tarea hace parpadear el LED integrado a una velocidad especificada por ese número entero. 

## Actividad 03

- Probar el código dentro de la carpeta Actividad 03 que corresponde a la solución del ejercicio planteado en clase.
- Después de la sección del loop principal, deberá agregregar un comentario donde indique lo que realiza el código.  

Genere un código que contemple lo siguiente: 
- Integre el código de su autoría que solucione el mismo problema. 

## Actividad 04
- Analizar el código dentro de la carpeta y determinar bajo que condicones se llena el queue. Pruebe modificando tienpo, longitud del mensaje, modificando longitud de la variable global, etc. 
- Se recomienda tener respaldo del código original para tener un punto de comparación.

## Actividad 05 
- Probar código dentro de la carpeta Actividad 05 y en la parte inferior del código agregar una sección de comentarios donde deberá incluir el análisis del código y el resultado obtenido en la consola.
