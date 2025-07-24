# Azure Security Framework – Integration in das ISMS der FinSec GmbH

**Organisation:** FinSec GmbH  
**Modul:** 01_ISMS_Basics  
**Autor:** George K.  
**Version:** 1.0  
**Stand:** 2025-07-25

---

## 1. Zielsetzung

Dieses Dokument beschreibt die Integration von Microsoft Azure-spezifischen Sicherheitsmaßnahmen in das bestehende ISMS der FinSec GmbH. Es basiert auf dem Microsoft Cloud Adoption Framework (CAF), dem Zero Trust Modell sowie den Anforderungen aus ISO 27001, DORA und FMA.

---

## 2. Azure-Sicherheitsprinzipien

### 2.1 Zero Trust Architecture (ZTA)

**Grundsatz:** "Never trust, always verify."  
**Umsetzung bei FinSec:**
- Azure AD Conditional Access
- Multifaktor-Authentifizierung (MFA) für alle privilegierten Konten
- Per-App-Zugriffskontrollen
- Zugriff nur über vertrauenswürdige Geräte (Compliant Devices)

### 2.2 Identity & Access Management (IAM)

| Maßnahme | Tool | Umsetzung |
|----------|------|-----------|
| MFA für Admins | Azure AD | Aktiviert |
| Just-in-Time Access | Azure AD Privileged Identity Management (PIM) | Aktiv |
| Role-Based Access Control | Azure RBAC | Implementiert |
| Passwortschutz | Azure AD Password Protection | In Umsetzung |

---

## 3. Technische Maßnahmen (ISO-Mapping)

| Maßnahme | Azure Tool | ISO Control | DORA Relevanz |
|----------|------------|-------------|---------------|
| Logging & Monitoring | Microsoft Defender for Cloud, Sentinel | A.8.15 | Art. 16, 17 |
| Network Security | Azure NSG, Private Link | A.8.9, A.8.23 | Art. 12 |
| Data Protection | Azure Disk Encryption, TLS, Customer Managed Keys (CMK) | A.8.11 | Art. 6 |
| Backup & Recovery | Azure Backup Vault + Geo-Redundanz | A.8.22 | Art. 11 |
| Secure Baseline | Azure Security Center Baselines | A.5.1, A.6.3 | Art. 10 |

---

## 4. Rollenmodell (Beispiel FinSec Cloud Governance)

| Rolle | Verantwortung |
|-------|----------------|
| Cloud Security Officer | Technische Umsetzung, IAM-Policy |
| IT Compliance Officer | Überwachung der Umsetzung & ISMS-Dokumentation |
| System Owner | Fachliche Verantwortung je Ressourcengruppe |
| Azure Admin | Betrieb & Lifecycle-Management der Infrastruktur |

---

## 5. Governance-Integration

### 5.1 Richtliniendokumente (Policies)

- Azure Resource Naming Convention
- Azure Role Assignment Policy
- Azure Diagnostic Logging Policy
- Azure Retention Policy (z. B. Logs 180 Tage, Backups 30 Tage)

### 5.2 Policy Enforcement

- Einsatz von **Azure Policy** zum Durchsetzen:
  - Nur VM-Größen aus genehmigter Liste
  - Kein Public IP ohne Genehmigung
  - TLS-Version ≥ 1.2 erzwingen

---

## 6. Roadmap

| Phase | Maßnahme | Zeitraum |
|-------|----------|----------|
| Q3/2025 | CMK für Kundendaten aktivieren | August |
| Q4/2025 | Azure Defender für alle Ressourcengruppen | Oktober |
| Q4/2025 | Sentinel Alerts in SIEM integrieren | November |
| Q1/2026 | Compliance Dashboard für Cloud Security | Januar |

---

**Dokumentenklasse:** Vertraulich – Cloud Security  
**Letzte Revision:** 2025-07-25  
**Verantwortlich:** Cloud Security Officer (CSO), ISB
