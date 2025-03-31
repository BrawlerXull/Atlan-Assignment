# Atlan Platform Internship Challenge 2025 - Cloud Cost Optimization

## 🚀 Overview
This repository contains my solution for the **Atlan Internship Challenge 2025** on **Cloud Cost Optimization**. The challenge focuses on building a system to monitor, analyze, and optimize cloud expenses (AWS/Azure/GCP), ensuring proactive cost control and efficiency.

## 📜 Scenario
Imagine you’re in a team experiencing **continuous increases in monthly cloud costs** without real-time visibility. Key challenges include:
- **Delayed cost awareness:** Teams realize cost surges too late.
- **Lack of cost attribution:** Identifying **which services, teams, or projects** contributed to cost increases is guesswork.
- **Non-straightforward optimizations:** There’s no clear, automated process to reduce top cost contributors.

### **Proposed Solution**
The solution comprises a **multi-layered cloud cost optimization framework**:

1️⃣ **Data Collection & Aggregation** – Extracts and normalizes cost data from AWS, Azure, and GCP billing APIs.
2️⃣ **Intelligent Cost Analysis** – Processes raw billing data, identifies inefficiencies, and detects anomalies.
3️⃣ **Monitoring & Alerting** – Implements dashboards (Grafana/Kibana) and real-time alerts (Alertmanager/Zenduty).
4️⃣ **Governance & Optimization** – Enforces budget policies (OPA, Apache Ranger) and recommends cost-saving measures.
5️⃣ **Execution & Automation** – Uses **Terraform, Argo Workflows, and Lambda Functions** for automatic cost optimizations.

## 📌 Deliverables
### 1️⃣ **High-Level System Diagram**
A visual representation of the cloud cost optimization architecture, detailing key components and interactions.

### 2️⃣ **Explanatory Document**
A brief 1-2 page PDF covering:
- **Major design decisions and trade-offs.**
- **Proof that the solution effectively solves the problem.**
- **Known limitations and why they are safe to ignore.**
