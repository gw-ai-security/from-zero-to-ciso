# Fallstudie: SecureBank AG – Profil & Szenario

**Organisation:** SecureBank AG  
**Modul:** case_study/securebank-profile.md  
**Erstellt von:** George K.  
**Version:** 1.0  
**Stand:** 2025-07-27  
**Vertraulichkeit:** Intern – Projektkontext

---

## 1. Unternehmensprofil

- **Branche:** Finanzdienstleister (Online-Banking, Zahlungsverkehr, Vermögensverwaltung)
- **Größe:** ca. 1.500 MA, 250.000 KundInnen
- **Standorte:** Wien (Zentrale), Linz (Datacenter), Graz (Service Center)
- **Systemlandschaft:**  
  - Core Banking (Eigenentwicklung, Hybrid-Cloud Azure)
  - Zahlungs-API (SEPA, Instant Payments)
  - Mobile App & Kundenportal (Web, iOS, Android)
  - Drittdienstleister für SWIFT-Gateways, Cloud Backup

---

## 2. Regulatorisches Umfeld

- **ISO/IEC 27001** (ISMS als Zertifizierungsziel)
- **DORA (EU 2022/2554)** – besonders Art. 11, 17, 23
- **DSGVO (inkl. Art. 32, 33, 35)**
- **FMA-Rundschreiben 2019 – IT-Sicherheit**
- **Bankwesengesetz (BWG) §39 Abs. 6**

---

## 3. Ausgangssituation

Die SecureBank AG steht vor einem **internen ISO27001-PreAudit** und will bis Q2/2026 zertifiziert sein. Erste ISMS-Bausteine sind eingeführt (Policy, Incident Process, Awareness). Jedoch fehlen:

- Eine vollständige Risiko- und Control-Dokumentation
- Technische Evidenzen (Azure, Logging, BCP)
- Stakeholder-Briefings & Auditstruktur
- DORA-Integration in die Betriebsprozesse

---

## 4. Stakeholder (Auszug)

| Rolle | Interesse | Relevante Anforderungen |
|-------|-----------|-------------------------|
| CEO / Vorstand | Auditreife & Image | Statusberichte, KPIs |
| CISO / ISB | Umsetzung ISMS | Policy, Risiko, GAP-Analyse |
| IT-Leitung | Tech Controls & Azure Security | Logging, MFA, RBAC |
| HR / Compliance | Awareness & Offboarding | LMS, NDAs |
| Externer Auditor | Zertifizierung | ISO-konforme Dokumentation |
| Aufsicht (FMA, DSB) | Meldepflicht & Prozesse | Art. 17 DORA, Art. 33 DSGVO |

---

## 5. Use Case – Auditziel Q4/2025

> Die SecureBank AG wird einem simulierten **internen Audit** nach ISO 27001 Annex A unterzogen.  
> Ziel ist der Nachweis, dass:  
> - ein risikobasiertes ISMS eingeführt wurde  
> - technische & organisatorische Controls dokumentiert sind  
> - Awareness und Incident Response funktionieren  
> - DORA-Elemente wie 2h-Meldung, Outsourcing & BCP berücksichtigt wurden

---

## 6. Referenzierte Module

| Modul | Verbindung zur Fallstudie |
|-------|---------------------------|
| 01_ISMS_Basics | Policy, GAP, Azure, Awareness, Incident |
| 02_Risk_Management | Risikobewertung der Cloud-APIs |
| 03_Awareness_Campaign | Phishing-Pläne & LMS-Szenarien |
| 04_Compliance_Framework | DORA-, DSGVO-, FMA-Mapping |
| 05_Audit_Simulation | Interviewfragen, Beweisführung |
| 06_Technical_Controls | Azure PIM, Logging, Backup |
| 07_Continuous_Improvement | Lessons Learned, KPIs, PDCA |

---

## 7. Ziel der Fallstudie

Diese Fallstudie begleitet alle Module der Projektreihe **„from-zero-to-ciso“** als verbindendes Praxisbeispiel. Sie dient dazu:

- Lerninhalte in realistische Kontexte zu übertragen
- Transferkompetenz für Bewerbung & Auditgespräche zu dokumentieren
- Interviewantworten mit konkreten Praxisfällen zu untermauern

---

**Nächste Überprüfung:** Q4/2025 – vor internem ISO-Audit  
**Verantwortlich:** George K., Projekt ISB  
