# Service Health Dashboard & API Monitoring System

## Note on Source Code Availability
This project is a proprietary enterprise application developed for a financial technology company. Due to confidentiality and security agreements, the source code cannot be shared publicly. This repository serves as a portfolio showcase highlighting the system design, features, and business impact.

---

## Overview
This is a 24/7 Service Health and API Monitoring Dashboard built to monitor critical banking APIs in real time.

The system functions as a central monitoring platform for production services, enabling operations teams to detect, analyze, and resolve issues before they impact users.

I was responsible for the end-to-end development of this application, including system design, backend logic, frontend implementation, and monitoring workflows.

---

## Impact

- Reduced API downtime through real-time polling and status tracking  
- Shifted issue detection from reactive (customer-reported) to proactive monitoring  
- Decreased incident identification and response time for operations teams  
- Enabled flexible configuration of thresholds, polling intervals, and API-specific rules  

---

## Core Features

### Real-Time Monitoring
- Continuous health checks with live status indicators  
- Server-synced updates with controlled polling mechanisms  

### Analytics and Metrics
- Tracks API types (.NET, Java)  
- Monitors transaction volumes, pending queues, and failure counts  

### Alert System
- Dynamic alerts triggered based on configurable limits such as:
  - PENDING_LIMIT  
  - FAILURE_LIMIT  
  - Timeout conditions (STATUS_QUERY)  
- Visual indicators for quick issue identification  

### Operational Controls
- Manual execution controls ("Run Now")  
- Integration with a custom scheduler for restarting or resyncing jobs  

### Log Viewer
- Direct querying of backend logs from AS/400 Integrated File System via SQL  
- Efficient rendering of large log datasets within the UI  

### UI Capabilities
- Global search and filtering  
- Column toggling  
- Real-time updates without page refresh  

---

## System Architecture (High-Level)

- Monitoring engine for API polling  
- Custom scheduler for job execution and retries  
- Database layer for storing API states and logs  
- Web dashboard for real-time visualization  

---

## Tech Stack

Backend:
- Java  
- DB2 / AS400 integration  

Frontend:
- JSF (JavaServer Faces)  
- PrimeFaces  
- CSS  

Scheduling:
- Custom Java-based job scheduler  

---

## Role and Responsibilities

- Designed and developed the system from scratch  
- Implemented backend monitoring and polling logic  
- Built frontend dashboard using JSF and PrimeFaces  
- Developed custom scheduling and alert mechanisms  
- Optimized performance for handling large logs and real-time updates  

---

## Summary
This project reflects experience in building enterprise-grade monitoring systems, working with legacy infrastructure, and delivering real-time dashboards for production environments.

---

## Disclaimer
This repository is intended for demonstration purposes only. No proprietary source code is included.
