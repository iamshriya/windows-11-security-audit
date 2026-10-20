Windows 11 Security Audit
Overview
A beginner-friendly, user-performed review of selected Windows 11 security controls using built-in Windows Security, Windows Update, and Event Viewer. The project emphasizes accurate observations and evidence-based conclusions.
Objectives
Review Microsoft Defender Quick scan and security intelligence status.
Check visible Windows Firewall profile status.
Check Windows Update restart status.
Review selected Windows Security log events.
Document findings, limitations, and recommendations.
Tools
Windows Security
Windows Update
Event Viewer (eventvwr.msc)
Microsoft Excel
Summary of Observations
Defender Quick scan: reported no threats found. This does not guarantee the device is malware-free.
Firewall: user reported firewall enabled for all visible network profiles.
Windows Update: after restarting, Windows Update no longer requested a restart.
Event ID 5379: observed in the Security log; this event alone is not proof of credential theft.
Event ID 4624: Logon Type 5, account SYSTEM; consistent with service logon activity, not proof of an attack.
Event ID 4672: account SYSTEM; special privileges can be expected Windows activity.
Defender definitions: initial update failed with code 2147416390; later the UI reported "Security intelligence is up to date." The cause of the initial failure was not confirmed.
Files
Windows_Security_Audit_Checklist.xlsx --- findings log and project notes.
Windows_11_Security_Audit_Report.docx --- detailed audit report.
Add redacted screenshots only when they support the observations.
Limitations
This is an educational, limited manual review---not a penetration test, forensic investigation, or guarantee that the computer is secure. Findings are based on visible results reported during the review. Event IDs must be interpreted in context.
Responsible Reporting
Do not publish personal usernames, IP addresses, device serial numbers, or other private information in screenshots. Do not describe an event as malicious without supporting evidence.
Suggested Resume Entry
Windows 11 Security Audit (Beginner Portfolio Project) --- Reviewed built-in Windows security settings, documented Defender scan and update status, checked firewall and Windows Update status, and interpreted selected Windows Security events with evidence-based risk notes and recommendations.
