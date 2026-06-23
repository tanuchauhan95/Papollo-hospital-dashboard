# Papollo Healthcare Analytics Dashboard

An end-to-end Power BI Business Intelligence solution developed to analyze healthcare operational efficiency, patient diagnostics, revenue leakage, and clinical performance metrics. This repository features an interactive dashboard backed by a dataset tracking thousands of detailed patient admissions.

---

## 📊 Dataset Profile & Attributes
The analysis is driven by the source dataset **`Papollo-Healtcare-Dataset.xlsx`**, which tracks operational and financial parameters across several clinical features:

* **Patient & Clinical Flow**: `Patient_ID`, `Admit_Date`, `Discharge_Date`, and `Followup Date` metrics to measure length of stay and readmissions.
* **Operational Demographics**: `Diagnosis` (Flu, Typhoid, Malaria, Viral Infections, etc.), `Bed_Occupancy` type (General, Private, ICU), and assigned `Doctor` tracking.
* **Diagnostic Tracking**: `Test` profiles including MRI, CT Scans, X-Rays, and Blood Tests.
* **Financial Data Engine**: Detailed performance arrays tracking total `Billing Amount` versus `Health Insurance Amount` coverage.
* **Quality of Care**: Patient feedback indexes calculated on a 1.0 to 5.0 rating scale.

---

## ⚙️ Repository Directory Architecture

To set up this workspace locally, ensure the project structure matches the layout below (extracted from **`Papollo (2).zip`**):

* **`Papollo-Healtcare-Dataset.xlsx`**: Raw relational source database tracking admissions, billing matrix configurations, and clinical outcomes.
* **`Papollo.pbix`**: Core Power BI application workspace housing data models, calculated DAX columns, relationships, and user interface panels.
* **`Report/Layout`**: Positional canvas schema metadata mapping multi-page structural alignments.
* **`StaticResources/`**: Graphical interface anchors, status flags, and custom UX assets (e.g., `happy-face`, `fever` status icons) powering conditional logic alerts.
* **`BaseThemes/`**: Configuration files detailing the master visual identity layout layout parameters (`CY24SU02.json`).

---

## 💡 Core Features & Analytical Focus

1. **Healthcare Financial Analytics**: Evaluates cross-sectional billing amounts against commercial health insurance profiles to isolate high-revenue diagnostic flows.
2. **Bed Efficiency Optimization**: Cross-evaluates Length of Stay (LOS) against room categories (`ICU` vs. `General` vs. `Private`) to minimize bottleneck constraints.
3. **Clinical Quality Audits**: Segments performance scores across specialized practitioners (`Doctor`) and diagnoses to locate quality variance trends.
4. **Custom Theme Engine**: Deploys professional typography, global design tokens, and contextual alert states customized using the `CY24SU02` structural template.

---

## 🚀 Installation & Execution

### System Requirements
* Windows OS with **Power BI Desktop** installed.
* [Download Power BI Desktop (Free)](https://powerbi.microsoft.com/desktop/)






<img width="1895" height="961" alt="Screenshot 2026-06-23 163708" src="https://github.com/user-attachments/assets/79783a41-a244-4dc8-98b5-27f8a4f64145" />
