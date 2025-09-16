# -Automatic-River-Cleaner-
Where IoT Meets Sustainability (🌊♻️ Automatic River Cleaner )

An IoT-powered autonomous river cleaning system designed to tackle water pollution by collecting floating waste. The system uses ESP32, GPS, ultrasonic sensors, and a smart waste collection belt, with Telegram bot integration for real-time monitoring and control.

🚀 Features

  Autonomous Navigation
  
  GPS + Compass to set target locations and return home.
  
  Ultrasonic sensors for obstacle detection and avoidance.
  
  Smart Waste Collection
  
  Belt-driven system to capture floating debris.
  
  Automatic bin monitoring with ultrasonic sensor → stops when full.
  
  IoT + Remote Monitoring
  
  ESP32 with Wi-Fi connectivity.
  
  Telegram bot integration for:
  
  Live boat location (Google Maps link).
  
  Status reports (bin level, navigation mode, GPS signal).
  
  Remote commands: /stop, /resume, /location, /set_target, /home, /status.
  
  Failsafe Mechanisms
  
  Emergency stop via Telegram.
  
  Return-to-home when bin is full.
  
  LED indicators for alerts.

🛠️ Hardware Components

  ESP32 microcontroller
  
  GPS Module (NEO-6M)
  
  HMC5883L Compass
  
  Ultrasonic Sensors (front, left, right, bin level)
  
  Motor Driver (L298N) for propulsion and belt control
  
  DC Motors (propulsion + waste belt)
  
  Power Supply (battery)
  
  Wi-Fi connection for Telegram bot

⚡ Software Stack

  Arduino Framework (C++)
  
  UniversalTelegramBot library for ESP32
  
  TinyGPS++ for GPS data
  
  Adafruit HMC5883L for compass integration
  
  Custom navigation & obstacle avoidance algorithms

📋 Commands (Telegram Bot)

  /stop → Emergency stop
  
  /resume → Resume navigation
  
  /location → Send current GPS coordinates + map link
  
  /set_target <lat> <lon> → Set target location
  
  /home → Show saved home location
  
  /status → Full boat status report

🌱 Benefits

  Removes floating plastic and waste from rivers.
  
  Protects aquatic ecosystems.
  
  Promotes sustainable, tech-driven environmental solutions.
  
  Scalable for urban and rural deployment.

📸 Project Poster

🔮 Future Improvements

  AI-based waste detection (camera + ML).
  
  Solar-powered charging for longer operation.

Cloud dashboard for data logging and analytics.

Swarm coordination of multiple cleaning boats.

📢 Acknowledgments

Developed as part of a sustainability & IoT initiative to apply engineering for environmental protection.
