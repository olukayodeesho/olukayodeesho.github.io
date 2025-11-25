---
layout: home
title: "Home"
---

# 👋 Hi, I'm **Olukayode Esho**

**Senior Software Engineer & Technical Lead**  
13+ years building enterprise-grade financial systems, national payment integrations, cloud-based platforms, and AI/ML-enabled solutions.

---

## 🔧 Core Technical Skills

- **Languages:** C#, .NET Core, VB.NET, Java, Ruby on Rails, JavaScript, jQuery
- **Architecture:** Microservices, Distributed Systems, Event-Driven Apps
- **Cloud:** AWS, Azure
- **Databases:** MSSQL, PostgreSQL, MySQL, Oracle
- **NoSQL:** ElasticSearch, Redis, MongoDB, Neo4j
- **DevOps:** GitHub Actions, Jenkins, Octopus Deploy, Docker
- **Messaging:** RabbitMQ, Apache ActiveMQ, WCF, SOAP, REST APIs
- **AI/ML Tools:** GPT-4, Whisper, Gemini Pro

---

## 🧩 Key Projects

### **Payment & Banking Integrations (Multiple Technologies)**

- Payment gateway APIs (REST & SOAP)
- FX transfer engine integrations
- Western Union liquidation integration
- Transaction limit management service
- Airtime & bill payment engines
- National bulk transfer integration (NAPS)
- Internet Banking (Retail & Corporate) redevelopment
- National switching integrations (NIBSS)
- Cardless transactions (PayCode)
- Hardware 2FA authentication integration
- Settlement & reconciliation automation (BluePrism RPA + .NET)
- Collections integrations (Total Nigeria Plc & Immigration Services)

### **AI / Machine Learning Projects**

- Real-time multilingual speech translation system (Whisper + GPT + TTS)
- Reinforcement learning environment for legible action planning

### **Enterprise Systems Development**

- UKHSA national system redevelopment
- ElasticSearch optimization for scientific datasets
- Data transformation pipelines and integration services

---

## 📄 View My Full CV

👉 [Click to view CV](cv)

---

## 📝 Latest Blog Posts

{% for post in site.posts limit:5 %}

- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %d, %Y" }}
  {% endfor %}
