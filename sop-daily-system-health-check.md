# SOP: Daily System Health Check

**Version:** 1.0  
**Date:** 2025-08-27  
**Owner:** IT Operations Team  

---

## 1. Purpose
To ensure that servers and applications are operating within acceptable performance and availability thresholds.  

## 2. Scope
Applies to all production servers and critical applications.  

## 3. Responsibilities
- **IT Operations Analyst**: Perform daily health checks.  
- **Team Lead**: Review daily log and escalate critical issues.  

## 4. Procedure
1. Log in to the system monitoring tool (e.g., SolarWinds, Nagios, Zabbix).  
2. Check CPU, RAM, and Disk utilization (threshold: CPU < 80%, RAM < 75%).  
3. Review error logs for critical warnings.  
4. Confirm scheduled jobs and backups completed successfully.  
5. Document findings in the Daily Ops Log.  
6. Escalate incidents to Level 2 support if thresholds are breached.  

## 5. Escalation Matrix
- Minor issue: Document and monitor.  
- Critical issue (downtime, system crash): Escalate to L2 and open incident ticket immediately.  

---
