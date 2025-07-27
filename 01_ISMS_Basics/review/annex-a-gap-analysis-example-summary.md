# GAP-Analyse ISO/IEC 27001:2022 – Annex A Controls (FinSec GmbH)

Diese GAP-Analyse dokumentiert den Umsetzungsstand aller 93 Kontrollen aus Anhang A der ISO/IEC 27001:2022 für das Projekt `from-zero-to-ciso` – Modul `01_ISMS_Basics` bei der FinSec GmbH. Die Analyse berücksichtigt bereits vorliegende Maßnahmen, z. B.:

- `isms-policy.md` (Informationssicherheitsrichtlinie mit Rollen, KPIs, Klassifizierung)
- `control-selection-matrix.md` (initiale Auswahl & Priorisierung)
- `incident-response-plan.md`, `business-continuity.md`, `azure-security-framework.md` (Umsetzung technischer & organisatorischer Controls)
- `isms-mini-audit.md` (Selbsteinschätzung ISMS-Reife)
- `awareness-program.md` (Awareness & LMS-Prozess)

## Statusübersicht der 93 Kontrollen (Stand: 2025-07-27)

| Status      | Anzahl Controls | Anteil  |
|-------------|------------------|---------|
| Erfüllt     | 31               | 33,3 %  |
| Teilweise   | 31               | 33,3 %  |
| Offen       | 31               | 33,3 %  |

## Kritische offene Punkte (TOP 5 Prioritäten)

1. **A.5.21 – IKT-Lieferkettensicherheit:** Drittdienstleister-Assessment unvollständig  
2. **A.8.9 – Konfigurationsmanagement:** Keine Richtlinien oder Prozesse dokumentiert  
3. **A.8.12 – Datenleckprävention:** Technische Umsetzung fehlt  
4. **A.8.27 – Sichere Systemarchitektur:** Noch keine Prinzipien definiert  
5. **A.5.29 – Informationssicherheit während Störungen:** BCP nicht vollständig integriert

## Visualisierung: Statusverteilung nach Kategorie

| Kategorie              | Erfüllt | Teilweise | Offen |
|------------------------|---------|-----------|-------|
| Organisatorisch (A.5)  | 12      | 12        | 13    |
| Personalbezogen (A.6)  | 3       | 3         | 2     |
| Physisch (A.7)         | 4       | 5         | 5     |
| Technologisch (A.8)    | 12      | 11        | 11    |

---

## Empfehlung zur weiteren Umsetzung

- GAPs mit **gesetzlicher Relevanz** (z. B. DORA, DSGVO, FMA) priorisieren  
- GitHub-Issues je Control anlegen (`control-id`, `status`, `evidenz`, `verantwortlich`)  
- Auditfähigkeit durch vollständige Referenzierung aller Controls auf ISMS-Dokumente sicherstellen  
- Lessons Learned aus BCP/IRP-Tests dokumentieren

**Nächste Revision:** Q4/2025 (vor interner Auditphase)  
**Verantwortlich:** George K., ISB (interimistisch)
