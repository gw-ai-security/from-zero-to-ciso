# FMA & EU Compliance Mapping für das ISMS der FinSec GmbH

**Organisation:** FinSec GmbH  
**Modul:** 01_ISMS_Basics  
**Autor:** George K.  
**Version:** 1.0  
**Stand:** 2025-07-25

---

## 1. Zielsetzung

Dieses Dokument verknüpft zentrale Anforderungen aus dem **FMA-Rundschreiben IT 2019**, der **EU-DORA-Verordnung** und der **DSGVO** mit implementierten Elementen des ISMS gemäß ISO/IEC 27001.

Ziel ist es, die **Regulatorik in den ISMS-Lifecycle** zu integrieren und die **Auditfähigkeit gegenüber Aufsichtsbehörden** wie FMA, OeNB und Datenschutzbehörde sicherzustellen.

---

## 2. Mapping-Matrix

| Regulatorik | Paragraph / Artikel | Inhaltliche Anforderung | ISO27001 Control / Policy-Kapitel | Status |
|-------------|----------------------|--------------------------|-----------------------------------|--------|
| FMA-Rundschreiben 2019 | Punkt 3.1 | IT-Strategie & Governance | ISMS-Policy §1.1, §4 | Erfüllt |
| FMA | Punkt 3.3 | Informationssicherheitsmanagement | Annex A / A.5–A.8 / Policy komplett | Erfüllt |
| FMA | Punkt 4.4 | Auslagerung & Dienstleister | A.5.10, A.5.23 | In Umsetzung |
| DORA | Art. 17 | Incident Reporting (2h) | A.8.21 + Policy §10 | Abgedeckt |
| DORA | Art. 11 | Business Continuity & Testing | A.8.22 | In Planung |
| DSGVO | Art. 32 | Technische & organisatorische Maßnahmen | A.8.11, A.8.15, A.8.4 | Erfüllt |
| DSGVO | Art. 33 | Meldung von Datenschutzverstößen (72h) | Policy §10 | Erfüllt |
| DSGVO | Art. 35 | Datenschutz-Folgenabschätzung | (Projektmodul 1.2) | In Vorbereitung |
| OeNB IT-Leitfaden | Abschnitt 2.1 | Kritische Geschäftsprozesse & Risiko | Policy §5, §8 | Erfüllt |
| BWG (Bankwesengesetz) | § 39 Abs. 6 | Ordnungsmäßigkeit der IT-Systeme | Gesamtes ISMS | Teilweise |

---

## 3. Priorisierte Lücken (Gap-Fokus)

| Regulatorik | Gap | Maßnahme | Priorität |
|-------------|-----|----------|-----------|
| FMA Punkt 4.4 | Keine strukturierte Lieferantenbewertung | Third-Party Risk Framework (Modul 2.5) | Hoch |
| DORA Art. 11 | BCP nicht dokumentiert | BCP-Integration mit RTO/RPO | Hoch |
| DSGVO Art. 35 | Keine DSFA-Prozesse | Modul 1.2: Datenschutz & AI Integration | Mittel |
| BWG §39 | Operational Risk Quantification unklar | Risikomodell erweitern | Mittel |

---

## 4. Weiterentwicklung

- Erweiterung des Mappings um EBA ICT Risk Guidelines (Modul 2.6)
- FMA-Auditvorbereitung (Fragebogen + Nachweise)
- Verknüpfung mit Control-Matrix (verlinkbar über ID)

---

**Dokumentenklasse:** Vertraulich – Regulatorisches Mapping  
**Nächste Aktualisierung:** Nach Gesetzesänderung oder Audit-Vorbereitung  
