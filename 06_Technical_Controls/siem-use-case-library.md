# SIEM Use Case Library – SecureBank AG

**Modul:** 06_Technical_Controls  
**Organisation:** SecureBank AG  
**Autor:** George K.  
**Version:** 1.0  
**Vertraulichkeit:** Intern – Security Operations

---

## 1. Ziel

Diese Use Case Library dient der Definition und Umsetzung von Überwachungsregeln im SIEM-System (z. B. Microsoft Sentinel), um sicherheitsrelevante Ereignisse in der IT-Landschaft der SecureBank AG frühzeitig zu erkennen.

---

## 2. Use Cases nach Risikokategorie

| ID | Titel | Beschreibung | Kritikalität | Reaktion |
|----|-------|--------------|--------------|----------|
| UC-001 | Ungewöhnliche Anmeldungen | Login außerhalb EU oder zu ungewöhnlicher Uhrzeit | Hoch | Alert, MFA-Reset |
| UC-002 | Änderung Admin-Rollen | RBAC-Änderung in Azure ohne Change-Ticket | Hoch | Alert + Audit |
| UC-003 | USB-Zugriff | Externer Datenträger an Endpoint ohne Freigabe | Mittel | Alert + Block |
| UC-004 | DNS-Traffic zu Command-&-Control-Domains | Malware-Kommunikation über DNS | Hoch | Quarantäne |
| UC-005 | Fehlgeschlagene Backups | Backup-Failure > 3x in 24h | Mittel | Ticket an IT |

---

## 3. Quellen und Systeme

- Microsoft Sentinel / Log Analytics
- Azure AD Sign-In Logs
- Defender for Endpoint
- Backup & Monitoring Tools

---

## 4. Wartung & Weiterentwicklung

- Review der Use Cases monatlich
- Lessons Learned aus Incidents fließen ein
- Verknüpfung mit `critical-alerts.yaml`

---
