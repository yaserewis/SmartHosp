# SmartHosp v0.0

**Open-source hospital patient file — print-ready, GAHAR-compliant, free for all.**

Built for Egyptian public hospitals. Designed around GAHAR accreditation standards. Released freely for any hospital to use, adapt, and improve.

---

## What is SmartHosp?

SmartHosp is a single HTML file containing a complete patient medical record — all forms needed from admission to discharge, organized by clinical stop. No installation, no internet connection, no database required.

Open the file in any browser. Enter the hospital name and logo once. Print the forms you need.

---

## Who is it for?

- Egyptian public and charity hospitals preparing for GAHAR accreditation
- Small and medium hospitals that cannot afford commercial HIS systems
- Any Arabic-speaking hospital needing bilingual clinical documentation

---

## What is included

| Stop | Forms |
|---|---|
| 🏥 Admission | Patient ID Band · Unified Consent (MR-03) · Registration (MR-01) · Nursing Assessment (MR-02) · Risk Scores (MR-04) |
| 📋 Daily Care | Progress Notes (MR-05) · Physician Orders (MR-06) · Investigation Results (MR-07) · Invasive Device Record (MR-15) · Nursing Care Plan (MR-NCP) · Medication Administration Record (MAR) |
| 🔬 Theater | Ward→Theater Handover (HO-WT) · Pre-op & Anaesthesia Record (PA-09) · WHO SSC Arabic (MR-08) · Circulating Nurse Record (MR-CN) · Count Sheet (COUNT) · Operative Note (MR-10) · PACU Record (MR-11) · Post-op Handover (HO-TW) |
| 🏠 Discharge | Transfer Record (MR-12) · Discharge Summary (MR-13) · Audit Trail (MR-14) |
| 🫀 ICU | ICU Daily Chart & Handover (ICU-01) |
| 💓 Cath Lab | Catheterization Record (CATH-01) |

**Separate files also included:**
- Obstetrics (10 forms — admission through postpartum discharge)
- NICU / PICU (5 forms)

---

## Key features

- **Single HTML file** — open in any browser, no installation
- **Bilingual** — English with Egyptian Arabic on nursing documents
- **Arabic consents** — MR-03 unified consent covers general, surgical, anaesthesia, cath, and obstetric consent in one Arabic document
- **WHO SSC** — official Arabic text from WHO 2009
- **GAHAR-tagged** — every form references its GAHAR standard (COP, ASC, NSR, PCC, IPC, MR)
- **Print by stop** — one button prints all forms for a clinical stop
- **No internet required** — runs completely offline after download
- **Hospital branding** — set hospital name and logo once, applies to all forms

---

## How to use

1. Download `SmartHosp.html`
2. Open in Google Chrome or Microsoft Edge
3. Click ⚙ → enter hospital name → upload logo → click Apply
4. Navigate to the stop you need
5. Click 🖨 to print all forms for that stop

For extra pages (MAR, progress notes, orders) — print the Daily Care stop again and take only the pages needed.

---

## GAHAR standards covered

| Code | Standard | Forms |
|---|---|---|
| ACC.1 | Admission | MR-01 |
| COP.1 | Initial assessment | MR-02 |
| COP.2 | Care planning | MR-NCP |
| COP.3 | Risk assessment | MR-04 |
| COP.6 | ICU care | ICU-01 |
| COP.8 | Anaesthesia | PA-09 |
| COP.9 | Handover / transfer | MR-11, MR-12, HO-WT, HO-TW |
| COP.10 | Discharge | MR-13 |
| ASC.5 | WHO Surgical Safety Checklist | MR-08 |
| ASC.6 | Pre-operative assessment | PA-09 |
| ASC.7 | Operative note | MR-10 |
| ASC.8 | PACU | MR-11 |
| PCC.1 | Informed consent | MR-03 |
| NSR.01 | Patient identification | ID-BLK |
| NSR.04 | Invasive device monitoring | MR-15 |
| NSR.13 | Medication administration | MAR |
| IPC.1 | Infection alert | ID band red marker |
| MR.1–5 | Medical record standards | All forms |

---

## Language policy

| Document type | Language |
|---|---|
| Patient consents (MR-03) | Arabic only — patient reads and signs |
| Patient registration (MR-01) | Arabic |
| Nursing documents | Bilingual — English / Egyptian Arabic |
| Physician documents | English |
| WHO SSC (MR-08) | Arabic — official WHO text |

---

## Notes on the WHO SSC

MR-08 uses the official WHO Surgical Safety Checklist Arabic text.
© World Health Organization, 2009. Reproduced for non-commercial health use.
Original: [WHO Surgical Safety Checklist](https://www.who.int/teams/integrated-health-services/patient-safety/research/safe-surgery)

---

## Status

**v0.0 — trial phase**

Currently in clinical trial at ELSALAM Charity Hospital, Egypt.
v1.0 will follow based on trial feedback.

Known trial focus areas:
- Do Arabic consents read naturally to Egyptian patients?
- Are writing line heights sufficient for handwriting?
- Which forms do staff skip in practice?
- Does the theater sequence flow correctly in the OR?

---

## Built by

**Dr. Yaser M. Ewis**
Anaesthesiologist — ELSALAM Charity Hospital, Egypt
GAHAR accreditation project lead

---

## License

MIT License — free to use, copy, modify, and distribute for any purpose including commercial use.

Attribution appreciated but not required.

---

## Contributions welcome

If you use SmartHosp in your hospital and identify gaps or improvements:
- Open an issue on GitHub
- Submit a pull request
- Or contact directly

Particularly welcome:
- Corrections to Egyptian Arabic terminology
- Additional specialty forms (paediatrics, orthopaedics, oncology)
- Translations to other Arabic dialects
- PHP/database backend integration

---

*SmartHosp — free clinical documentation for hospitals that need it most.*
