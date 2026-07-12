# Project 4 – Windows Log Analysis

## Objective

In this project, I’ll practice analyzing Windows event logs to identify key security events. I’ll focus on reviewing logon attempts, system details, and suspicious activity from the Event Viewer, which is a crucial skill for a SOC analyst working in a Windows environment.

---

## Environment

- Windows 10 Pro
- Event Viewer
- PowerShell
- Desktop Environment

---

## Skills Practiced

- Navigating Windows Event Viewer
- Filtering and searching for logon events
- Identifying failed and successful logins
- Reviewing system resource usage
- Using PowerShell to gather event data
- Understanding Windows Security logs for SOC analysis

---

## Commands and Tools Used

| Command/Tool               | Purpose                                                 |
| -------------------------- | ------------------------------------------------------- |
| Event Viewer               | Review Windows security, logon, and system logs          |
| PowerShell `Get-EventLog`  | Retrieve event log data for automation and review        |
| Filter by Event ID 4625    | Identify failed logon attempts                           |
| Filter by Event ID 4624    | Identify successful logon attempts                       |
| Resource Monitor           | Check CPU, memory, and disk usage                        |

---

## Lab Activities

- Opened Windows Event Viewer and explored the security logs.
- Filtered event logs to isolate logon attempts (Event IDs 4624 for success, 4625 for failure).
- Used PowerShell to pull event data for further inspection.
- Reviewed system resource usage via Resource Monitor.
- Created a log review workspace to record findings.
- Documented all suspicious or abnormal activities for follow-up.

---

## Screenshots

- 01 – Logon Events Overview  
  ![Logon Events Overview](screenshots/Project4/01-Logon-Events-Overview.png)

- 02 – Viewing Failed Logons  
  ![Viewing Failed Logons](screenshots/Project4/02-Viewing-Failed-Logons.png)

- 03 – Successful Logon Details  
  ![Successful Logon Details](screenshots/Project4/03-Successful-Logon-Details.png)

- 04 – System Resource Usage  
  ![System Resource Usage](screenshots/Project4/04-System-Resource-Usage.png)

---

## Lessons Learned

- I learned how to identify both successful and failed logon attempts using Windows Event Viewer.
- I became more comfortable filtering event logs to find security-relevant events.
- I realized the importance of correlating logon attempts with system resource usage to spot anomalies.

---

## SOC Analyst Takeaways

- In a SOC environment, Windows log analysis is critical for detecting intrusions and monitoring user behavior.
- Knowing how to navigate Event Viewer and filter by logon events helps pinpoint suspicious access patterns.
- Combining log data with resource monitoring can reveal potential misuse or performance issues tied to security incidents.
