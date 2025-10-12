# Proyecto del diplomado — modelo **HistGradientBoosting (HGB)** con política **recall-first** y **semáforo operativo** (día: verde/amarillo/rojo; noche: verde/rojo) para priorizar pacientes con riesgo de **DTN > 60 min**. Incluye anexo exportable en Excel con rankings por hito.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Danii2609/proyectodiplomadoia/blob/main/InformeFinalIASalud.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Danii2609/proyectodiplomadoia/HEAD?labpath=InformeFinalIASalud.ipynb)
[![Codespaces](https://img.shields.io/badge/GitHub-Codespaces-blue?logo=github)](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=Danii2609%2Fproyectodiplomadoia)

 Datos
Incluidos en el repo: data/synthetic_stroke_candidates.csv.
El notebook carga por defecto desde ./data/.

Resultados / Anexos
Se exporta outputs/alto_riesgo_incumplimiento.xlsx con una hoja por hito:


### `requirements.txt`
```text
pandas>=2.0
numpy>=1.24
scikit-learn>=1.4
matplotlib>=3.8
xlsxwriter>=3.1
openpyxl>=3.1
shap>=0.44
