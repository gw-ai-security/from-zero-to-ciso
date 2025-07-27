# Risikoanalyse-Methodik – SecureBank AG

**Modul:** 02_Risk_Management  
**Organisation:** SecureBank AG  
**Autor:** George K.  
**Version:** 1.0  
**Letztes Update:** 2025-07-27

---

## 1. Ziel

Dieses Dokument beschreibt die standardisierte Methodik zur Bewertung und Behandlung von Informationssicherheitsrisiken gemäß ISO/IEC 27005, DORA, FMA und NIS2.

---

## 2. Ablauf der Risikoanalyse (ISO-konform)

1. **Asset-Identifikation**
   - Kritische Systeme, Prozesse, Daten
2. **Bedrohungen und Schwachstellen ermitteln**
   - Technisch (z. B. Phishing, Ransomware)
   - Organisatorisch (z. B. fehlende Awareness)
3. **Risiko bewerten**
   - Matrix 5x5 (Impact × Likelihood)
   - Wertebereich: 1–25
4. **Behandlungsoption wählen**
   - Akzeptieren, Reduzieren, Vermeiden, Übertragen
5. **Maßnahmen planen**
   - Zuweisung von Controls
6. **Review / Reassessment**
   - Alle 6–12 Monate oder nach Incidents

---

## 3. Risikokategorien

| Kategorie | Beispiele |
|-----------|-----------|
| Technisch | Malware, DDoS, SQL Injection |
| Menschlich | Social Engineering, Fehlkonfiguration |
| Organisatorisch | Fehlende Prozesse, Auslagerungen |
| Regulierung | DSGVO, DORA, Meldeversäumnisse |

---

## 4. Bewertungsskala (5x5 Matrix)

| Impact \ Likelihood | 1 | 2 | 3 | 4 | 5 |
|----------------------|---|---|---|---|---|
| **1 – Gering**       | 1 | 2 | 3 | 4 | 5 |
| **2 – Mäßig**        | 2 | 4 | 6 | 8 | 10 |
| **3 – Mittel**       | 3 | 6 | 9 | 12 | 15 |
| **4 – Hoch**         | 4 | 8 | 12| 16 | 20 |
| **5 – Kritisch**     | 5 | 10| 15| 20 | 25 |

**Risikogrenze:** Score ≥ 12 gilt als behandlungspflichtig

---

## 5. Referenzierte Standards

- ISO/IEC 27005:2022
- DORA (Art. 9, 11, 15)
- FMA-Rundschreiben 2019
- NIS2

