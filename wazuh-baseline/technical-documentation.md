# Wazuh Baseline Technical Documentation

## Figure 8 — Security Events Dashboard
<img width="1672" height="771" alt="Screenshot 2026-03-31 125605" src="https://github.com/user-attachments/assets/93818126-e39a-4a64-9a4d-641167f39f19" />



## Figure 9 — Individual Alert Detail
<img width="1640" height="697" alt="Screenshot 2026-03-31 125658" src="https://github.com/user-attachments/assets/5e4edc30-6dd0-4248-92a2-76093162e1ca" />
<img width="1650" height="718" alt="Screenshot 2026-03-31 125711" src="https://github.com/user-attachments/assets/01a511c8-45ca-4c66-b6eb-c51bd14ea455" />
<img width="1650" height="177" alt="Screenshot 2026-03-31 131411" src="https://github.com/user-attachments/assets/5bb5352e-1f64-430a-bbe7-8dfbc8906fe8" />


## Figure 10 — Rule Tab
<img width="1653" height="613" alt="Screenshot 2026-03-31 125912" src="https://github.com/user-attachments/assets/9d944d94-2c2d-4102-8f8f-bf2a0544ba98" />


## Figure 11 — Raw JSON Alert Record
<img width="603" height="702" alt="Screenshot 2026-03-31 130017" src="https://github.com/user-attachments/assets/28344bba-bb78-4d7e-9747-7ae7d365cd34" />
<img width="579" height="632" alt="Screenshot 2026-03-31 131806" src="https://github.com/user-attachments/assets/85ca7e98-19f7-4bba-a62d-5547c5e9dcee" />
<img width="1401" height="301" alt="Screenshot 2026-03-31 131819" src="https://github.com/user-attachments/assets/dc659539-d244-4ef7-a699-8c08aa791ec7" />


## Figure 10 - Rule Tab Details
**Rule Groups:** authentication_failed, invalid_login, syslog, sshd

**Compliance Framework Mappings:**
- GDPR: IV_35.7.d and IV_32.2
- GPG13: 7.1
- HIPAA: 164.312.b
- MITRE: T1110.001 and T1021.004

This rule tab is accessible only through deliberate navigation into the rule detail view and is not surfaced at the alert list level.

## Full JSON Field Documentation
**Predecoder fields:** source program identified as sshd-session

**Agent metadata:** reporting host identified as kali-agent

**Structured data fields:**
- srcuser: invaliduser
- srcip: 127.0.0.1

**Rule metadata:**
- Severity level: 5
- Compliance tags: HIPAA 164.312.b, PCI DSS 10.2.4, 
  10.2.5, 10.6.1, TSC CC6.1, CC6.8, CC7.2, CC7.3
- MITRE techniques: T1110.001, T1021.004
