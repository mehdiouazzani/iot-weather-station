# IoT Weather Station — ESP32 + MQTT

Simulation d'une station météo IoT sur ESP32.

## Description
- Capteur DHT22 (température + humidité)
- Publication des données via MQTT (broker.hivemq.com)
- Format JSON : `{"temperature": 24.0, "humidite": 40.0}`
- Topic MQTT : `mehdi/meteo`

## Stack technique
- ESP32 (Arduino framework)
- Protocole MQTT (PubSubClient)
- Simulateur Wokwi

## Simulation
[Voir le projet sur Wokwi](https://wokwi.com/projects/477523770561207297)
