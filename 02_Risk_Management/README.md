# Modul 02 – Risk Management

**Ziel:**  
Dieses Modul dokumentiert die systematische **Identifikation, Bewertung und Behandlung von Informationssicherheitsrisiken** gemäß ISO/IEC 27005, DORA, DSGVO und FMA-Vorgaben.

**Anwendungsfall:**  
Die SecureBank AG bereitet sich auf ein internes Audit und eine ISO27001-Zertifizierung vor. Modul 02 liefert den methodischen Rahmen und die praktischen Tools zur Umsetzung der risikobasierten Steuerung.

---

## Ordnerstruktur

```plaintext
02_Risk_Management/
├── methodology/         # Methodik & Richtlinien (ISO27005, DORA)
├── templates/           # Vorlagen für Risikoanalyse & Bewertung
├── examples/            # Anwendungsbeispiele (z. B. Cloud-Migration)
└── README.md            # Diese Dokumentation
```

---

## Inhalt nach Themen

### Methodik (`methodology/`)
- `risk-assessment-methodology.md` → ISO-konformer Analyseprozess (5x5 Matrix, Review-Zyklus)
- `risk-management-policy.md` → Grundsätze, Verantwortlichkeiten, Schnittstellen
- `third-party-risk.md` → Bewertung ausgelagerter Dienstleister nach ISO A.5.10 & DORA Art. 28

### Vorlagen (`templates/`)
- `finance-specific-threat-catalog.csv` → Bankenspezifischer Bedrohungskatalog
- `risk-register-template.csv` → Vorlage für Risikoregister mit Impact × Likelihood
- `residual-risk-calculation.csv` → Berechnung der Restrisiken nach Maßnahmeneffektivität

### Beispiele (`examples/`)
- `cloud-migration-risk-assessment-example.csv` → Risikobewertung einer Azure-Migration

---

## Verbindung zu anderen Modulen

| Modul | Bezug |
|-------|-------|
| `01_ISMS_Basics` | Risikobasierte Control-Auswahl (`control-selection-matrix.md`) |
| `04_Compliance_Framework` | DORA/DSGVO-Risiken als regulatorische Pflicht |
| `05_Audit_Simulation` | GAP-Feststellungen basieren auf Risikoanalyse |
| `07_Continuous_Improvement` | Residual Risks fließen in KPIs & Lessons Learned ein |

---

## Zielkompetenzen nach Abschluss

Nach Bearbeitung dieses Moduls kannst du:

- Eine vollständige Risikoanalyse im Finanzumfeld durchführen
- Risiko-Register und Residual-Risiken berechnen
- Drittdienstleister gemäß ISO & DORA bewerten
- Risikobasierte Entscheidungen dokumentieren
- Risiken für Audits & Interviews argumentieren

---

**Nächste Revision:** 2025-12-31  
**Verantwortlich:** George K. – Projekt ISB  
