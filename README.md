# 🛡️ Cyber Defense SOC Platform

## Real-Time Cyber Threat Monitoring & Analysis Platform

A cybersecurity monitoring platform designed to collect, analyze, and visualize real-time cyber threats using honeypot technology.

This project focuses on understanding attacker behavior, improving threat visibility, and providing security insights through a modern dashboard.

---

## 🚀 Overview

The Cyber Defense SOC Platform acts as a lightweight Security Operations Center (SOC) solution that monitors suspicious activities, analyzes attack patterns, and presents security events in real time.

The system integrates a honeypot environment to safely capture attacker interactions and provides an interface for security monitoring and analysis.

---

## ✨ Features

### 🔴 Real-Time Threat Monitoring

* Live attack event streaming
* Real-time security updates
* Attack activity tracking

### 🐝 Honeypot Integration

* Cowrie SSH honeypot integration
* Captures attacker behavior
* Records login attempts and commands

### 📊 Security Dashboard

* Threat statistics
* Attack trends visualization
* Security event analytics

### 🔍 Threat Analysis

* IP-based analysis
* Attack pattern detection
* Suspicious activity identification

### 🎬 Session Analysis

* Attacker session tracking
* Command history analysis
* Behavioral observation

---

## 🏗️ System Architecture

```
Attacker
    |
    ↓
Cowrie Honeypot
    |
    ↓
Log Processing Engine
    |
    ↓
FastAPI Backend
    |
    ↓
MongoDB Database
    |
    ↓
WebSocket Communication
    |
    ↓
Flutter Mobile Application
```

---

## 🛠️ Technology Stack

### Frontend

* Flutter
* Dart
* Riverpod

### Backend

* Python
* FastAPI
* WebSockets

### Database

* MongoDB
* Redis

### Cybersecurity

* Cowrie Honeypot
* Threat Analysis

### Development Tools

* Docker
* Git
* VS Code

---

## 📁 Project Structure

```
cyber-defense-soc-platform/

├── mobile-app/
├── backend/
├── honeypot/
├── database/
├── docs/
├── scripts/
└── tests/
```

---

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/rohithreddy-cyber/cyber-defense-soc-platform.git

cd cyber-defense-soc-platform
```

### Backend Setup

```bash
cd backend

pip install -r requirements.txt

python main.py
```

### Mobile Application

```bash
cd mobile-app

flutter pub get

flutter run
```

---

## 🔐 Security Approach

The platform follows security best practices:

* Secure authentication
* API protection
* Environment-based configuration
* Isolated honeypot deployment
* Safe threat analysis environment

---

## 🎯 Learning Objectives

This project demonstrates practical knowledge in:

* Cybersecurity monitoring
* SOC operations
* Threat intelligence concepts
* Backend development
* Real-time systems
* Mobile application development

---

## 🔮 Future Enhancements

* AI-based threat detection
* Advanced threat intelligence integration
* Automated alerting system
* Cloud deployment
* Multi-honeypot support

---

## 👨‍💻 Author

**Rohith Reddy**

Cybersecurity | Software Development | Learning by Building

---

## 📜 License

This project is developed for educational and research purposes.
