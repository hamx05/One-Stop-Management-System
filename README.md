# DS-Assignment-01: One-Stop Management System

A mini-project built as part of the **Data Structures** course during my 3rd semester at FAST NUCES (Fall 2024).  
It simulates a simplified One-Stop system for managing student service requests using linear data structures.

## 💡 Overview

This command-line system handles:
- Ticket creation, assignment, and resolution
- Agent management
- Real-time logs and basic analytics

Key data structures used: **Arrays**, **Linked Lists**, **Stacks**, **Queues**

## ⚙️ Features

### Ticket Management
- Add, remove, and search tickets  
- Sort by priority, creation time, or customer name  
- Managed using a **Linked List**

### Agent Management
- Add and manage agents across departments  
- Auto-assign tickets based on priority and load  
- Tracked using **Dynamic Arrays**

### Logs & Queues
- Pending tickets handled via a **Queue**  
- Resolved tickets stored in a **Stack**  
- Recent activity viewable from logs

### Reporting & Analysis
- Display open tickets and agent workloads  
- Sort using: Bubble, Insertion, Selection, Merge, Quick Sort  
- Search using: Interpolation and Bubble Search  
- Configurable sorting/searching via a `config.txt` file

## How To Run
```bash
g++ OneStopManagementSystem.cpp Tickets.cpp Agents.cpp TicketResolutionLogs.cpp ReportingAndAnalytics.cpp -o OneStopManagementSystem
```

Made with 💻 in C++ as part of my academic journey.
~ hammad