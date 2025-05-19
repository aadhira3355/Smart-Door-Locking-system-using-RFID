# 🔐 Smart Door Locking System using RFID and Blynk (ESP8266)

This project implements a **smart door locking system** using an **RFID scanner**, **ESP8266 Wi-Fi module**, and **Blynk mobile app** for remote unlocking and access monitoring.

---

## 🚀 Features

- Unlock the door using a **registered RFID tag**.
- **Remote unlock** using the Blynk mobile app.
- **Live access logs** via Blynk (e.g., who accessed the door and when).
- **Buzzer alert** for unauthorized card scans.
- **LED indication** for access granted.
- NTP-based **real-time clock** for accurate timestamps.

---

## 🧰 Hardware Used

| Component         | Description                       |
|------------------|-----------------------------------|
| NodeMCU ESP8266  | Wi-Fi-enabled microcontroller     |
| RC522 RFID Reader| For scanning RFID cards           |
| RFID Card/Tag    | Used for authentication           |
| Relay Module     | To control a solenoid lock        |
| Servo / Solenoid | Door locking mechanism            |
| Buzzer           | Alerts on unauthorized access     |
| LED              | Status indicator                  |
| Jumper Wires     | Connections                       |

---

## 📲 Mobile Integration (Blynk)

### Virtual Pins Used:

| Virtual Pin | Purpose                |
|-------------|------------------------|
| V0          | Access log messages    |
| V1          | Switch for remote unlock |
