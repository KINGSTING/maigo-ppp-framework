# Institutionalizing Dual-Use ICT Facilities

**A Public-Private Partnership Framework for Technical-Vocational Education in the Municipality of Maigo**

[![LaTeX](https://img.shields.io/badge/LaTeX-Project-008080?style=flat-square&logo=latex)](#)
[![Status](https://img.shields.io/badge/Status-Work_in_Progress-FFA500?style=flat-square)](#)

## 📌 Project Overview
This repository contains the LaTeX source code and research manuscript for a localized public policy proposal in the Municipality of Maigo, Lanao del Norte. 

The research addresses a dual-faceted socio-economic crisis: the severe deficit of Information and Communication Technology (ICT) laboratories for public Technical-Vocational Education and Training (TVET) programs (specifically at MSU-MCEST and TESDA), juxtaposed against the daytime underutilization and economic decline of local internet cafés (MSMEs).

### The Solution: "Dual-Use" via Service Contracting
Anchored in **Collaborative Governance** and the **Philippine Public-Private Partnership (PPP) Code (RA 11966)**, this study proposes a Zero-CapEx solution: the LGU leases private cybercafés during the day as accredited training micro-laboratories.

To ensure pedagogical integrity, the proposal mandates a **Diskless (PXE-Boot) Multiple Image architecture**. This allows the hardware to boot into a restricted, government-controlled "Educational Image" during academic hours—segregating recreational games—before reverting to "Commercial Mode" at night.

## 🗂️ Repository Structure
This project uses a modular LaTeX structure to prevent merge conflicts and maintain clean code.

```text
maigo-ppp-framework/
│
├── policy_research_main.tex    # The master file (handles formatting & includes chapters)
├── chap1_main.tex              # Chapter 1: Introduction
├── chap2_main.tex              # Chapter 2: Review of Related Literature
├── chap3_main.tex              # Chapter 3: Research Methodology
├── appendices_main.tex         # Research Instruments and Interview Guides
├── bibliography_policy.bib     # BibTeX citations file
└── README.md                   # Project documentation