# ISMS Mini-Audit – Self-Assessment der FinSec GmbH

**Modul:** 01_ISMS_Basics  
**Autor:** George K.  
**Version:** 1.0  
**Letztes Update:** 2025-07-26  
**Vertraulichkeit:** Intern – Revision & Compliance

---

## 1. Ziel

Dieses Dokument dient der strukturierten Selbsteinschätzung der ISMS-Reife bei FinSec GmbH. Die Fragen orientieren sich an zentralen Anforderungen aus **ISO/IEC 27001:2022 (Annex A)**, dem **FMA-Rundschreiben 2019** und **DORA**.

Jede Zeile umfasst:

- Eine Prüffrage
- Den aktuellen Status (erfüllt / teilweise / offen)
- Verweis auf vorhandene Dokumentation
- Falls offen: geplante Maßnahme

---

## 2. Checkliste (Auszug: 12 Kernkontrollen)

| Nr. | Prüffrage | Status | Referenz | Maßnahme / Kommentar |
|-----|-----------|--------|----------|-----------------------|
| 1 | Gibt es eine durch Management autorisierte ISMS-Policy? | Erfüllt | `isms-policy.md` §1.1 | – |
| 2 | Existiert eine Risikobewertungsmatrix inkl. Akzeptanzgrenze? | Erfüllt | `isms-policy.md` §5.1 | – |
| 3 | Werden Incident-Meldungen innerhalb von 2h ermöglicht (DORA)? | Erfüllt | §10, `stakeholder-briefing.md` | – |
| 4 | Wurde ein BCP mit RTO/RPO definiert und dokumentiert? | Offen | – | Integration in `business-continuity.md` geplant |
| 5 | Sind Awareness-Trainings verpflichtend für alle Mitarbeitenden? | Teilweise | §7 | LMS-Anbindung noch offen |
| 6 | Gibt es eine Klassifizierung aller Informationen? | Erfüllt | §12 | 4-Level-Modell |
| 7 | Wird der Zugang zu Cloud-Ressourcen durch MFA geschützt? | Erfüllt | `azure-security-framework.md` §2.2 | – |
| 8 | Werden kritische Drittdienstleister sicherheitsgeprüft? | Offen | – | `third-party-risk.md` in Planung |
| 9 | Ist eine zentrale Logging- und SIEM-Struktur vorhanden? | Teilweise | `control-selection-matrix.md`, `azure-security-framework.md` | Sentinel-Integration offen |
| 10 | Existieren dokumentierte KPIs zur Sicherheitswirksamkeit? | Erfüllt | `control-effectiveness-metrics.md` | – |
| 11 | Gibt es eine dokumentierte Auditplanung? | Teilweise | `isms-mini-audit.md` | Review-Frequenz definieren |
| 12 | Sind Datenschutz-Folgenabschätzungen im ISMS integriert? | Offen | – | Modul 1.2 geplant (DSFA für AI/Cloud Systeme) |

---

## 3. Gesamtstatus (grafische Bewertung)

| Bereich                  | Status     |
|--------------------------|------------|
| ISMS Policy & Struktur   | ✅ stabil |
| Risikomanagement         | ✅ vorhanden |
| Awareness & Training     | ⚠️ im Aufbau |
| Cloud Security (Azure)   | ✅ integriert |
| BCP / BCM                | ❌ fehlt |
| Lieferantenmanagement    | ⚠️ in Planung |
| Auditfähigkeit           | ⚠️ Grundstruktur vorhanden |
| Datenschutz (DSGVO/DSFA) | ❌ noch offen |

---

## 4. ToDos für Version 1.2

- `business-continuity.md` erstellen
- Awareness-Prozess mit LMS-Anbindung definieren
- DSFA (Datenschutz-Folgenabschätzung) in Modul 1.2 vorbereiten
- Third-Party Risk Framework entwickeln (siehe Phase 2)

---

**Nächste Überprüfung:** 2025-10-01 (vor interner Auditphase)  
**Verantwortlich:** George K. (Interim ISB)  
