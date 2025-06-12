# iot-enviornment-monitor
This project uses an ESP8266 and DHT11 to send temperature and humidity data to an app using MQTT. The app was made using MIT App Inventor and can control a light remotely.

## Layers
- Device Layer: DHT11 + ESP8266
- Edge Layer: ESP8266 formats data
- Network Layer: Wi-Fi + MQTT (Mosquitto broker)
- Platform Layer: test.mosquitto.org
- Application Layer: MIT App with UrsPahoMqttClient

## Screenshots
MQ.png

block programming.png

mymqtt.aia

sensor-data-icon-line-illustration-vector.jpg

tempfileForShare_20250428-115606.jpg

## Note
Tried connecting to Mosquitto, but MQTT failed due to unknown network issues. App and code are fully built.
