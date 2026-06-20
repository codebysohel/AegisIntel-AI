# 🛡️ AegisIntel-AI

**Next-Generation AI-Powered OSINT Platform**

[![Python 3.10+](https://img.shields.io/badge/Python-3.10%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.104%2B-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![React 18+](https://img.shields.io/badge/React-18%2B-61DAFB?logo=react&logoColor=white)](https://react.dev/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Docker Ready](https://img.shields.io/badge/Docker-Ready-2496ED?logo=docker&logoColor=white)](https://www.docker.com/)

---

## 📋 Overview

AegisIntel-AI is a modern, open-source OSINT (Open Source Intelligence) platform that combines:

✅ **Systematic Reconnaissance** - 15+ automated modules
✅ **AI-Powered Analysis** - LLM-based threat insights
✅ **Interactive Dashboards** - Real-time visualization
✅ **Risk Scoring** - Composite threat assessment
✅ **Professional Reports** - PDF/JSON/HTML exports
✅ **Scalable Architecture** - FastAPI + React + PostgreSQL

---

## 🎯 Key Features

### Reconnaissance Modules
- **DNS Analysis** - Subdomain enumeration, zone transfers, record analysis
- **WHOIS Intelligence** - Domain registration, IP geolocation, ASN lookup
- **Certificate Analysis** - Chain analysis, CT log scanning, expiry tracking
- **Technology Detection** - Framework identification, WAF detection, software fingerprinting
- **Email OSINT** - Breach checking, platform presence, account intelligence
- **Social Media Enumeration** - Username search, profile discovery
- **Threat Intelligence** - DNSBL, reputation checking, blocklist hits
- **Metadata Extraction** - EXIF data, PDF/Office metadata
- **Port Scanning** - TCP/UDP service discovery
- **HTTP Analysis** - Header analysis, security policy detection

### AI Capabilities
- 🤖 **Threat Analysis** - LLM-powered finding interpretation
- 📊 **Risk Prediction** - ML-based threat scoring (configurable)
- 🔮 **Investigation Guidance** - AI-generated next steps
- 📈 **Anomaly Detection** - Isolation Forest-based outlier detection
- 🎯 **Smart Recommendations** - BERT-based investigation playbooks

### Enterprise Features
- 📊 **Interactive Dashboards** - Real-time scan monitoring
- 📁 **Scan History** - SQLite-backed persistence
- 📈 **Analytics** - Success rates, trending findings
- 🔐 **Security** - API key management, rate limiting, CORS protection
- 🚀 **Scalability** - Async execution, connection pooling, caching
- 🐳 **Containerization** - Docker + Docker Compose ready
- 📦 **Kubernetes** - Production-grade K8s manifests included

---

## ⚡ Quick Start

### Prerequisites
- Python 3.10+
- Node.js 18+
- Docker & Docker Compose (optional)
- PostgreSQL 13+ (optional, SQLite default)

### Installation (Docker)

```bash
# Clone repository
git clone https://github.com/yourusername/AegisIntel-AI.git
cd AegisIntel-AI

# Start with Docker Compose
docker-compose up -d

# Access platform
# Frontend: http://localhost:3000
# Backend API: http://localhost:8000
# API Docs: http://localhost:8000/docs
