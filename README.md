# Ketcher
# MolWard - Chemical Sketcher Module

This repository hosts the standalone chemical drawing interface for **MolWard**, a SaaS platform for predicted drug stability and nitrosamine risk assessment.

## 🚀 Purpose
This module provides a professional-grade 2D molecular editor that allows users to draw chemical structures, which are then analyzed by the MolWard Python backend.

## 🛠 Integration
This editor is designed to be embedded in a Wix environment via an Iframe. 
- **Message Listener:** Listens for `getMolfile` from the parent window.
- **Data Output:** Returns a V2000/V3000 Molfile string.

## ⚖️ License & Attribution
This project utilizes the **Ketcher** standalone package developed by EPAM Systems.
- **License:** Apache License 2.0
- Ketcher is a trademark of EPAM Systems.
