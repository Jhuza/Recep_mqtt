# Monitor de sensores

Recibe una lectura MQTT y muestra sus campos como métricas.

- Entrada: Broker, puerto, tópico e identificador del cliente.
- Resultado: Último mensaje recibido, métricas y vista JSON.
- Tecnología: Paho MQTT · JSON

## Uso

Configura la conexión en el panel lateral y pulsa Obtener Datos del Sensor mientras el emisor publica en ese tópico.

## Límites

Espera hasta cinco segundos por lectura. Depende de un emisor activo y de una conexión disponible.

## Evidencia de ejecución

La ficha describe el funcionamiento del código. Una ejecución del modelo o una conexión a un dispositivo debe documentarse con su entrada, resultado observado y captura real; no se presentan resultados simulados como evidencia académica.

[Demo](https://recepmqtt-yjrvz6zzhbblxzpf7uctim.streamlit.app/) · [Código](https://github.com/Jhuza/Recep_mqtt)
