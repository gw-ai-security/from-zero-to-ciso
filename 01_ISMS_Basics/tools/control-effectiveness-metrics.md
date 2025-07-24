# Metriken zur Wirksamkeit von Sicherheitskontrollen (Control Effectiveness Metrics)

**Organisation:** FinSec GmbH  
**Modul:** 01_ISMS_Basics  
**Autor:** George K.  
**Version:** 1.0  
**Letztes Update:** 2025-07-25

---

## 1. Zweck des Dokuments

Dieses Dokument definiert Metriken zur Messung der **Wirksamkeit von Informationssicherheitsmaßnahmen** (Controls) gemäß ISO/IEC 27001:2022. Ziel ist es, objektive Kennzahlen zur Bewertung, Verbesserung und Steuerung des ISMS bereitzustellen.

---

## 2. Bewertungsmodell

### 2.1 Qualitative Einstufung

| Level | Beschreibung |
|-------|--------------|
| 0 – Nicht vorhanden | Control existiert nicht oder ist unzureichend |
| 1 – Reaktiv | Control vorhanden, aber nur manuell und nicht dokumentiert |
| 2 – Formalisiert | Control dokumentiert, Umsetzung uneinheitlich |
| 3 – Implementiert | Control ist umgesetzt und wird genutzt |
| 4 – Überwacht | Wirksamkeit wird regelmäßig gemessen (KPIs vorhanden) |
| 5 – Optimiert | Control wird aktiv verbessert, Lessons Learned fließen ein |

---

### 2.2 Quantitative Metriken (Auswahl)

| Control-ID | Thema | Metrik | Zielwert |
|------------|-------|--------|----------|
| A.8.15 | Logging & Monitoring | Anzahl kritischer Incidents ohne Logdaten | 0 |
| A.5.10 | Supplier Security | Anzahl freigegebener Lieferanten mit dokumentiertem Security Assessment | 100 % |
| A.8.21 | Incident Response | Durchschnittliche Reaktionszeit bei Vorfällen (TTR) | ≤ 2h |
| A.8.11 | Kryptografie | Anteil verschlüsselter Datenträger | 100 % |
| A.8.22 | Business Continuity | Erfolgsquote BCP-Tests (Simulationen pro Jahr) | ≥ 90 % |
| A.6.5 | Offboarding-Prozess | Zeit bis Sperrung nach Kündigung | ≤ 4h |
| A.5.36 | Behördenkommunikation | Anzahl verspäteter gesetzlicher Meldungen | 0 |

---

## 3. Zielgruppen

- **CISO / ISB** – Steuerung der ISMS-Performance
- **Audit-Team** – Beurteilung der Wirksamkeit einzelner Controls
- **Management** – Überblick über Fortschritt & Sicherheitslage
- **IT-Teams** – Umsetzung & Korrekturmaßnahmen

---

## 4. Reporting

- Monatliches Reporting an CISO & Geschäftsleitung
- Visualisierung der KPI-Werte in Dashboards
- Verknüpfung mit Lessons Learned nach Incidents

---

## 5. Weiterentwicklung

- Metriken werden halbjährlich überprüft und angepasst
- Erweiterung um Risk Exposure Scores (z. B. durch Schwachstellen-Scanner)
- Optional: Automatisierung über GRC-Tools, SIEM oder Excel-Vorlagen

---

**Dokumentenklasse:** Intern – Vertraulich  
**Nächste Revision:** 2026-01-01
