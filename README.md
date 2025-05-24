# Smart Dust Bin 🗑️

A smart IoT-based dustbin that monitors fill levels, temperature, and humidity in real-time, sending alerts when the bin is nearly full.

## 💡 Features
- Real-time fill-level detection using ultrasonic sensor
- Environmental monitoring with DHT11 sensor (temperature and humidity)
- Web dashboard for live monitoring
- Alerts on reaching 80%+ fill level
- Built using ESP32, Node.js, MQTT, WebSocket, HTML/CSS/JS

## 🖼️ System Images

### Ultrasonic Sensor
![Ultrasonic Sensor](images/ultrasonic_sensor.jpg)  
📖 Refer: **Figure 1.1** in the project report

### Temperature and Humidity Sensor
![DHT Sensor](images/dht_sensor.jpg)  
📖 Refer: **Figure 1.2** in the project report

### System Architecture
![Architecture](images/architecture.png)  
📖 Refer: **Figure 3.1** in the project report

## 🛠️ Tech Stack
- **Hardware**: ESP32 BharathPi, HC-SR04, DHT11/DHT22
- **Backend**: Node.js + MQTT + WebSocket
- **Frontend**: HTML, CSS, JavaScript
- **Visualization**: JustGage JS library

## 🚀 How It Works
1. ESP32 collects sensor data.
2. Data sent to MQTT broker.
3. Node.js server receives and broadcasts via WebSocket.
4. Dashboard updates in real-time with alerts.

## 📂 Project Files
- `index.html` – Frontend dashboard UI
- `server.js` – Node.js server with MQTT & WebSocket handling

## 📈 Results
- Real-time readings display on the web page
- Alerts triggered when fill level exceeds 80%
- Efficient and scalable architecture for smart cities

## 🔮 Future Scope
- Add gas sensors for hazardous gas detection
- Mobile app for remote notifications
- Use solar power for deployment

## 👥 Team
- Abhishek (1CD22CS004)
- Khazi Afifa Fathima (1CD22CS065)
- N S Sai Vyshnavi (1CD22CS088)
- Veeresha (1CD22IS178)
- Prajwal M (1CD22CS103)
- Rahul M R (1CD22IS136)
- Karthik Naik (1CD23CS404)
- Tarun S V (1CD22CS166)


> 🔧 Guided by Mr. Tushar Das, SIC-IoT Trainer
