# Customer-Relationship-Management-System
A Java + MySQL desktop CRM application with Login, Dashboard, Customer Management, Interactions, Service Tickets and Deals modules built using Java Swing GUI.

# ◈ CRM Pro — Customer Relationship Management System
### BTech Project | Java + MySQL | Swing GUI

---

## 📋 Project Overview

A fully-featured **Customer Relationship Management (CRM)** desktop application built with:
- **Java Swing** — Rich, dark-themed GUI
- **MySQL** — Relational database backend
- **JDBC** — Java Database Connectivity
- **Design Patterns** — DAO, Singleton, MVC

---

## 🎯 Features

| Module | Features |
|--------|----------|
| **Dashboard** | KPI cards, live stats, pipeline value, quick tips |
| **Customers** | Add, Edit, Delete, Search, View Details |
| **Interactions** | Log Calls, Emails, Meetings, Follow-ups |
| **Service Desk** | Create Tickets, Update Status, Priority tracking |
| **Deals** | Pipeline management, Stage tracking, Revenue |

---

## 🗃️ Database Tables

| Table | Purpose |
|-------|---------|
| `customers` | Core customer profiles |
| `interactions` | Every touchpoint (call, email, meeting) |
| `service_history` | Support tickets and resolutions |
| `deals` | Sales pipeline and deal stages |

---

## 🎨 UI Theme
- Dark navy color scheme (`#0D111E` background)
- Electric blue accent (`#388BFF`)
- Color-coded status badges (Green=Active, Red=Danger, Yellow=Pending)
- Striped table rows with hover effects
- Smooth sidebar navigation with active state indicator

---

## 📐 Design Patterns Used

| Pattern | Where Used |
|---------|-----------|
| **Singleton** | `DatabaseConnection` — single DB connection |
| **DAO (Data Access Object)** | All `*DAO.java` classes |
| **MVC (Model-View-Controller)** | model/ + ui/ + dao/ separation |
| **Factory Method** | `UITheme` button/component factories |

---

## 📊 Sample Data
The SQL script inserts 6 sample customers, interactions, tickets, and deals so the app looks populated immediately on first run.

---

## 🧪 Testing the App
1. Launch → Splash screen → Dashboard loads with live stats
2. Go to **Customers** → Try Add/Edit/Delete/Search
3. Go to **Interactions** → Log a new call or email
4. Go to **Service Desk** → Create a ticket, then update its status
5. Go to **Deals** → Add a deal, change its stage

---

## 👨‍💻 Technologies
- **Language:** Java 17
- **GUI:** Java Swing (javax.swing)
- **Database:** MySQL 8.0
- **Connectivity:** JDBC (mysql-connector-java)
- **IDE:** IntelliJ IDEA / Eclipse / NetBeans

---

*BTech Second Year Project — CRM System | 2026*

