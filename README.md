# Sentiment Analysis
Real-time sentiment analysis app using Spring Boot, Kafka, and WebFlux. It processes live news streams, integrates a news API, and applies StanfordCoreNLP for sentiment scoring. The system uses Kafka for message queuing and dynamic time windows for efficient real-time sentiment insights.

# 📰 Real-Time News Sentiment Analysis

## 📘 Overview
This project is a **real-time sentiment analysis system** built with **Spring Boot**, **Kafka**, and **Stanford CoreNLP**.  
It continuously fetches news headlines and content, streams them through Kafka, analyzes their sentiment, and exposes real-time results through a reactive REST API.

The goal is to demonstrate how to combine **real-time data streaming**, **NLP**, and **reactive programming** into one microservice pipeline.

---

## 🚀 Features
- 🔄 **Real-time streaming** of news articles via a public News API  
- 💬 **Sentiment analysis** using Stanford CoreNLP  
- ⚙️ **Reactive Kafka integration** using Reactor Kafka  
- 🧩 **REST endpoints** to:
  - Send custom messages to Kafka  
  - View live Kafka messages  
  - Start and stop news streaming  
  - Group messages by time window  
  - Compute average sentiment in real-time  

---

## 🧠 Technologies Used
| Technology | Purpose |
|-------------|----------|
| **Java 17+** | Programming language |
| **Spring Boot (WebFlux)** | Backend framework for reactive REST APIs |
| **Reactor Kafka** | Reactive Kafka producer & consumer |
| **Apache Kafka** | Message queue for streaming data |
| **Stanford CoreNLP** | Natural language sentiment analysis |
| **News API** | External data source for real-time news |
| **Maven** | Build and dependency management |

---


