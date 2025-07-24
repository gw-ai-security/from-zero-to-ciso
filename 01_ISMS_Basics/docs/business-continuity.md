# Business Continuity Planning (BCP) – FinSec GmbH

**Organisation:** FinSec GmbH  
**Modul:** 01_ISMS_Basics  
**Autor:** George K.  
**Version:** 1.0  
**Datum:** 2025-07-26  
**Vertraulichkeit:** Intern – Notfallplanung

---

## 1. Zielsetzung

Dieses Dokument beschreibt die Business Continuity Strategie der FinSec GmbH für den Fall von schwerwiegenden IT-Störungen. Ziel ist es, **geschäftskritische Systeme schnellstmöglich wiederherzustellen** und regulatorische Anforderungen (ISO 27001 A.8.22, DORA Art. 11, FMA-Rundschreiben Punkt 4.3) zu erfüllen.

---

## 2. Anwendungsbereich

Der BCP gilt für alle produktiven IT-Systeme der FinSec GmbH, insbesondere:

- Core Banking Plattform (On-Premise)
- Zahlungsverkehrs-API (Cloud-basiert)
- Kundenportal & Online Banking (Azure)
- Interne Kommunikationssysteme (MS Teams, E-Mail)
- Backup- und Recovery-Systeme

---

## 3. Business Impact Analyse (BIA)

### Kritische Systeme & Prozesse

| System / Prozess | Kritikalität | Begründung |
|------------------|--------------|------------|
| Echtzeit-Zahlungsverkehr | Hoch | Reputations- und Liquiditätsrisiko |
| Online-Banking Login | Hoch | Kundenzufriedenheit & SLA |
| Kontoüberträge / SEPA | Mittel | Verzögerung möglich, aber übertragbar |
| Buchhaltungssystem | Mittel | 2–3 Tage Toleranzzeit |
| Backup-Infrastruktur | Hoch | Grundlage für Wiederanlauf |

---

## 4. Wiederherstellungsziele (RTO/RPO)

| System | RTO (max. Ausfallzeit) | RPO (max. Datenverlust) |
|--------|------------------------|--------------------------|
| Core Banking | 4 Stunden | 15 Minuten |
| Zahlungsverkehr (API) | 2 Stunden | 10 Minuten |
| Kundenportal | 6 Stunden | 30 Minuten |
| Backoffice Systeme | 24 Stunden | 12 Stunden |

---

## 5. Kontinuitätsmaßnahmen

### 5.1 Technische Maßnahmen

- Geo-redundante Backups (Azure Backup Vault + On-Prem Snapshots)
- Automatisierte Recovery-Tests (halbjährlich)
- Failover auf sekundäre Rechenzentren (Data Center Linz)
- Notfall-E-Mail-Infrastruktur (Outlook via Webmail-Fallback)

### 5.2 Organisatorische Maßnahmen

- BCP-Notfallhandbuch (Druck & digital verfügbar)
- Regelmäßige BCP-Übungen mit Notfallteams
- Eskalationsmatrix mit 24/7-Rufbereitschaft
- Schnittstelle zum Incident Response Team

---

## 6. Rollen & Verantwortlichkeiten

| Rolle | Aufgabe |
|-------|---------|
| BCP-Koordinator (CISO/ISB) | Gesamtverantwortung, Tests & Audit |
| IT-Betrieb | Wiederherstellung der Infrastruktur |
| Fachbereiche | Priorisierung der Geschäftsprozesse |
| Kommunikation | Kunden-/Behördenbenachrichtigung |
| Backup-Admin | Datenwiederherstellung gemäß RPO-Vorgaben |

---

## 7. Prüf- & Teststrategie

- **Technischer Recovery-Test** (halbjährlich)
- **Manueller Tabletop-Test** (jährlich)
- **Blackout-Test (Simulation)** – alle 2 Jahre
- Dokumentation via `BCP-Testprotokoll` (nicht enthalten)

---

## 8. Regulatorischer Abgleich

| Regulatorik | Abgedeckter Aspekt |
|-------------|--------------------|
| ISO27001 A.8.22 | Wiederherstellungsstrategie dokumentiert |
| DORA Art. 11 | Recovery Time & Testing-Plan enthalten |
| FMA Punkt 4.3 | Kritische Systeme & Eskalationslogik vorhanden |

---

## 9. Nächste Schritte

- Integration in ISMS-Risikolandschaft (`control-selection-matrix.md`)
- Verknüpfung mit Incident Response Plan (Modul 1.2)
- Erstellung BCP-Testprotokoll-Vorlage (`templates/`)

---

**Letzte Revision:** 2025-07-26  
**Nächste Überprüfung:** 2026-01-15  
**Verantwortlich:** George K., ISB (interimistisch)
