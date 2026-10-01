Hands-on workshop materials for the 2nd Symposium on Protein Design and Engineering (SPDE) pre-event workshop "AI for Protein Design", held October 5--6, 2026 at CNPEM, Campinas, Brazil.

Organized by: CNPEM | Supported by: RosettaCommons, Serrapilheira | Co-organizers: Fiocruz, EMS

Symposium website: https://pages.cnpem.br/spde/


## Overview

This workshop guides the participants through the use of pyrosetta to filter and evaluate protein designed by AI-driven protein design. The goals is to show how physics-based methods can be used in a enzyme design pipeline.

---

## Repository Structure

```
|-- README.md                        <-- This file
|-- LICENSE
| EnzDesPractical
  |-- Instructions
  |-- PyRosetta Notebooks
    |-- Task 1 - ThreadSequence.ipynb
    |   Design binders with RFdiffusion3 + LigandMPNN/solMPNN + ColabFold.
    |   Screens by ipTM, pLDDT, binder RMSD. Produces a ZIP of designs.
    |   
    |-- Task 2 - FastRelax comparison.ipynb
    |
    |-- Task 3 - AnalyzeLigandbinding.ipynb
    |
    |--- Task4 - Energy and structural metrics.ipynb
    |
    |--- Task5 - RunFastDesign.ipynb
    |
    |--- Task 6 - ddGcalculator.ipynb
    |
    |--- Bonus task: - Task 7 - Interfaceanalysis.ipynb
    |
```

Instructions
---
## Quick Start

### Requirements

- A Google account (for Colab)
- A free GPU runtime on Google Colab
- **PyRosetta academic license** (Notebook 2 only) -- register at [RosettaCommons](https://www.rosettacommons.org/software/license-and-download)

---
## License

This workshop material is provided for educational purposes. The notebooks and guides are released under the [MIT License](LICENSE). Third-party tools (PyRosetta) are subject to their own licenses.
