# BCP-Testprotokoll Vorlage

**Organisation:** FinSec GmbH  
**Modul:** 01_ISMS_Basics  
**Dokumenttyp:** Template zur Durchführung und Nachweisführung von BCP-Tests  
**Erstellt von:** George K.  
**Version:** 1.0  
**Stand:** 2025-07-26

---

## 1. Testdaten

| Feld | Wert |
|------|------|
| Test-ID | BCP-2025-01 |
| Testdatum | [Datum einsetzen] |
| Testtyp | Technisch / Tabletop / Blackout |
| Beteiligte Systeme | [z. B. Core Banking, Zahlungsverkehr] |
| Leitung | [Name / Rolle] |
| Auditor / Beisitz | [Optional] |

---

## 2. Zielsetzung des Tests

Beschreibe hier:

- Ziel des Tests (z. B. Recovery-Zeit messen, Kommunikation prüfen)
- Relevante RTO-/RPO-Ziele aus `business-continuity.md`
- Referenz auf relevante Risiken aus der Risikoanalyse

---

## 3. Testablauf

| Schritt | Beschreibung | Verantwortlich | Zeit |
|--------|--------------|----------------|------|
| 1 | Ausfall simulieren (z. B. Zahlungssystem) | IT-Security | HH:MM |
| 2 | Alarmierung Incident-Team | SOC / ISB | HH:MM |
| 3 | Notfall-Backup aktivieren | Backup-Team | HH:MM |
| 4 | Wiederherstellung prüfen | Infrastruktur | HH:MM |
| 5 | Kommunikation auslösen | Kommunikationsstelle | HH:MM |

---

## 4. Ergebnisse / Abweichungen

| Ziel | Soll-Wert | Ist-Wert | Abweichung | Kommentar |
|------|-----------|----------|------------|-----------|
| RTO Core Banking | ≤ 4h | [Zeit] | [z. B. +30 min] | Ursache: Storage Recovery langsam |
| RPO Transaktionsdaten | ≤ 15min | [Wert] | [ok / Abw.] | Wiederherstellung aus Azure OK |
| Kommunikationszeit | ≤ 1h | [Wert] | [Abw.] | Stakeholderliste war veraltet |

---

## 5. Lessons Learned / Korrekturmaßnahmen

- [ ] Backup-Server Standort-Dokumentation aktualisieren
- [ ] Eskalationsmatrix automatisieren (LMS/Tool)
- [ ] SOP zur Krisenkommunikation überarbeiten

---

## 6. Abschlussbewertung

| Bewertungskriterium | Bewertung | Kommentar |
|---------------------|-----------|-----------|
| Testziele erreicht | Ja / Teilweise / Nein | – |
| Dokumentation vollständig | Ja / Nein | – |
| Wiederanlauf innerhalb RTO | Ja / Nein | – |
| Eskalation funktionierte | Ja / Teilweise / Nein | – |

---

## 7. Unterschriften

| Funktion | Name | Unterschrift | Datum |
|----------|------|--------------|--------|
| Testleiter | | | |
| Auditor | | | |
| BCP-Koordinator | | | |

---

**Nächste Aktualisierung:** Nach jedem BCP-Test
