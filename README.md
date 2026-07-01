# STM32WL-LoRa
Stage d'été 2025 - Implémentation d'une chaîne LoRa complète, du VNA au cloud HiveMQ

Ce dépôt contient l'ensemble des travaux réalisés lors du stage d'été.
Le projet propose une approche "bottom-up" de l'écosystème LoRa, de l'antenne jusqu'au dashboard cloud.

## Architecture du Projet
* **Phase 1 & 2 :** Caractérisation RF (VNA 433/868 MHz) et analyse spectrale du chirp LoRa.
* **Phase 3 :** Firmware sur STM32WLEX (Driver SX1262 interne via SPI, gestion des IRQ).
* **Phase 4 :** Transmission des payloads vers un Network Server et visualisation sur HiveMQ.

## Matériel Utilisé
* SoC : STM32WLEX (Cortex-M4 + Cortex-M0+) avec transceiver SX1262 interne.
* Instrumentation : VNA, Analyseur de spectre.
* Cloud : HiveMQ Cloud (MQTT).

## Livrables
- [ ] Rapport de caractérisation RF (S11, SWR)
- [ ] Rapport d'analyse du spectre (RSSI, SNR, Sensibilité)
- [ ] Code C fonctionnel avec ST HAL
- [ ] Dashboard de visualisation temps réel
