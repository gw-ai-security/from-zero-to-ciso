# Incident Response Plan (IRP) – FinSec GmbH

**Modul:** 01_ISMS_Basics  
**Autor:** George K.  
**Version:** 1.0  
**Vertraulichkeit:** Intern – Sicherheitsrelevant  
**Stand:** 2025-07-26

---

## 1. Ziel

Ziel dieses Dokuments ist es, sicherzustellen, dass alle sicherheitsrelevanten Vorfälle bei FinSec GmbH **strukturiert, zeitnah und dokumentiert** behandelt werden. Die Vorgaben orientieren sich an:

- ISO/IEC 27001:2022 (A.8.21 – Incident Management)
- EU-Verordnung DORA (Artikel 17–20)
- DSGVO (Art. 33 – Datenschutzvorfälle)

---

## 2. Geltungsbereich

Der Plan gilt für alle IT-Systeme und Benutzer der FinSec GmbH, insbesondere:

- Core Banking Infrastruktur
- Online-Banking-Frontend
- Zahlungsverkehrssysteme
- Cloud-Dienste (Azure, SaaS)
- Kritische Schnittstellen (API, 3rd Party)

---

## 3. Definition Sicherheitsvorfall

Ein **Sicherheitsvorfall** ist jedes Ereignis, das:

- die Verfügbarkeit, Integrität oder Vertraulichkeit von Informationen beeinträchtigt
- gesetzlichen oder regulatorischen Meldepflichten unterliegt
- zu einem potenziellen oder realen Schaden führt

Beispiele:
- Ransomware-Angriff
- Phishing mit kompromittierten Zugangsdaten
- Datenleck bei Drittanbieter
- IT-Systemausfall durch Fehlkonfiguration

---

## 4. Rollen und Zuständigkeiten

| Rolle | Verantwortung |
|-------|----------------|
| Incident Response Manager (IRM) | Koordination, Dokumentation, Kommunikation |
| CISO / ISB | Entscheidung über Meldepflicht, Eskalation |
| IT-Security-Team | Technische Analyse, Eindämmung, Wiederherstellung |
| Fachabteilung | Bewertung des Business Impact |
| Datenschutzbeauftragter | DSGVO-Meldung, Kontakt zur Aufsichtsbehörde |
| Kommunikationsverantwortlicher | Externe Kommunikation (optional) |

---

## 5. Ablauf: Incident Handling Lifecycle

1. **Erkennung / Meldung**  
   - Durch SOC, Mitarbeitende, Monitoring-Systeme  
   - Meldung an incident@finsec.local oder Ticket-System

2. **Ersteinstufung**  
   - Klassifikation nach Kritikalität (hoch, mittel, gering)  
   - Prüfung auf DORA-/DSGVO-Meldepflicht

3. **Containment / Eindämmung**  
   - Sofortmaßnahmen (z. B. Netzwerktrennung, Account Lock)  
   - Snapshot-Erstellung für forensische Analyse

4. **Analyse & Behebung**  
   - Root Cause Analysis  
   - Wiederherstellung (ggf. gemäß BCP)

5. **Meldung an Behörden**  
   - DORA: binnen 2 Stunden an FMA  
   - DSGVO: binnen 72 Stunden an Datenschutzbehörde

6. **Kommunikation intern/extern**  
   - Stakeholder, Vorstand, ggf. Kunden  
   - Kommunikationsplan verwenden

7. **Nachbereitung / Lessons Learned**  
   - Abschlussbericht  
   - Ableitung von Maßnahmen  
   - ISMS-Anpassung (Policy, Controls)

---

## 6. Zeitrahmen & Fristen

| Pflicht / Vorgabe | Zeitfenster | Gesetz / Standard |
|-------------------|-------------|-------------------|
| Erste Incident-Erfassung | sofort / ≤ 30 Min | intern |
| DORA-Meldung an FMA | ≤ 2 Stunden | DORA Art. 19 |
| DSGVO-Meldung an Behörde | ≤ 72 Stunden | DSGVO Art. 33 |
| Interner Abschlussbericht | ≤ 5 Werktage | ISO A.8.21 |
| Maßnahmenumsetzung | ≤ 30 Tage | PDCA-Zyklus |

---

## 7. Dokumentation

Alle Vorfälle werden in einem zentralen Vorfallsregister dokumentiert. Pflichtangaben:

- Datum / Uhrzeit
- Art des Vorfalls
- Systeme betroffen
- Maßnahmen
- Kommunikationswege
- Lessons Learned
- Verknüpfte Risiken

---

## 8. Tests & Verbesserung

- IRP wird jährlich durch ein Incident-Response-Testevent überprüft
- Verbesserungen fließen in den PDCA-Zyklus des ISMS
- Ergebnisse werden im `isms-mini-audit.md` berücksichtigt

---

**Letzte Überprüfung:** offen  
**Nächste Revision:** spätestens Juli 2026  
**Verantwortlich:** CISO / IRM
