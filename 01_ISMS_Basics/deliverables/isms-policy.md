# Informationssicherheitsrichtlinie (ISMS-Policy)

**Version:** 1.1  
**Dokumentnummer:** ISMS-POL-001  
**Gültig ab:** 2025-07-23  
**Erstellt von:** George K.  
**Genehmigt durch:** [CISO oder Geschäftsleitung]  
**Modul:** 01_ISMS_Basics  
**Organisation:** FinSec GmbH

---

## 1. Zweck der Richtlinie

Diese Informationssicherheitsrichtlinie legt die übergeordneten Grundsätze, Ziele und organisatorischen Maßnahmen der FinSec GmbH zur Sicherstellung der Vertraulichkeit, Integrität und Verfügbarkeit von Informationen fest. Sie bildet die Grundlage für das Informationssicherheits-Managementsystem (ISMS) gemäß ISO/IEC 27001.

### 1.1 Management Commitment

Die Geschäftsleitung der FinSec GmbH bekennt sich ausdrücklich zur Informationssicherheit und stellt die notwendigen Ressourcen (Personal, Budget, Schulungszeit) für die Umsetzung, Aufrechterhaltung und kontinuierliche Verbesserung des ISMS bereit. Informationssicherheit ist als Führungsaufgabe in die Unternehmensstrategie eingebettet.

---

## 2. Geltungsbereich

Der Geltungsbereich des ISMS umfasst alle informationstechnischen Systeme, Prozesse und Mitarbeiter der FinSec GmbH, insbesondere:

- Online-Banking-Systeme
- Zahlungsverkehrsplattformen
- Core Banking Infrastruktur (Azure/On-Premise)
- Externe Dienstleister mit Zugriff auf geschäftskritische Daten
- Mitarbeiter an den Standorten Wien, Linz und Remote

---

## 3. Informationssicherheitsziele

Die FinSec GmbH verfolgt folgende übergeordnete Sicherheitsziele:

- Schutz vertraulicher Daten von Kunden, Partnern und Mitarbeitenden
- Sicherstellung der Integrität geschäftskritischer Systeme
- Aufrechterhaltung der Verfügbarkeit zentraler Services
- Erfüllung regulatorischer Anforderungen (ISO 27001, DORA, NIS2, DSGVO)

---

## 4. Rollen und Verantwortlichkeiten

| Rolle | Verantwortung |
|-------|---------------|
| Geschäftsleitung | Strategische Verantwortung, Ressourcenfreigabe |
| CISO / ISB | ISMS-Führung, Risikoüberwachung, Auditkoordination |
| IT-Abteilung | Implementierung technischer Kontrollen |
| Fachabteilungen | Umsetzung betrieblicher Sicherheitsvorgaben |
| Alle Mitarbeitenden | Informationssicherheit im Alltag umsetzen, Incidents melden |

---

## 5. Risikomanagement

Das Risikomanagement basiert auf einem standardisierten, iterativen Prozess gemäß ISO/IEC 27005. Risiken werden identifiziert, klassifiziert, bewertet und mit Maßnahmen behandelt.

### 5.1 Risikobewertungsmatrix

- **Impact:** Skala 1 (niedrig) bis 5 (katastrophal)
- **Likelihood:** Skala 1 (unwahrscheinlich) bis 5 (häufig)
- **Gesamtrisiko = Impact x Likelihood**
- Akzeptanzgrenze: **Residual Risk Score ≤ 12**
- Risiken über 12 müssen vom ISB eskaliert werden

---

## 6. Sicherheitsmaßnahmen (Annex A Controls)

Die Maßnahmen orientieren sich an ISO/IEC 27001:2022 (Anhang A). Eine Auswahl erfolgt risikobasiert und dokumentiert in der `control-selection-matrix.md`.

Maßnahmenkategorien:

- Organisatorisch: Sicherheitsrichtlinien, Personalmanagement
- Technisch: Verschlüsselung (AES-256), MFA, SIEM, Zero Trust
- Physisch: Zutrittskontrolle, Alarmanlagen
- Monitoring: Logging, IDS, Incident Tracking

---

## 7. Awareness und Schulungen

- Verpflichtende Grundlagenschulungen für alle Mitarbeitenden innerhalb von 30 Tagen nach Dienstantritt
- Jährliche Auffrischungen und Awareness-Kampagnen
- Simulierte Phishing-Kampagnen zur Wirksamkeitsprüfung
- Ergebnisdokumentation über Learning Management System (LMS)

---

## 8. Überwachung, KPIs und Kontrolle

Die folgenden Key Performance Indicators (KPIs) werden regelmäßig gemessen und im Management-Reporting dokumentiert:

| KPI | Zielwert |
|-----|----------|
| Phishing-Click-Rate | < 5 % |
| Kritische Incidents pro Quartal | ≤ 2 (RTO < 4h) |
| Verfügbarkeit Core Banking | ≥ 99,9 % |
| Awareness-Schulungsquote | 100 % innerhalb von 30 Tagen |
| SOC-Alarmbehebung | innerhalb 1 Stunde bei Priorität 1 |

---

## 9. Interne Audits und kontinuierliche Verbesserung

- Jährliche interne Audits
- Review aller Controls und Policies mindestens halbjährlich
- Audit-Feststellungen werden dokumentiert und über Maßnahmenpläne verfolgt
- Nutzung des PDCA-Zyklus zur Verbesserung des ISMS

---

## 10. Umgang mit Sicherheitsvorfällen

- Alle Incidents werden über ein zentrales Meldesystem erfasst
- Incident Response erfolgt gemäß internem Playbook
- Meldepflichtige Vorfälle werden innerhalb von 2 Stunden an FMA und Datenschutzbehörde übermittelt (gemäß DORA/DSGVO)

---

## 11. Revisionsverlauf

| Version | Datum | Autor | Änderung | Genehmigt durch |
|---------|--------|--------|-------------------------|-----------------|
| 1.0     | 2025-07-23 | George K. | Erstveröffentlichung | CISO            |
| 1.1     | 2025-07-25 | George K. | Management-Commitment, KPIs, Klassifizierung | CISO |

---

## 12. Datenklassifizierung

Die FinSec GmbH verwendet ein vierstufiges Klassifizierungsmodell:

| Klassifizierungsstufe | Beschreibung |
|------------------------|-------------|
| **Öffentlich (Public)** | Informationen ohne Vertraulichkeitsanforderung (z. B. Website) |
| **Intern (Internal)** | Interne Arbeitsdokumente, nicht öffentlich |
| **Vertraulich (Confidential)** | Kundendaten, Vertragsunterlagen, Finanzdaten |
| **Streng Vertraulich (Restricted)** | Board-Dokumente, sicherheitskritische Infrastruktur, CISO-Freigabe erforderlich |

Alle Informationen müssen bei Erstellung oder Eingang klassifiziert und entsprechend geschützt werden.

---

**Dokumentenklasse:** Vertraulich  
**Nächste Revision:** 2026-07-01
