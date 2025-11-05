# 💼 Database Administrator Portfolio

## 👋 About Me
**[Your Name]**  
📧 [youremail@example.com]  
🌐 [LinkedIn Profile](https://linkedin.com/in/yourprofile)  
💻 [GitHub Profile](https://github.com/yourhandle)

---

## 🧠 Professional Summary
Experienced **Database Administrator (DBA)** with **[10+] years** of expertise managing and optimizing SQL Server, Azure SQL, and other RDBMS platforms. Skilled in high availability, performance tuning, automation, and database security. Passionate about building reliable, scalable, and secure database systems that drive business success.

---

## 🧩 Technical Skills

| Category | Skills |
|-----------|---------|
| **Databases** | Microsoft SQL Server (2005–2019), Azure SQL, MySQL, PostgreSQL |
| **High Availability** | Always On Availability Groups, Log Shipping, Replication, Failover Clustering |
| **Security & Compliance** | TDE, Row-Level Security, Role-Based Access Control |
| **Performance Tuning** | Query optimization, Index strategies, Execution plan analysis, Statistics management |
| **Automation & Scripting** | PowerShell, T-SQL, SQL Agent Jobs, SSIS |
| **Backup & Recovery** | Full/Differential/Log backups, Recovery models, Point-in-time restore |
| **Monitoring & Maintenance** | SQL Profiler, Extended Events, DMVs, SolarWinds DPA |
| **Cloud Platforms** | Azure SQL Database, Managed Instance |
| **Tools** | SSMS, Azure Data Studio, Git, Jenkins, Visual Studio Code |

---

## 🚀 Key Projects

### 🏗 Always On Availability Setup for Enterprise ERP
**Environment:** SQL Server 2019 Enterprise, Windows Server 2019  
**Role:** Lead DBA  
- Designed and implemented **Always On Availability Groups** for high availability and disaster recovery.  
- Configured listener-based failover for ERP and reporting databases.  
- Achieved **99.99% uptime** with secondary read-only replicas for analytics.

---

### 🔐 Transparent Data Encryption (TDE) Rollout
**Environment:** SQL Server 2016–2019  
**Objective:** Strengthen database security and ISO 27001 compliance.  
- Deployed **Transparent Data Encryption (TDE)** across 30+ production databases.  
- Automated certificate rotation using PowerShell scripts.  
- Reduced compliance audit findings by 100%.

---

### ⚙️ Performance Tuning and Query Optimization
**Environment:** Mixed workloads (OLTP + Reporting)  
- Identified top 10 slow queries using **Query Store** and **Extended Events**.  
- Optimized indexing strategy, reducing average query response time by **68%**.  
- Implemented **automatic statistics updates** and baseline dashboards.

---

### ☁️ Migration to Azure SQL Managed Instance
**Scope:** 1 TB on-premise database with minimal downtime  
- Used **Azure Database Migration Service (DMS)** for seamless cutover.  
- Created **failover runbook** and post-migration validation scripts.  
- Achieved downtime of less than **15 minutes** during migration.

---

## 💾 Sample Code & Automation

### Database Schema Example
```sql
CREATE TABLE Player (
    PlayerID INT IDENTITY PRIMARY KEY,
    FullName NVARCHAR(100),
    Position NVARCHAR(50),
    DateOfBirth DATE,
    CreatedAt DATETIME DEFAULT GETDATE()
);
