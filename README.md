🗄️ SQL-DBA-Scripts
SQL Server DBA toolkit — production-ready scripts covering index maintenance, statistics management, backup & restore, security auditing, performance tuning, and monitoring alerts. Designed for SQL Server 2019/2022 and Azure SQL environments.

👤 About
Built by a SQL Server DBA with hands-on experience managing large database estates across on-premises and cloud environments (Azure SQL, Azure SQL Managed Instance). These scripts are used in real production workflows and are shared here as a personal portfolio and reference library.

📁 Repository Structure
📜 Script Categories
🔧 Index Maintenance - Scripts for intelligent index rebuild and reorganize operations based on fragmentation levels. Integrated with Ola Hallengren's IndexOptimize procedure and CommandLog table for tracking execution history.
📊 Statistics Management - Statistics health reporting across all user databases. Bulk statistics update with date-based filtering. Identifying stale statistics that impact query plan quality
💾 Backup & Restore - Backup job validation and history reporting. Restore testing scripts for DR readiness. Backup file size and duration trend analysis.
🔐 Security & Auditing - SQL login audit, identifying logins without password policy enforcement. Server-level and database-level permission reviews. Orphaned user detection
⚡ Performance Tuning - Top wait stats analysis. Missing index recommendations from DMVs. Expensive query identification via sys.dm_exec_query_stats. Blocking and deadlock monitoring
📡 Monitoring & Alerting - Disk space capacity planning scripts. SQL Agent job failure history. Long-running query detection. TempDB usage monitoring.