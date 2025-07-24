# Auswahl- und Bewertungsmatrix für ISO 27001:2022 Annex A Controls

**Organisation:** FinSec GmbH  
**Modul:** 01_ISMS_Basics  
**Autor:** George K.  
**Version:** 1.0  
**Letztes Update:** 2025-07-25

---

## 1. Zweck dieses Dokuments

Diese Matrix dokumentiert die Auswahl, Priorisierung und Begründung der relevanten ISO/IEC 27001:2022 Annex A Controls für die FinSec GmbH. Grundlage sind die identifizierten Risiken im ISMS sowie die Anforderungen durch DORA, NIS2 und interne Geschäftsprozesse.

---

## 2. Bewertungsprinzip

**Auswahlkriterien:**
- Risiko (Impact x Likelihood gemäß Policy Kap. 5.1)
- Regulatorischer Zwang (DORA, DSGVO, SWIFT, FMA)
- Kritikalität des Geschäftsprozesses
- Umsetzbarkeit & Reifegrad

**Prioritäten:**
- **Hoch:** Muss sofort umgesetzt werden (gesetzlich, Risiko > 12)
- **Mittel:** Umsetzung innerhalb 6–12 Monate
- **Niedrig:** Monitoring oder spätere Phase

---

## 3. Auswahlmatrix (Auszug aus Annex A)

| Control-ID | Beschreibung | Risiko | Auswahlgrund | Priorität | Umsetzungsstatus |
|------------|--------------|--------|---------------|-----------|------------------|
| A.5.10     | Information security in supplier relationships | Hoch (15) | Cloud Services mit Kundendaten, DORA Art. 28 | Hoch | Offen |
| A.5.23     | Information security for use of cloud services | Hoch (20) | Hybrid-Cloud Architektur (Azure) | Hoch | Offen |
| A.6.5      | Responsibilities after termination or change of employment | Mittel (10) | Offboarding-Prozesse unvollständig | Mittel | Offen |
| A.7.4      | Physical security monitoring | Mittel (9) | Serverräume nicht rund um die Uhr überwacht | Mittel | Offen |
| A.8.4      | Access control | Hoch (16) | Zugriffsschutz auf Core Banking erforderlich | Hoch | In Umsetzung |
| A.8.11     | Use of cryptography | Hoch (18) | Verschlüsselung sensibler Kundendaten (AES-256) | Hoch | In Umsetzung |
| A.8.15     | Logging and monitoring | Hoch (20) | SIEM mit SOC notwendig, DORA Auditpflicht | Hoch | Offen |
| A.8.21     | Information security incident management | Kritisch (25) | DORA & DSGVO Meldepflicht (2h) | Hoch | In Umsetzung |
| A.8.22     | Business continuity planning | Kritisch (20) | Kein dokumentierter BCP vorhanden | Hoch | Offen |
| A.5.36     | Contact with authorities | Mittel (12) | FMA-/DSB-Kommunikation nicht geregelt | Mittel | Offen |

---

## 4. Maßnahmenplanung (Beispiel)

| Priorität | Maßnahme | Zieltermin | Verantwortlich |
|-----------|----------|------------|----------------|
| Hoch | SIEM-Einführung + SOC-Anbindung | 2025-08-31 | IT Security |
| Hoch | Vertragsprüfung Cloud-Provider | 2025-09-15 | Einkauf + CISO |
| Mittel | BCP-Dokumentation starten | 2025-10-01 | IT Governance |
| Mittel | Zutrittskontrollsystem bewerten | 2025-11-15 | Facility Management |

---

## 5. Hinweis für Auditoren

Die vollständige Control-Matrix umfasst alle 93 Annex A Controls. Diese Version bildet einen risikoorientierten Auszug ab, der zur Initialumsetzung innerhalb des ISMS-Scopes priorisiert wurde. Eine vollständige GAP-Analyse folgt im Modul `isms-mini-audit.md`.

---

## 6. Weiteres Vorgehen

- Status-Tracking über GitHub Issues oder GRC-System
- Implementierungsdokumentation (Beweisführung)
- Review alle 6 Monate (Change Management)
- Erweiterung um Control-Metriken (siehe `control-effectiveness-metrics.md`)

---

**Dokumentenklasse:** Vertraulich  
**Nächste Revision:** 2026-01-01
