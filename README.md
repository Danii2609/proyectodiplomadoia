# Predicción de incumplimiento de DTN y semáforo día/noche (HGB)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Danii2609/proyectodiplomadoia/blob/main/InformeFinalIASalud.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Danii2609/proyectodiplomadoia/HEAD?labpath=InformeFinalIASalud.ipynb)
[![Codespaces](https://img.shields.io/badge/GitHub-Codespaces-blue?logo=github)](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=Danii2609%2Fproyectodiplomadoia)

Proyecto del diplomado — modelo **HistGradientBoosting (HGB)** con política **recall-first** y **semáforo operativo** (día: verde/amarillo/rojo; noche: verde/rojo) para priorizar pacientes con riesgo de **DTN > 60 min**. Incluye anexo exportable en Excel con rankings por hito.

---

##  Ejecución rápida

### A) Google Colab (recomendado)
1. Click en **Open in Colab** (badge arriba).  
2. **Runtime → Run all**.  
3. Verifica los anexos en `outputs/alto_riesgo_incumplimiento.xlsx`.

### B) Binder (sin cuenta)
1. Click en **Binder** (badge arriba).  
2. Abre `InformeFinalIASalud.ipynb` → **Run All**.

### C) GitHub Codespaces
1. Click en **Codespaces** (badge arriba).  
2. En la terminal:
   ```bash
   pip install -r requirements.txt
   jupyter lab --ip=0.0.0.0 --port=8888 --no-browser
