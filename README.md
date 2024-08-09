# Curso de IOT


## Contenido

### Evaluacion 1
La intención de la práctica es realizar una integración entre sensores que capturan datos y sean enviados a un servicio en la nube. Para simplificar la actividad, se optó por generar un script de python el cual va a simular la generación de datos y será el encargado de enviar la
información a la Thingspeak para después proceder a generar gráficas con los datos registrados.

Instrucciones:

```python
python ./evaluacion-1/main.py
```

### Actividad 6 
Generacion de  una simulación de datos de temperatura y los procesa para determinar temperaturas anómalas en tiempo real.

Instrucciones:

- Se necesitan correr ambos scripts en simultaneo

```python
python ./actividad-6/01_real_time_temp_processing.py
```

```python
python ./actividad-6/02_data_pull_snippet.py
```

### Actividad 8
Simulación de los diferentes conceptos de edge, roof, fog, y cloud computing


Instrucciones:

```python
python ./actividad-8/computing_levels.py
```

### Evaluacion 3
Practica de MQTT, este proyecto cuenta con un publisher y un subscriber para intercambiar información usando un servidor publico de mosquitto.

Instrucciones:

Se necesita correr el publisher y el susbcriber simultaneamente para poder que exista una comunicación en tiempo real

```python
python ./evaluacion-2/publisher_mqtt.py
```


```python
python ./evaluacion-2/subscriber_mqtt.py
```