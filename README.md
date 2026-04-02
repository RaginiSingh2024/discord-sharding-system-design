# 🚀 Discord-Like Scalable Chat System (Sharding Project)

## 📌 Overview

This project simulates a Discord-like chat system and explores how systems behave under high load.

The focus is not just building a chat app, but understanding:

* Scaling challenges
* Load distribution
* System failures

---

## 🎯 Objective

To design a scalable backend system using sharding strategies and analyze real-world problems like:

* Hotspots
* Load imbalance
* Server overload

---

## ⚙️ Features

* Single server chat simulation
* Multi-shard architecture
* User-based sharding
* Channel-based sharding
* Hash-based sharding
* Load imbalance detection
* Basic system optimization

---

## 🧠 Key Learnings

* Why single server systems fail at scale
* Importance of shard key selection
* Real-world sharding challenges
* Trade-offs in distributed systems

---

## 🏗️ System Flow

User → Server → Shard → Store Message

---

## 📊 Sharding Strategies Implemented

### 1. User-Based Sharding

* Uses: user_id % N
* Problem: heavy users overload a shard

### 2. Channel-Based Sharding

* Messages go to channel shard
* Problem: viral channels create hotspots

### 3. Hash-Based Sharding

* Better distribution
* Still has issues when shards change

---

## 📈 Results

* Observed performance issues in single server
* Detected imbalance in poor sharding strategies
* Improved distribution using hashing

---

## 🚀 Future Improvements

* Consistent hashing
* Replication
* Load balancing
* Fault tolerance

---

## 📂 Tech Stack

* Python
* Google Colab
* System Design Concepts

---

## ✨ Author

Ragini Singh

