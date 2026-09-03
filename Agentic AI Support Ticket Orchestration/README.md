
# Agentic AI Support Ticket Orchestration

This project implements a no‑code Agentic AI workflow using Zapier and Google Sheets to classify support tickets, route them through multi‑path logic, trigger automated actions, and incorporate human‑in‑the‑loop approval for high‑risk cases. The system also generates audit logs for compliance and analytics.

---

## Features
- AI‑powered ticket classification  
- Three automated paths: Routine, Billing Escalation, High‑Risk/Cancellation  
- Human‑in‑the‑loop approval for sensitive tickets  
- Automated email responses  
- Audit log creation for traceability  
- Google Sheets + Zapier orchestration  
- Agentic AI decision + action pipeline  

---

## Architecture
The workflow includes:
- AI prediction step  
- Conditional routing into three paths  
- Human approval for high‑risk tickets  
- Automated updates, emails, and audit logs  

(See the included PNG diagram in the repository.)

---


---

## How the Workflow Works

### Routine Path
- Low/medium risk  
- Non‑billing  
- Non‑cancellation  
- Auto‑reply + audit log  

### Billing Escalation Path
- Issue_Category = Billing  
- Billing escalation email + audit log  

### High‑Risk / Cancellation Path
- High risk OR cancellation OR negative sentiment  
- Human approval required  
- Approved → send email  
- Rejected → manual review  
- Audit log created  

---

## Technologies Used
- Zapier  
- Google Sheets  
- Agentic AI (Decision + Action Agents)  
- Human‑in‑the‑loop approval
- Gmail

---

## Future Improvements
- Add more specialized paths (Technical, Account Management)  
- Add audit logs to Routine & Billing paths  
- Add Low Confidence Path  
- Add Fraud/Security Escalation Path  
- Add auto‑assignment to agents  
- Add analytics dashboards  

---


