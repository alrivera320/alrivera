# 💼 Database Administrator Portfolio

## 👋 Hi! I'm Alejandre R. Rivera Jr.
📧 [alrivera320@gmail.com]  
🌐 [LinkedIn Profile](https://www.linkedin.com/in/alejandre-rivera-jr-693920151)  
💻 [GitHub Profile](https://github.com/alrivera320)

---

## 🧠 Professional Summary
Experienced **Database Administrator (DBA) / Database Developer** with **[10+] years** of expertise managing and optimizing SQL Server, Azure SQL, and other RDBMS platforms. Skilled in high availability, performance tuning, automation, and database security. 

---

## 🧩 Technical Skills

| Category | Skills |
|-----------|---------|
| **Databases** | Microsoft SQL Server (2008–2019), Azure SQL, MySQL |
| **High Availability** | Always On Availability Groups, Replication, Failover Clustering |
| **Security & Compliance** | TDE, Row-Level Security, Role-Based Access Control |
| **Performance Tuning** | Query optimization, Index strategies, Execution plan analysis, Statistics management |
| **Automation & Scripting** | T-SQL, Bash, SQL Agent Jobs, SSIS |
| **Backup & Recovery** | Full/Differential/Log backups, Recovery models, Point-in-time restore |
| **Monitoring & Maintenance** | SQL Profiler, SolarWinds DPA, DMVs |
| **Cloud Platforms** | Azure SQL Database, Managed Instance |
| **Tools** | SSMS, Azure Data Studio, Git, Visual Studio Code |

---

## 🚀 Key Projects

### 🏗 Always On Availability Setup for National Confederation of Cooperatives
**Environment:** SQL Server 2019 Enterprise, Windows Server 2019  
**Role:** Lead DBA  
- Designed and implemented **Always On Availability Groups** for high availability and disaster recovery.  
- Configured listener-based failover for ERP and reporting databases.  
- Achieved **99.90% uptime** with secondary read-only replicas for analytics.

---

### 🔐 Transparent Data Encryption (TDE) Rollout
**Environment:** SQL Server 2016–2019  
**Objective:** Strengthen database security at rest.  
- Deployed **Transparent Data Encryption (TDE)** to production databases.  
- Automated certificate rotation using PowerShell scripts.  
- Reduced compliance audit findings by 100%.

---

### ⚙️ Performance Tuning and Query Optimization
**Environment:** Mixed workloads (OLTP + Reporting)  
- Identified top 10 slow queries using **Query Store** and **Extended Events**.  
- Optimized indexing strategy, reducing average query response time by **68%**.  
- Implemented **automatic statistics updates** 

---

### ☁️ Migration to Azure SQL Managed Instance
**Scope:** on-premise database with minimal downtime  
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
