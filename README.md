# End-to-End-Azure-Monitoring-URL-Tests-Logs-Alerts-Insights
## Table of Contents
- [Monitoring –Availability /URL ping test Troubleshooting](#url-ping-test-troubleshooting)
- [Log Monitoring for VM Ware and Windows Server](#monitoring-setup)
- [Sending resource Logs to Log Analytical Workspace](#log-analytics-integration)
- [Creating Alert Rules](#creating-alert-rules)
- [Application Insights Configuration](#application-insights-configuration)

## Monitoring –Availability /URL ping test Troubleshootin 🌐 
Go to Application Insights > Availability -->
Click + Add test-->
Choose URL Ping Test.

Check for alerts -->enabled

set for 

- URL to test  
- Test frequency (default: every 5 mins)  
- Locations (Azure regions)  
- Success criteria (response time, HTTP 200 OK, etc.)

![Ping Test Setup](images/Picture1.png)
