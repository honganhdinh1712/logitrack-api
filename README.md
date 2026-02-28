# 🚚 LogiTrack System - Backend API

**LogiTrack** is a high-performance, real-time last-mile delivery management system. It addresses complex logistics challenges such as intelligent driver dispatching, route optimization, and automated financial settlements based on real-world operational data.

## 🚀 Key Features

- **Smart Dispatching Engine:** Automated order routing to the nearest available drivers using Geo-spatial queries.
- **Real-time Tracking:** Live driver location monitoring via Socket.io & Redis-backed caching.
- **Proof of Delivery (PoD):** Mandatory image-based verification for pickup and delivery stages.
- **Dynamic SLA & Business Rules:** Automated delivery deadlines and sophisticated return-to-sender (RTS) workflows.
- **Finance & Gamification:** Digital wallet system, automated fee deductions, and driver reliability scoring.

## 🛠 Tech Stack

- **Framework:** NestJS (Node.js)
- **ORM:** TypeORM
- **Database:** PostgreSQL (Core), Redis (Geo-spatial & Caching)
- **Real-time:** Socket.io (Websockets)
- **Package Manager:** Yarn

## 🏗 System Architecture

## 🧠 Middle-Level Engineering Challenges

- **Concurrency Control:** Mitigating race conditions during order acceptance using **Pessimistic Locking**.
- **Scalability:** Optimized coordinate querying with Database Indexing and Redis Geo-hashing.
- **Data Integrity:** Ensuring financial consistency across multiple tables using **ACID Transactions**.
- **Edge Case Handling:** Implementing Offline-sync resilience and driver penalty logic for frequent rejections.

## 🚦 Getting Started

### Prerequisites

- Node.js (v18+)
- PostgreSQL & Redis
- Yarn

### Installation
