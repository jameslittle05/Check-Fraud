# 🕵️‍♂️ Check Fraud & Social Engineering Simulation 🧠

This project simulates a real-world financial cybercrime scenario involving check fraud (commonly referred to as scamming or "bussing" accounts) and social engineering tactics used to manipulate individuals and organizations. Designed as a dual Red & Blue Team exercise, it explores offensive strategies for reconnaissance and exploitation, along with defensive methods for detection, prevention, and user awareness.

---

## ⚙️ Project Objectives

- Simulate real-life check fraud operations (e.g., bussing accounts)
- Demonstrate social engineering tactics (vishing, phishing, impersonation)
- Showcase detection and mitigation strategies (SIEM, IAM, training)
- Highlight business and personal risks involved in financial cybercrimes

---

## 🔴 Red Team (Attacker Simulation)

**Techniques Used:**

- Spear Phishing with fake check deposit emails
- Social Engineering: Impersonating bank representatives
- OSINT Recon: Gathering employee names and phone numbers
- Check Alteration Tactics
- BEC (Business Email Compromise) Simulation

**Artifacts:**

- `phishing_template.html`
- `impersonation_script.txt` (call scripts or chat templates)
- `osint_report.md`
- Screenshots of fake deposits/check templates (redacted/fake)

---

## 🔵 Blue Team (Defensive Simulation)

**Defensive Focus:**

- SIEM Detection Use Cases for Suspicious Transactions
- Email Filtering & EDR Configurations
- IAM Controls to Limit Access to Payment Systems
- Employee Awareness Training Modules

**Artifacts:**

- `SIEM_UseCase_DetectionRules.md`
- `IAM_HardeningChecklist.md`
- `AwarenessTrainingSlides.pdf`
- PowerShell script: `monitor-unusual-logins.ps1`

---

## 📊 Risk Analysis

Includes a mini case study on how real businesses fall victim to this fraud and what controls could have helped.

- `CaseStudy_FakeVendorFraud.md`
- `RiskMatrix_CheckFraud.xlsx`

---

## 🧠 Lessons Learned

- Importance of layered security in finance operations
- Human factor is often the weakest link
- Detection is useless without user education

---

## 🚨 Disclaimer

This is a simulated educational project. No real bank data or personal information is used. All scripts and templates are fictional and used for ethical training purposes only.

---

## 👤 Author

James B. Little  
Cybersecurity Analyst | IAM Enthusiast | Red Team Curious  
📍 Stone Mountain, GA  
📧 james.b.little@outlook.com  
🔗 [LinkedIn](https://linkedin.com/in/JamesBLittle5)

