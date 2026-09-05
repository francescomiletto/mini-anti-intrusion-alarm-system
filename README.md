# Arduino Mini Anti-Intrusion Alarm & RFID Access System

A feature-rich miniature security system combining motion detection, electronic locking, and RFID tag authentication, powered by an Arduino microcontroller.

---

## 🇬🇧 English Description

### Overview
This project is an advanced miniature anti-intrusion security system. It integrates motion detection with an electronic lock and RFID access control, providing real-time visual and acoustic feedback through an LCD screen, LEDs, and a buzzer.

### Key Features & Hardware Components
* **Microcontroller:** Powered by an Arduino board.
* **Motion Detection:** PIR sensor used to detect unauthorized movements when the alarm is active.
* **Electronic Lock:** Servo motor acting as an automated locking mechanism.
* **Access Control:** RFID sensor (RC522 module, powered at 3.3V from the Arduino board) for secure arming/disarming.
* **User Interface:** I2C LCD display providing real-time system status and user instructions.
* **Alert System:** Red LED and Buzzer activated when an intrusion is detected.
* **Status Indicators:** Green LED indicating the system activation status and guiding the tag-change procedure.
* **Configuration:** Dedicated Push Button (in a pull-down configuration, 0 = inactive) allowing administrators to register new RFID tags **only** when the alarm is disarmed, with step-by-step instructions displayed on the LCD.

---

## 🇮🇹 Descrizione in Italiano

### Panoramica
Un sistema di allarme anti-intrusione in miniatura avanzato, che unisce il rilevamento di movimento, una serratura elettronica e il controllo degli accessi tramite RFID, gestito interamente da Arduino con interfaccia utente su display LCD, LED e buzzer.

### Caratteristiche Principali e Componenti
* **Unità di Controllo:** Gestita tramite scheda Arduino.
* **Rilevamento Movimento:** Sensore PIR per l'individuazione di movimenti sospetti a sistema inserito.
* **Serratura Elettronica:** Servomotore impiegato come attuatore per il blocco/sblocco.
* **Controllo Accessi:** Sensore RFID con modulo RC522 (alimentato a 3.3V da Arduino) per l'autenticazione tramite tag.
* **Interfaccia Utente:** Display LCD con connessione I2C per la visualizzazione di tutte le informazioni utili.
* **Sistema di Allarme:** Led Rosso e Buzzer attivi in caso di allarme in corso.
* **Indicatori di Stato:** Led Verde utilizzato sia per indicare lo stato di attivazione dell'allarme sia come riscontro visivo (insieme al buzzer) durante la procedura di cambio tag.
* **Gestione Tag (Configurazione):** Pulsante con configurazione in pull-down (0 = non attivo) per avviare la procedura di registrazione di un nuovo tag **SOLO** se l'allarme risulta disattivato, con istruzioni guidate mostrate sul display LCD.

---

## 🔌 Media & Resources / Materiale e Documentazione
- **Schema Elettrico / Schematic:** <img width="1162" height="588" alt="Schema Elettrico" src="https://github.com/user-attachments/assets/f50f1bea-a5bf-4246-9ff7-2d946df086ff" />
- **Video Dimostrativo / Demo Video:** [Youtube Link](https://youtu.be/AuxsWHAKap0)
